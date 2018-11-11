**UdaciFeeds**
==============
Project 4 for Udacity FEND Program

*About*
=======
Hello! This is a fairly simple app, showing the benefits of test-driven development using Jasmine for JavaScript testing.

*Get Started*
=============
Getting started is simple - download the files and open the index.html file in your browser. Jasmine is already integrated, and you should see all of the tests (seven total, detailed in the next section) passing if you scroll to the bottom of the page.

Play around with it! Go into the /js/app.js file and start tinkering with the code, commenting out lines of feed names, urls, etc. Refresh your browser and you should see some of the tests failing. 

*Tests*
=======
The current Jasmine feedreader.js file tests for seven features: 
1) Checks that the allFeeds variable is defined and not an empty array.
2) Checks that each allFeeds object has a URL listed.
3) Checks that each allFeeds object has a name listed.
4) Checks that the menu bar is hidden on default. 
5) Checks that the menu hides when its icon is clicked.
6) Checks that there's at least one .entry element in the .feed container when loadFeed() has completed. 
7) Checks that the content changes when a new feed is selected.

*Dependencies*
==============
This app was created with HTML/CSS, JavaScript, and the Jasmine JS framework for testing.