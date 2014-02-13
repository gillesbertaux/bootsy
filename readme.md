# Bootsy

Bootsy provides an organized folder structure for every aspect of a project. It contains versioning & templates folders to help you bootstrap and maintain your project. I also added some tools such as keynote templates, resets, RACI models, reports models for PMs. Also, I only pushed a file with the structure written in indentation.

By the way, I am totally open to suggestions to improve and discuss Bootsy, feel free to post an issue or request a pull request. 

## How it works

Bootsy is pretty simple, every side of a project has its folder. Each folder is structured and contains tools I found across the Web to properly bootstrap a project. Of course you won't use everything so just delete what has no use for you.

Almost every folder has a :

- OLD folders : with the previous versions.
- MODELS folders : contains templates.$
- .txt files with the naming convention for the folder.


### AUDITS

Audits contains all the files concerning your audit analysis if your project is a redesign for example.

**Status : Maybe a template spreadsheet could be useful as a framework**

### BRIEF 

Here you'll find everythin about the client's brief, the original project documents.

### CLIENT FOLDER

This folder is special, it only concerns the client. It requires Dropbox or Zapier with Basecamp. Basically, the idea is that everything you put in there is visible for the client. With Dropbox it is a shared folder and with Basecamp the client has access to the documents automatically uploaded thanks to Zapier.

### DESIGN

Obviously, this folder is all about design, UX and UI. 

- A.D is for the art direction, the guidelines of the project (fonts, color scheme, etc.)
- SCREENS is for UI (PSDs or .Sketch). The folder is structured in ELEMENTS folders. ELEMENTS are pages, they can be ABOUT, WORK, INSCRIPTION, etc.
- SITEMAP is the tree structure of the site.
- WIREFRAMES is for the UX. The folder is structured in ELEMENTS folders. You'll also find a SHEETS folder for sketching. It contains sketching templates.

### DEV

- _if bootstrap project : It is bascially the latest version of Bootstrap.
- _if php project : In case you want to deploy a CMS, this folder contains header.php, index.php, sidebar.php, footer.php.  
- _if ruby project : This folder has a ROR project already initiated.
- assets

	* css : In there you have 960 css grids, animations.css, font-awesome.css (from Bootstrap), a reset.css file, and a blank style.css file.
	* fonts : Fonts will contain all your fonts and the font-awesome font collection from Bootstrap.
	* img : Well, it is pretty much obvious.
	* js : This folder has IE7,8,9 js browser fixes, and Jquery files (1.9.1 & the latest).

- index.html with a proper HTML5 structure.

### MARKETING

- AQUISITION : Contains a SEO/SEA/SOCIAL folder. 
- BENCHMARK : All your benchmark assets for the project.

**Status : Maybe a ketword/seo/sea template spreadsheet could be useful. Also I am not sure about the benchmark folder here.**

### PITCH

This folder will contains everything for your client presentations.

- KEY : all the keynote files here.
- MODELS : I created a clean template for keynote to help you make good looking presentations fast.
- PDF : Pdf exports here.

### PM 

The project manager folder.

- SPECS : all the specs file. You'll find templates in MODELS.
- REPORTS : all the meeting reports. You'll find templates in MODELS.
- AGENDA : all the meeting agendas. You'll find templates in MODELS.
- PLANNING AND BUDGET : XLS templates for GANTT planning and budget.
- RACI : Risk management spreadsheet. Contains a template in MODELS.
- CONTRACTS : All your contracts in there.
- DEPLOYMENT : Contains a checklist before deployment.

### RESSOURCES

- CLIENT RESSOURCES : All the client documents other than the briefs. Has an ASSETS folder (images furnished, text documents for the site, etc.), and a BRAND GUIDELINES folder ( brand logo, font, color scheme).
- EXTERNAL RESSOURCES : All the ressource documents (studies, framework documentation, etc.)
- FONTS : Fonts used in the project.
- IMGs : Images collected for the project.
- TEAM INFO : Contains an excel with all the contact informations, or FTP access for example.

### Workflow Examples With IFTTT or Zapier

- Copy/Paste your project in Dropbox and e-mail every time you there is a change.
- Copy/Paste your project in Dropbox and put a message in Basecamp time you there is a change.
- Upload file on Basecamp every time a new file is added to your folder.

Also feel free to post workflows examples in the issues, I will push the good ones into the readme file.



