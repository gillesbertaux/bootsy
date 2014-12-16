# Bootsy


Bootsy provides an organized folder structure for every aspect of a project. It contains versioning & templates folders to help you bootstrap and maintain your project. I also added some tools such as keynote templates, resets, RACI models, reports models for PMs. Also, I only pushed a file with the structure written in indentation.

See the Home Page : [http://gillesbertaux/bootsy](http://gillesbertaux.com/bootsy)

By the way, I am totally open to suggestions to improve and discuss Bootsy, feel free to post an issue or request a pull request. 


## V.1.0 - Improvements

- I created a bower package to run Bootsy in one command line.

## V.0.5 - Improvements

- Acording to your feedbacks I put .gitkeep files in every folder in order to commit the whole structure in the repository and allow pull requests. Therefore, I deleted the structure.md file since it has no use anymore.
- I deleted OLD folders, apparently people would do it naturally
- I deleted the majority of of the files in the DEV folder. I only keeped the Index.html and the assets folder. PHP, Ruby, projects etc. will now be generated thanks to the projectLaunch.md file. It contains all the command lines to initialize a project using mostly Yeoman.

## Milestones

- Deploy on Github Pages
- Deal with front/back dev

## Installing Bootsy with Bower

First install NPM and Bower :
`npm install -g bower`

Then install Bootsy package in your working directory :
`bower install bootsy`

## How it works

Bootsy is pretty simple, every side of a project has its folder. Each folder is structured and contains tools I found across the Web to properly bootstrap a project. Of course you won't use everything so just delete what has no use for you.

Almost every folder has a :

- MODELS folders : contains templates.
- .txt files with the naming convention for the folder.

The naming convention for every file is PROJECTNAME_FOLDER_Element_DDMM.ext

The core font for Bootsy is Open Sans [available here](http://www.google.com/fonts#UsePlace:use/Collection:Open+Sans)


### Audits

Audits contains all the files concerning your audit analysis if your project is a redesign for example.

### Brief 

Here you'll find everythin about the client's brief, the original project documents.

### Client folder

This folder is special, it only concerns the client. It requires Dropbox or Zapier with Basecamp. Basically, the idea is that everything you put in there is visible for the client. With Dropbox it is a shared folder and with Basecamp the client has access to the documents automatically uploaded thanks to Zapier.

### Design

Obviously, this folder is all about design, UX and UI. 

- A.D is for the art direction, the guidelines of the project (fonts, color scheme, etc.)
- SCREENS is for UI (PSDs or .Sketch). The folder is structured in ELEMENTS folders. ELEMENTS are pages, they can be ABOUT, WORK, INSCRIPTION, etc.
- SITEMAP is the tree structure of the site.
- WIREFRAMES is for the UX. The folder is structured in ELEMENTS folders. You'll also find a SHEETS folder for sketching. It contains sketching templates.

### Dev

- assets

	* css : In there you have 960 css grids, animations.css, font-awesome.css (from Bootstrap), a reset.css file, and a blank style.css file.
	* fonts : Fonts will contain all your fonts and the font-awesome font collection from Bootstrap.
	* img : Well, it is pretty much obvious.
	* js : This folder has IE7,8,9 js browser fixes, and Jquery files (1.9.1 & the latest).

- index.html with a proper HTML5 structure.
- projectLaunch.md that contains all the command lines to initialize a project using mostly Yeoman.

### Pitch

This folder will contains everything for your client presentations.

- KEY : all the keynote files here.
- MODELS : I created a clean template for keynote to help you make good looking presentations fast.
- PDF : Pdf exports here.

### Pm 

The project manager folder.

- SPECS : all the specs file. You'll find templates in MODELS.
- REPORTS : all the meeting reports. You'll find templates in MODELS.
- PLANNING AND BUDGET : XLS templates for GANTT planning and budget.
- RACI : Risk management spreadsheet. Contains a template in MODELS.
- CONTRACTS : All your contracts in there.
- DEPLOYMENT : Contains a checklist before deployment.

### Resources

- CLIENT RESOURCES : All the client documents other than the briefs. Has an ASSETS folder (images furnished, text documents for the site, etc.), and a BRAND GUIDELINES folder ( brand logo, font, color scheme).
- EXTERNAL RESOURCES : All the resource documents (studies, framework documentation, etc.)
- FONTS : Fonts used in the project.
- IMGs : Images collected for the project.
- TEAM INFO : Contains an excel with all the contact informations, or FTP access for example.

### Workflow Examples With IFTTT or Zapier

- Copy/Paste your project in Dropbox and e-mail every time you there is a change.
- Copy/Paste your project in Dropbox and put a message in Basecamp time you there is a change.
- Upload file on Basecamp every time a new file is added to your folder.

Also feel free to post workflows examples in the issues, I will push the good ones into the readme file.



