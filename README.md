sass-boilerplate
================

#### A boilerplate to get you started with SASS in your projects.

*********************************************************************************

This repository has been created to standardize the front-end development through SilverStripe.

Copy the `/sass` and `/css` folders along with the `config.rb` file into your `/themes/mytheme/` directory.
Rename the `yourprojectname.scss` to your project's name. 

Run `compass compile` from the command line to recompile the css files. 

Add this into the `<head>` of your Page.ss file using the require tag `<% require themedCSS(yourprojectname) %>`

