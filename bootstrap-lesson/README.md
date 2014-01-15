# SoBA Web Curriculum

### Lesson 3: Twitter Bootstrap

#### Overview

For this lesson you will be building pages from scratch to meet the specifications below, and you will be using Twitter Bootstrap to style those pages. Most of your work will be based of Bootstrap examples and the accompanying documentation. But don't just copy and paste! Tweak the sample code, change it, and understand it!

#### Instructions

Again, make sure you fork this repository to your own account and clone it like you did for the first two assignment.

Keep up the habit of branching in git, making your changes, and then merging back into your main branch. But this time, let's do something  more real-world. With git you can branch from a branch. Instead of branching from main, create a "development" branch first immediately after you clone the repository, and branch from this line when you edit the individual files.

In a real development environment, you often have a main branch that mirrors the currently deployed site. Then you have a development branch where active development takes place. From this line you create feature branches for individual changes, merging them into development as you finish them. Then, when a period of development is completed, you merge the development branch into master with all the included features and push it to your server.

#### Editing the HTML

There are four HTML files you'll be editing for this assignment. Edit them one at a time, each time branching to make your changes and then merging back into master when you are done, before going on to the next file.

1. index.html
2. about.html
3. signup.html
4. reports.html

You also have a css directory where you can place a global stylesheet used by all of your html pages.

And remember, use python's SimpleHTTPServer for viewing your pages!

#### Create a Website

For this assignment you will need to create the files from scratch. I've added an empty file for each page. You will generate all the HTML. 

You should base your HTML on the Bootstrap "Basic Template". In order to do this, you'll need to download the Bootstrap framework to your computer. Use the directory structure we discussed in class: 3rd party code that you do not edit goes in a /lib directory such as /lib/js or /lib/css, while css code you edit goes in /css.

Don't forget the [HTML shim](http://en.wikipedia.org/wiki/HTML5_Shiv) inlcuded with Bootstrap, and don't forget to edit the template to take into account the directory structure we've set up.

#### Navigation and Container

Each page should have a working Bootstrap-based navigation bar with links to all the other pages that also indicates the current page, as in Assignment 2. Each page should also have a container div that contains the rest of the page.

#### Index.html

The index is the front landing page for our site. Use the jumbotron component and featurette components to highlight the site. Make up marketing copy (text) for a data analysis firm. For images, use the holder.js file Bootstrap makes use of in its examples.

#### About.html

Create an about page that describes the business and the team. Add images for team members. The images should be circles, but don't edit square images. Use Bootstrap's support for making a rectangular image appear circular. Again, make up the copy (text contents).

#### Signup.html

Create a sign up page for the product. Create a form using Bootstrap's form classes. Your sign up form should require an email address and password. No username and no password confirmation field. Include a signup button.

#### Reports.html

The reports page is where your customers go to view the data reports available to them. Use Bootstrap's grid system to create a two column layout. The left column is the sidebar (width:4) that contains a [List Group](http://getbootstrap.com/components/#list-group) component. The right column is the main content area (width:8) and should include a sample report or chart. If you're feeling brave, try incorporating one of the examples from [D3.js](http://d3js.org/).