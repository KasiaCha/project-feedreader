# Feed Reader Testing Project

## About the Feed Reader

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/).

## How to run this project?

- Download the project to a local folder and run index.html.

## How to change feeds or add a new feed?

- Changing the list of feeds requires editing the variable allFeeds in js/app.js in the app directory.

## List of tests

1. A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
2. A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
3. A new test suite named "The menu".
4. A test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
5. A test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
6. A test suite named "Initial Entries".
7. A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
8. A test suite named "New Feed Selection".
9. A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

## Dependencies

This project was created based on Udacity Feed Reader code: https://github.com/udacity/frontend-nanodegree-feedreader.