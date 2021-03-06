REST Assist
===========

REST Assist is released under the MIT license. It is simple and easy to understand and places almost no restrictions on what you can do with REST Assist.
[More Information](http://en.wikipedia.org/wiki/MIT_License)

This is a simple page that will allow you to make ajax requests usng GET, POST, PUT, and DELETE to test a REST interface.  It was made with JSON responses in mind so it first tries to parse the response as JSON, if that fails, it will simply display the response as HTML.  If the repsonse is JSON, then it will render a nice tree with the results with icons denoting the value type.

How To Use
==========
Paths & Dependencies
--------------------
This tool uses [MooTools 1.4](http://mootools.net/download) so if you have this in your site already, simply change the path to point to it.  If you want to store the CSS, images, and Javascript elsewhere, just edit that paths in the html file and CSS to reflect the new location.  It's using `document.id` so it "should" play nice with other frameworks.

URL
---
Enter a URL and click the button for the request method you want

Data
----
This is a simple key value pair to send with the request.  To add a new line, simply hit TAB in the Value input.

All variables are stored using localStorage so you don't have to re-enter data on page reload.

![Alt screenshot](https://github.com/theiviaxx/RESTAssist/blob/master/i/screenshot.png?raw=true)
