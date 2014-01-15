# SoBA Web Curriculum

### Lesson 2: CSS & Twitter Bootstrap

#### Overview

You will continue learning CSS in this lesson, focusing on layout. But you will quickly move to Twitter Bootstrap and leveraging its predefined syltes to produce complex, responsive layouts for your webpages.

#### Instructions

Make sure you fork this repository to your own account and clone it like you did for the first assignment.

This is also a great chance to get into the habit of branching in git, making your changes, and then merging back into your main branch. There are two HTML files you'll be editing for CSS portion of this assignment and four for the Bootstrap portion. Edit them one at a time, each time branching to make your changes and then merging back into master when you are done, before going on to the next file.

Your workflow might look like:

	git checkout -b columns-changes
	# make your changes
	
	git commit -am "completed columns assignment"
	
	git checkout master
	git merge columns-changes
	
	git branch -d columns-changes 
	# deletes the branch
	
	# if at any point you are confused about using git, try:
	git status
	git help
	

Be sure to use python's SimpleHTTPServer for viewing your pages!

Look at the HTML files themselves for specific instructions. I suggest you work in the following order:

1. index.html
2. selectors.html
3. navbar.html
4. columns.html

Finally, also review the Twitter Bootstrap documentation for the next lesson. We'll be going over it in detail.

[http://getbootstrap.com/](http://getbootstrap.com)