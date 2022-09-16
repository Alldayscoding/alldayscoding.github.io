---
layout: post
title: 2022-Aug-31 coding study note.
---

* The definition of Sanitizer in python from PyPI.
 - Learned PyPI (The Python Package Index) is a repository of software for Python
 - Why HTML Sanitizer? because CSS technic can be hidden. 

* What is API?
 - Application Programming Interface.
 - print, format, etc they are Python's API
 - Being development cycle, Learning, making, achieve, vulnerability scanning and upgrade/patch so on.

* Learned Web framework
 - the problem is for CGI is too heavy and slow. 
 - alternative matrial is "Web framework" like Django, Flask, Tornado..
 - I choose Django as my framework as per popularity statistics. Django is 1st popular web framework

* study plans updated
 - Framework, Django
 - Database, MySQL to connect my webserver
 - Crawling. Library using <urllib, Beatutiful soup>
 - Github. Find out trend of APIs. what's new, what's hot

* Learned how to set up environment python web application with Bitnami WAMP.
  - Configured httpd.conf file in conf folder to enable py extention file and excute CGI.
  - troubleshooted errors in error.log files to identify cgi error.
* Used Atom as editor but switched back to Visual Studio code.
  - because indent feature is more powerful when save the py file in VS
* cgi.FieldStorage
  - when data coming through from HTML, FieldStorage class creates an instance to store user data to form(FieldStorage object)
* Form method GET vs POST
  - GET method is being cached
  - GET method can save browser history
  - GET method has length restricted
  - DO NOT USE GET method when dealing with sensitive data
* Using redirection
  - remove all other print()
  - print("Location: index.py?id=" + title) # redirection code

Reference: 
https://opentutorials.org/course/3256/19836
