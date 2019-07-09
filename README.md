# Feed Reader Testing

## Table of Contents

* [Overview](#Overview)
* [Instructions](#Instructions)

## Overview

The .zip file includes:
- static html file
- css styling
- JavaScript files (including Jasmine feedreader file)

To test the code, navigate to your local copy of index.html and open it in your browser. At the bottom of the page, you can see if tests were successfully completed or failed.

## Instructions

Jasmine 3.3.0 reads feedreader.js file that contains all of the tests, including:

1. RSS Feeds test:
    - tests to make sure that the allFeeds variable has been defined and that it is not empty
    - loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty
    - loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty
2. The menu test:
    - ensures the menu element is hidden by default
    - ensures the menu changes visibility when the menu icon is clicked
3. Initial Entries:
    - ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container
4. New Feed Selection:
    - ensures when a new feed is loaded by the loadFeed function that the content changes

For more information regarding Jasmine, refer to http://jasmine.github.io/
