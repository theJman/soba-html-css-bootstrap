# SoBA Web Curriculum

### Lesson 2: CSS & Twitter Bootstrap

#### Overview

You will continue to practice CSS in this lesson, focusing on layout. But you will quickly move to Twitter Bootstrap and leverage its predefined syltes to produce complex, responsive layouts for your webpages.

#### Instructions

Make sure you fork this repository to your own account and clone it like you did for the first assignment.

This is also a great chance to get into the habit of branching in git, making your changes, and then merging back into your main branch. There are two HTML files you'll be editing for the CSS portion of this assignment and four for the Bootstrap portion. Edit them one at a time, each time branching to make your changes and then merging back into master when you are done, before going on to the next file.

Your workflow might look like:

	git checkout -b columns-changes
	# make your changes
	
	git add .
	git commit -m "completed columns assignment"
	
	git checkout master
	git merge columns-changes
	# changes now merged back into master
	
	git branch -d columns-changes 
	# deletes the branch
	
	# if at any point you are confused about using git, try:
	git status
	git help
	

And be sure to use python's SimpleHTTPServer for viewing your pages:

	cd soba-html-css-bootstrap
	python -m SimpleHTTPServer

#### Assignemnt 1: CSS

Complete the remaining CSS files in the *css-lesson* directory:

1. navbar.html
2. columns.html

#### Assignment 2: Bootstrap based website

Complete the files in the *bootstrap-lesson* directory:

1. index.html
2. about.html
3. signup.html
4. reports.html

For this assignment you will need to create the files from scratch. I've added an empty file for each page. You will generate all the HTML. 

You should base your HTML on the Bootstrap "Basic Template". In order to do this, you'll need to download the Bootstrap framework to your computer.

Don't forget the [HTML shim](http://en.wikipedia.org/wiki/HTML5_Shiv) inlcuded with Bootstrap, and don't forget to edit the template to take into account the directory structure you're using.

Work together and refer to the Twitter Bootstrap documentation when you need help.

[http://getbootstrap.com/](http://getbootstrap.com)

#### Navigation and Container

Each page should have a working Bootstrap-based navigation bar with links to all the other pages that also indicates the current page, as in the earlier *navbar* assignment. Each page should also have a container div that contains the rest of the page.

#### Index.html

The index is the front landing page for our site. Use the jumbotron component and featurette components to highlight the site. Make up marketing copy (text) for a data analysis firm. For images, use the *holder.js* file Bootstrap makes use of in its examples.

#### About.html

Create an about page that describes the business and the team. Add images for team members. The images should be circles, but don't edit square images. Use Bootstrap's support for making a rectangular image appear circular. Again, make up the copy (text contents).

#### Signup.html

Create a sign up page for the product. Create a form using Bootstrap's form classes. Your sign up form should require an email address and password. No username and no password confirmation field. Include a signup button.

#### Reports.html

The reports page is where your customers go to view the data reports available to them. Use Bootstrap's grid system to create a two column layout. The left column is the sidebar (width:4) that contains a [List Group](http://getbootstrap.com/components/#list-group) component. The right column is the main content area (width:8) and should include a sample report or chart. If you're feeling brave, try incorporating one of the examples from [D3.js](http://d3js.org/).