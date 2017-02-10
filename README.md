# static-website
#########################################
WELCOME TO THE README FILE FOR CSE 3901
FACULTY PAGE RESDESIGN FOR R.WENGER
#########################################

#########################################
PROJECT AUTHORED BY STRUCT BY_LIGHTNING
#########################################

@authors Tania Prince, Chenyang Wang, Dragan 
Pantic, Cameron Mitchell, and Daniel White.

#########################################
PROJECT DESCRIPTION
#########################################

This project is a faculty member's 
website from the computer science 
department. It has been redesigned to HTML5
and CSS3 standards. We chose R. Wenger's 
Website.

Original Site URL:
http://web.cse.ohio-state.edu/~wenger/

#########################################
THIS PROJECT REQUIRES MIDDLEMAN
#########################################

GEMS/INSTALL COMMAND

$ gem install middleman

##########################################
HOW TO RUN THE PROJECT
#########################################

First run the command- $ bundle exec middleman build
inside a terminal window. This command generates
the static site content from the source files in the
source directory. This content is output to the build
directory.

Then issue command - $ bundle exec middleman server
This command will allow you to view the site on your
computer by typing localhost:port# inside your browsers 
url. 

Default URL: http://0.0.0.0:4567/

##############################################
ABOUT THE SITE
##############################################

The source directory contains all the necessary files
such as html pages images stylesheets and all other 
site specific info. Inside the layouts folder you
will find partials for nav and footer. This allows
for a uniform website across all pages.

Build will use all html.erb files in source and 
create .html files for each. Also uses any neccesary
images, stylesheets other directories needed for site.

##########################################
DIRECTORY STRUCTURE
#########################################

BUILD
---------------------------------------------
cse2331 - Content referenced on CSE 2331 page
images - Images for entire site
papers - Papers referenced throughout the site
publications - Publications referenced throughout the site
stylesheets - CSS files
contact.html - Contact page
cse2331.html - CSE 2331 page
index.html - Home/Main page
officehouse.html - Office hours page
publications.html - Publications page

SOURCE
---------------------------------------------
cse2331 - Content referenced on CSE 2331 page
images - Images for entire site
layouts - Layouts for site generation
	_footer.erb - layout for footer include file
	_navigation.erb - layout for nav include file
	layout.erb - main layout for site
papers - Papers referenced throughout the site
publications - Publications referenced throughout the site
stylesheets - CSS files
contact.html.erb - Content for contact page
cse2331.html.erb - Content for CSE 2331 page
index.html.erb - Content for home/main page
officehours.html.erb - Content for office hours page
publications.html.erb - Content for publications page
