# Datatables
This repository contains source on how to integrate a Panther grid screen with Bootstrap datatables.

# Prerequisite:
  * Panther Web 5.5*
  * Apache  Web Server

# This repo consists of the following files:
  * main.css
  * pyordr.html
  * pyordr.jpl
  * pyordr.js
  * cookiedb.lib
  * bootstrap_headers.zip
  * cookie database file
  
# Cookiedb.lib
This library ontains the Panther grid screen. Pyordr.html is attached as a HTML template.

# Pyordr.jpl
Jpl code which is included in the Panther screen. 

# Pyordr.html
This is the HTML template that is included in the Panther screen. The HTML will generate a user-defined UI for the screen. Main.css and pyordr.js are referenced in the HTML template.

# bootstrap_headers.zip
Please unzip  this file . Make sure SMPATH  points to the location of this file . SMPATH is configured in your Panther Web ini. This folder contains multiple bootstrap Javascript and CSS files which are  referenced in a file called icmsHeader.html and icmsFooter.html. These files are being referenced in pyordr.html which loads the datatables.

# cookie database file
JDB database containing  data used to populate Panther Grids/Datatables.

If you wish to generate PDF reports from this Panther screen, please visit our other repository: https://github.com/ProlificsPanther/Report-Writer

Video for Report Writer and Datatables: https://youtu.be/qk_K2Jd9Aco

Need a Panther Web 551 Redhat Image? [Click Here](https://hub.docker.com/r/prolificspanther)

Contact support@prolifics.com for a 45 day license.

How to setup a Panther Servlet Web Application? [Click Here](https://github.com/ProlificsPanther/PantherWeb/releases)
