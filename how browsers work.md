**Introduction**

A web browser or frequently called as browser is an application software that is installed on a computer to provide access to the World Wide Web.  The browser’s main functionality is to fetch the files from the server and to display them on the screen.
A browser is a group of structured codes that performs plenty of tasks to display a webpage on the screen. These codes are separated in to different components according to their tasks performed.

**The Browser Structure**

I.	*User Interface* – It is the space where interaction between users and the browser occurs. Most of the browsers have common inputs for user interface. Some of them are - an address bar, next and back buttons, buttons for home, refresh and stop, options to bookmark web pages, etc.

II.	*Browser Engine* – It is the piece of code that communicates the inputs of user interface with the rendering engine. It is responsible for querying and manipulating the rendering engine according to the inputs from various user interfaces.

III.	*Rendering Engine* – It is the part thoroughly responsible for displaying the requested content on the screen. It first parses the html tags and then using the styles, it builds a render tree and finally a render layout, which displays the content on the screen.

IV.	*Networking* – The fraction of the code written in the browser, responsible to send various network calls. For example sending the http requests to the server.

V.	*Java Script Interpreter* – It is the component of the browser written to interpret the java script code presented in a web page.

VI.	*UI Backend* – This draws basic widgets on the browser like combo boxes, windows, etc.

VII.	*Data Storage* – It is small database created on the local drive of the computer where the browser is installed. This database stores various files like cache, cookies, etc.

**How it actually works**

When we type in a URL or click on a link and hit the Go button. Now, the page requested to browser would probably be located on a Server computer far away.
The web browser program sends a request to a web server program running on the remote computer, the server program, gathers the request from the web browser, tries to hunt for the web page and then formulates a response. 
This response will differ depending on whether the server program was able to find the requested web page or web file. Assuming, the server was able to locate the web page, it sends the HTML file to the web browser. The browser picks up all the information coming in from the server and does its best to display the web page.
 A typical web page not only has text but also images and these are separate files that need to be transferred from the server to the browser.
So the browser-server communication goes on till all the files have been transferred to the browser. Once the files arrive at your computer, the browser- server connection is terminated. If you now click on any link on this web page or even refresh the page, the process starts all over again.  This is the client-server architecture .


http://www.webdevelopersnotes.com/basics/how_do_web_browser_work.php

http://fieldguide.andrewbrinker.com/browsers/
