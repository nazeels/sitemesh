sitemesh
========

A working sample for Sitemesh 2 reference.

## Feature:

Parameter based decorator selector.

## Usage

Deploy the the folder to Tomcat (or any servlet container) (Devlopmet environment: Tomcat7 on JDK 1.7)


* Check 1: http://localhost:9000/sitemesh/data/menu.jsp
* Check 2: http://localhost:9000/sitemesh/data/menu.jsp?decorator=en

enjoy the difference

_________
Basic project and documents can be accessed on: http://wiki.sitemesh.org/display/sitemesh/Home


PS: sitemesh.xml is the file to modified to choose decorator based on parameter or User agent or a few more in the list, and 
the tricky part is ordering of element in the xml file is important, else it wont't work as expected 

