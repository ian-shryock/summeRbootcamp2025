# summeRbootcamp2025
 Here’s a rough guide to the process I used to create the site this year. No promises this will work perfectly on your first try given my experiences navigating updates to Hugo and Netlify. Hopefully this will make the process much smoother. 
In terms of timing, I was able to make these changes in a single 8-hour workday in 2025. In 2024 there were more extensive changes (i.e., migrating the website to a new design template) that took me closer to four 8-hour workdays. If you’re more experienced at building and deploying websites via GitHub than me, you can probably make quick work of this. If you’re new to it, it would be preferable to allot yourself more time. 

1.	Create new repository from previous site:
a.	Go to https://github.com/ian-shryock/summeRbootcamp2025
b.	Select Code > Download Zip 
c.	Unzip folder and rename it to summeRbootcamp2026
2.	Make that folder a new repo in GitHub Desktop
a.	Open GitHub Desktop
b.	Go to File → Add local repository….
c.	Select the unzipped summeRbootcamp2025 folder.
d.	GitHub Desktop will say “This does not appear to be a Git repository.” → click Create a repository here.
i.	Give it the name you want (summeRbootcamp2025).
ii.	Add a description if you like.
iii.	Leave the rest as defaults.
iv.	Click Create repository.
e.	Now you’ll see a blue “Publish repository” button at the top.
i.	Click it.
ii.	Choose the Owner (you or your org).
iii.	Set visibility (Public).
iv.	Hit Publish.
f.	Add public/ to .gitignore
i.	Tip: Use Command + Shift + . to see the hidden files
3.	Login or create an account with Netlify
a.	Select a project name that you like as the URL
b.	Deploy the site
c.	Visit the URL to ensure that it deploys
4.	Create and use a GitHub fork to make all changes
a.	That way, you can easily revert them if things get messed up
5.	View the local rendering of the site before making changes
a.	From your finder, locate Users/GitHub/summeRbootcamp2025
b.	Open uobootcamp2025.Rproj (***Always start by opening this file***)
c.	Run: blogdown::serve_site()
i.	This allows a view of the changes you make prior to rendering on Netlify
ii.	End with: blogdown::stop_server()
iii.	As you make changes, you’ll need to use: blogdown::build_site() to execute the changes on your local files before you can see them enacted with blogdown::serve_site()
iv.	blogdown::check_site() allows you to locate files that need troubleshooting when the site can’t run
6.	Start by editing “content/_index.md” 
a.	Edit the year and dates
b.	Run:
i.	 unlink("public", recursive = TRUE)
ii.	blogdown::hugo_build()
iii.	blogdown::build_site() 
iv.	blogdown::serve_site()
c.	Push the changes to GitHub!
d.	Deploy these changes via Netlify and verify that you can see them on the published site
7.	Edit the rest of “content/”
a.	All of the  “_index.md” files in these subfolders render the pages. 
b.	Edit all of them to have up to date information
c.	Then run:
i.	unlink("public", recursive = TRUE)
ii.	blogdown::hugo_build()
iii.	blogdown::build_site() 
d.	Push to Github and render site via Netlify
8.	Edit site name
a.	Config/_default/hugo.yaml
9.	Edit Slides
a.	Slides are in static/slides
b.	Open each RMD file, make the changes, then knit the file
c.	Preview the files to ensure the changes are correct
i.	Note that you’ll need to add .png files of everyone’s headshots to static/slides/images to include them in the first set of slides

