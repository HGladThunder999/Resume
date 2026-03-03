## Resume Hosting using a Static Site Generator

The purpose of this repository is to create a resume using a static site generator and host it using GitHub pages. Static site generators allow to create a site that requires no back-end or server side programming.

This project makes use of Hugo static site generator. Hugo is a static site generator written in the GO Language. It is used to generate a site within seconds.

Git, a version control system was used to manage the different versions of the project. Moreover, git allowed to work with github via the command line. Most of the code uploaded to the repository was done using Git in the command line. 

In order to Edit and create `.toml` and `.md` files VSCode was used. The `.toml` file which is the configuration file of the website was edited using VSCode in order to make use of the theme `ananke` Which is a program that makes it easier for us to write different programs.

GitHub is a forge, Which are website used to collaboratively work on projects. A component of Github is Github pages which is used to deploy the code in the repository. The deployed code by default is hosted on `https://GITHUBUSERNAME.github.io/PROJECTNAME/` 

## Set of Pre-requisities

1) GitHub Account:
   required to view the project and deploy the project using a local GitHub repository 
2) Git installed on personal system:
   In order to clone, commit to, or add to, the repository Git must be needed
3) Hugo installed on personal system:
   In order to make changes to the site and for them to be visible in the deployment of the website, Hugo is required on the local system.
4) Visual Studio Code (optional):
   In order to add further content to the generated website, Having VSCode is much more organized and efficient however the files. 

In order to host the website on a local machine, download the repository and then use the public folder's contents to host the website. In order to perform this a github account is required. If contribution to the project is to be made then an elementary level of Git is required. making use of GIT using command prompt or gitBash


## Set of Instructions 
##### Option - 1: Downloading as a ZIP file
If you dont want to work with Git, then you can download the project as a ZIP folder, and mannually change the files without using command prompt.  
- **Step - 1**
Locate the green button titled code.
- **Step - 2**
Make sure the dropdown under the local window appears.
- **Step - 3**
Select the  `Download Zip`.
- **Step - 4**
From the file manager extract the folder.
- **Step - 5**
Make use of the `public` folder present in-order to host from your end.

If you wish to host the downloaded file, then on any hosting service, upload the folder `/docs` to it.

##### Option - 2: Cloning the repository
If you wish to contribute to the project, you will need to make use of git and clone the repository on your local system.
- **Step - 1**
Using git bash or the command prompt type the following command

`git clone https://https://github.com/HGladThunder999/Resume.git`
- **Step - 2**
change the directory to Resume using the command:

`cd Resume`
- **Step - 3**
In order to add a new post type the command :

`hugo new content content/posts/NEWFILE.md`

Then head over to the quickstart directory and type the following command in order to view you new content on the website:

`hugo server -buildDrafts`

If you wish to preview the site then type the following command:

`hugo server`

In order to generate the website type the command `hugo` while in the quickstart directory. Then rename the public folder to docs if you wish to host using github pages or upload the public folder to any forge or hostring service to host the site.
- **Step - 4**
In order to edit a pre-exisitng content type the command:

`cd content\posts`

suppose you want to open the `File.md` file you wish to edit and, if you are using VSCode type the command:

`code File.md`

if you dont want to use VSCode type the command:

`File.md`

Save the changes made and navigate to the quickstart folder and run the following command

`hugo server`

If you wish to deploy these changes type head over to the `quickstart` directory, and then type the following command 

`hugo`

Then delete the docs folder:

`rmdir /s/q docs`

Rename the new `public` folder generted by hugo:

`ren public docs`

Headover to the quickstart directory and type the following 
`git add .`

`git commit -M "Making changes on the website"

`git push`
Once these changes are commited then github automatically deploys them 

## Further Resources/Readings 

[Markdown Tutorial](https://commonmark.org/help/tutorial/)

[About static site generators](https://www.cloudflare.com/en-gb/learning/performance/static-site-generator/)

[compehensive directory of static site Generators](https://jamstack.org/generators/)

[hugo documentation](https://gohugo.io/documentation/)

[Video on how to create a website using Hugo and deploy using github](https://youtu.be/zrmeOu8DYyw?si=WVW8nuCYE4d8Bat3)

[Basic Git Command](https://www.atlassian.com/git/glossary)123

## FAQ
1. What is Markdown?

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Lightweight markup languages are languages that are used to define the structure of a document and are easy to learn

3. Do I need coding experience?

Coding experience is not required, However a basic knowledge of git is required if you wish to contribute to the project

4. Why use Hugo?

Because hugo is fast and flexible

4. Can I host this somewhere else?
Yes on the following:
- Hostpapa
- Netlify
- wix
- siteground
- etc.

6. What if GitHub Pages is not working?
Make sure you are in the correct branch from the pages option of the settings of your repository for this site `main` was used, and make sure the correct folder is selected for this website specifically `\root` was used

## Credits:
[Resource used to create the site](https://youtu.be/zrmeOu8DYyw?si=WVW8nuCYE4d8Bat3)
[Resource used for markdown](https://www.markdownguide.org/cheat-sheet/)
[Resource used for Git](https://www.reddit.com/r/git/comments/zuq54x/a_beginners_guide_to_git_a_comprehensive/)









