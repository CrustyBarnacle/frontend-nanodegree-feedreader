# Project Overview

A simple RSS reader needs to have tests written to confirm it works as expected, and that future code changes do not break existing functionality. The tests that need to be written have been described, thankfully, by the previous developer (really by the Udacity instructors) in detailed TODOs in each test suite section.

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


## How to use this project?

1. Download or clone this project: https://github.com/CrustyBarnacle/frontend-nanodegree-feedreader
2. Open the ```index.html``` file in your browser.
3. The tests will be displayed at the bottom of the page

You may review the application and testing code in the following files:

* The application to be tested is provided in ```/js/app.js```.
* Testing code is in ```/jasmine/spec/feedreader.js```.
* The main structure and elements are in ```index.html```.

### The Test Suites

Each section of tests is in it's own *suite*, and is __not__ dependent on any other section/suite of code (a requirement for this project). This helps limit the scope, and the amount of complexity in each section. Keeping the sections independent of one another also promotes thorough testing, and will let you know how much you've really broken if/when you do :wink:.

#### RSS Feeds
Confirms that the the ```allFeeds``` variable has been defined and that it is not empty.

#### The Menu
Ensures the menu element is hidden by default.

#### Initial Entries
Tests that when the ```loadFeed``` function is called and completes its work, there is at least ones ```.entry``` element within the ```.feed``` container.

#### New Feed Selection
Test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

## Resources Used

* The original [Udacity course Github repository code](https://github.com/udacity/frontend-nanodegree-feedreader)
* [Jasmine 2.0 Documentation](https://jasmine.github.io/2.2/introduction)
* The succint [Feedreader Walkthrough by Matthew Cranford](https://matthewcranford.com/feed-reader-walkthrough-part-1-starter-code/)
* [Udacity Javascript Testing](https://www.udacity.com/course/javascript-testing--ud549) online course
