# Project Overview

Using [Jasmine](http://jasmine.github.io/), create various tests for a RSS Feed Reader Application.

# Launching the Application

Download or clone this repository, and open index.html in your browser.

### For Windows Command Prompt/Powershell:

    cd frontend-nanodegree-test-suites
    start index.html

### For OSX:

    cd frontend-nanodegree-test-suites
    open index.html

# Project Instructions

* Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
*  Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
*  Write a new test suite named `"The menu"`.
*  Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
*  Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
*  Write a test suite named `"Initial Entries"`.
*  Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
*  Write a test suite named `"New Feed Selection"`.
*  Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
*  No test should be dependent on the results of another.
*  Callbacks should be used to ensure that feeds are loaded before they are tested.
*  Implement error handling for undefined variables and out-of-bound array access.
*  When complete - all of your tests should pass. 

