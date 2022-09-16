---
layout: post
title: 2022-Aug-30 coding study note.
---

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
