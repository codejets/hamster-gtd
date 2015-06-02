Hamster-GTD
===========

Organize your documents and workflow. An ultra-simple implementation of [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done)<sup> 1</sup><sup> 2</sup>, using:

- [Twitter](https://twitter.com/)'s concept of *#* and *@* as the basis of the project folders notation.
- [SemVer](http://www.semver.org/) for file versioning.
- Hamster-note<sup> 6</sup> for workflow management in Evernote.

###So, how can you start?

**Organize your documents:**

- [Main folder](#main-folder)
- [Project folders](#project-folders)
- [Files](#files)
- [How to navigate through your documents](#how-to-navigate-through-your-documents)
- [Others](#others)

**Organize your workflow:**

- [Actions and briefings](#actions-and-briefings)
- [Cabinet](#cabinet)

---
###// Organize your documents

===
####Main folder:

First of all create a folder in a safe place of your disk.
ALL your stuff will be stored here<sup> 3</sup>. 

- main folder: **YOUR NAME**

		Rename this folder with your name or/and surname using ALL CAPS.
        Example: JOHN

- project status: **{ }**

        Inside your main folder there are 3 folders:

        {inbox} is the folder where you put new documents until deciding what to do with them.
        {current} is the folder where you store your current projects.
        {archive} is the folder where you store your archived projects.
    
- project scope: **[ ]** 

        Inside:

        {inbox} there aren't permanent folders, just temporary stuff.
        {current} there are 2 folders: [personal], [work]
        {archive} there are 2 folders with archive symbol: +[personal], +[work]

        Inside these folders with project scopes you will store your projects.

===
####Project folders:

*# bundle @ project . subproject - folder - nested folder*

- bundle of projects (inspired in twitter hashtag): **#**

        Inside folders [personal], [work] you can have bundles of projects:
        Example: #large investor (bundle with all projects of a client)
        Example: #family (bundle with all your family related projects)

- project<sup> 4</sup> (inspired in twitter mention): **@**

    	Inside folders [personal], [work] or bundles you have projects:
        Example: @house in lisbon

        To reduce the need of memorization, when naming the project folder
        you can also add the bundle name (if existent):
        Example: #large investor@house in lisbon

- subproject (inspired in object oriented programming): **.**

    	Inside projects you can have subprojects:
        Example: .building permit

        To reduce the need of memorization, when naming the subproject folder
        you can also add the project name:
        Example: @house in lisbon.building permit

- folder (each nesting level): **-**

    	Inside subprojects you can have folders:
        Example: -plans

        On nested folders you can add previous folder(s) name to reduce the need of memorization:
        Example: -drawings-sections
        Example: -drawings-details-wall

===
####Files:

- files named using folders logic or other naming system relevant to your job.

        Example using folder's naming logic: plan+0.1.2
        Example using other naming system: @ARC.EXE-plan+0.1.2

- archived file using [SemVer](http://www.semver.org/) (each version *adds* a change on data): **+ major . minor . patch** 
        
        Example: plan+0.1.2

- prefix for standard / boilerplate files: **$**

        Example: $curriculum+1.1.2  

===
####How to navigate through your documents:

- you only need 2 *permanent desktop shortcuts* to navigate your documents: 

        Shortcut to {inbox}
        Shortcut to {current}

        If you use it often (in theory you don't, they are archived projects):
        Shortcut to {archive}

- and some *temporary desktop shortcuts* to specific folders that you use a lot.

===
####Others:

- use camelCase, PascalCase, snake_case or spaces:

        Example using camelCase: #largeInvestor@houseInLisbon
        Example using PascalCase: #LargeInvestor@HouseInLisbon
        Example using snake_case: #large_investor@house_in_lisbon
        Example using spaces: #large investor@house in lisbon  

- but avoid these symbols for regular naming: **# @ . - + $ % { } [ ]**

- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).

---
###// Organize your workflow

===
####Actions and briefings:

- in GTD, undivisible tasks are called *actions*. A list of actions is called *briefing*<sup> 5</sup>. Actions and briefings are managed in Evernote using Hamster-note<sup> 6</sup>.

- if you need to detail an action: **( )**

        Insert a comment: (comment)
        Example: Write a mail to Susy (your comment here)

        Insert a strict date: (year-month-day=hour)
        Insert dates in the beggining of the line to allow chronological sorting:
        Example: (2012-11-29=9h) Doctor appointment

        Insert a starting date: (date >) or 
        Example: (2014-12-10 >) Waiting for client feedback after this date

        Insert a deadline date: (date <)
        Example: (2014-12-10 <) Pay electricity bill

- prefix for a finished action (before delete or store it): **%**

        Use it in the beggining of the line to allow sorting:
        Example: % going to bank

####Cabinet:

- to simplify and optimize your workflow, your project references and notes are always stored here (not inside project folders). They are managed in Evernote using Hamster-note<sup> 6</sup>.

- name your notes using project folders notation:

        Note with all references regarding a particular subproject:
        Example: @house in lisbon.building permit

- use notes to keep your bookmark collections. It will allow easy access and share:

		Example: #resources@frontend.bootstrap
---
<sup>Notes:</sup><br>
<sup>1 - Without understanding GTD, this system will not make much sense.</sup><br>
<sup>2 - Hamster-gtd was tested in a Windows PC and Evernote.</sup><br>
<sup>3 - The hamster cheeks :)</sup><br>
<sup>4 - In GTD any document belongs to a project.</sup><br>
<sup>5 - Innovation by Hamster-gtd.</sup><br>
<sup>6 - Hamster-note is a variant of [Secret Weapon](http://www.thesecretweapon.org/media/Manifesto/The-Secret-Weapon-Manifesto.pdf).</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">hamster-gtd</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://enioferreira.com/" property="cc:attributionName" rel="cc:attributionURL">Enio Ferreira</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.