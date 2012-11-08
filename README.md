BootstrapScaffoldMVCTemplates
=============================

Visual Studio Scaffolding templates for Twitter Bootstrap.


Overview
--------

This templates are meant to complement the "MVC 4 TwitterBootstrap Starter Layout Page (Razor)" developed by J Sakamoto.
The files contained in this project will tell Visual Studio to create the scaffolding views in accordance to Twitter Bootstrap 
CSS rules and make them work with Sakamoto's layout page.




Installation
------------


Follow the instructions at J Sakamoto's project [site](http://visualstudiogallery.msdn.microsoft.com/268d0b05-6ba5-4793-9a10-7d9d2a478881 "MVC 4 TwitterBootstrap Starter Layout Page (Razor)")
 before using this Visual Studio templates.

Continue with this steps to install the templates in one of your Visual Studio projects.

1. Download the files or clone the project from it's [github repository](https://github.com/carlosblanco/BootstrapScaffoldMVCTemplates "BootstrapScaffoldMVCTemplates").
2. Copy the "CodeTemplates" folder and all its content to the root directory of the sources in your Visual Studio project. Make sure the name of the folder stays "CodeTemplates".
3. Copy the "bootstrap-validation.js" javascript file to your projects "Script" folder.

Usage
-----
Once the templates are intalled in one of your projects. You can use them in the following two ways.

1. **Creating a new controller and all its corresponding views.**
  1. Right click on the Controllers folder and select Add -> Controller.
  2. Fill the name of the new controller.
  3. Select "MVC Controller with read/write actions and views, using Entity Framework" from the "Template" dropbox.
  4. Select your Model and Data Context clases.
  5. Click Add. 


2. **Creating one view at a time for an existing controller.**
  1. Right click on the Views folder for a controller that you have created previously.
  2. Fill the name for the new View.
  3. Select the Model class which the new view will be for.
  4. Select the type of view from "Scaffold Template" dropbox.
  5. Click Add.

Screenshots
-----------
**Index view**

![Index view](https://raw.github.com/carlosblanco/BootstrapScaffoldMVCTemplates/master/Docs/Images/IndexView.png)

**Edit view**

![Edit view](https://raw.github.com/carlosblanco/BootstrapScaffoldMVCTemplates/master/Docs/Images/EditView.png)

**Delete view**

![Delete view](https://raw.github.com/carlosblanco/BootstrapScaffoldMVCTemplates/master/Docs/Images/DeleteView.png)
