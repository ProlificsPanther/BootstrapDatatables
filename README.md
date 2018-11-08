# Datatables
This repository contains source on how to integrate a Panther grid screen with Bootstraps datatables.

# Pre-Requisite:
  * Panther Servlet/Apache
  * anther ini file for the Panther Web application

# This repo consists of the following files:
  * main.css
  * pyordr.html
  * pyordr.jpl
  * pyordr.js
  * cookiedb.lib
  * bootstrap_headers.zip
  * cookie
  
# Cookiedb.lib
This library that contains the Panther grid screen. Pyordr.html attached as the HTML template.

# Pyordr.jpl
Jpl code that  is included in the Panther screen. 

# Pyordr.html
This is the HTML template that is attached to the Panther screen so as to generate a user-defined UI for the screen. Main.css and pyordr.js are referenced from HTML template.

# bootstrap_headers
Please unzip  this file  and have it pointed to by SMPATH in your Panther Web ini. This folder contains multiple bootstrap Javascript and CSS files which are being called in a file called icmsHeader.html and icmsFooter.html. These two files are being referencd in pyordr.html which loads the datatables.

# cookie
This is the JDB database containing  used to  populate Panther Grids/Datatables.

If you wish to generate PDF reports from this Panther screen, please visit our other repository: https://github.com/ProlificsPanther/Report-Writer

Video for Report Writer and Datatables: https://youtu.be/qk_K2Jd9Aco

For further queries: support@prolifics.com
