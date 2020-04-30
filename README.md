# Panther with Bootstrap Datatables
This sample contains a responsive Panther Grid/Bootstrap Datatable screen. The sample also demonstrates a JQuery Click event on a row.
Below is the screenshot of the completed Login screen in the Brower. Most of the HTML and js was generated by the Panther Migration Utility. Bootstrap libraries were used to transform the plan screen into a modern, responsive screen. JPL validation and SQL functionality remain the same. Some of the JPL was rewritten in Javascript.
![](pyordr.PNG)

# Prerequisite
  * Panther Web 5.5* 

# This repository consists of the following files
  * main.css
  * pyordr.html
  * pyordr.jpl
  * pyordr.js
  * pyordr.scr
  * next.scr
  * cookie database file
  
# pyordr.scr
Panther screen containing a grid. Pyordr.html is attached as an HTML template.

# next.scr
The Next Panther screen

# Pyordr.jpl
JPL code which is included in the Panther screen. 

# pyordr.html
HTML template that is included in the Panther screen. The HTML will generate a user-defined UI for the screen. Main.css and pyordr.js are referenced in the HTML template.
Our Migration Utility(Panther 5.52)  was used to generate this HTML template

# pyordr.js
Javascript File created by the Panther Migration Utility containing references to Bootstrap libraries, making it a responsive web screen.
The Javascript at the bottom of this file will allow a user to make a row click on the DataTable, fetch the row data and at the same time submit the Panther Screen utilizing a hidden pushbutton.

# cookie database file (to populate data)
JDB database containing data used to populate Panther Grids/Datatables.

NNeed a Panther Web 552 Redhat Image? [Click Here](https://hub.docker.com/r/prolificspanther/pantherweb "Named link title") 

[Click Here](https://prolifics.com/panther-trial-license-request/ "Named link title") for a 45-day license.

How to set up a Panther Servlet Web Application? [Click Here](https://github.com/ProlificsPanther/PantherWeb/releases "Named link title")

Read our Documentation [here](https://docs.prolifics.com)
