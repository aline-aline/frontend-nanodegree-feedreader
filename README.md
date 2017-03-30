# Feedreader - Javascript Testing + TDD
##### Udacity FEND Feedreader (Project 6)

This project from the Udacity Frontend Developer Nanodegree is about app testing with Jasmine.

The Feedreader is a javascript RSS-Feed reader.

## How to use it
* Use the live version at [https://aline-aline.github.io/frontend-nanodegree-feedreader/](https://aline-aline.github.io/frontend-nanodegree-feedreader/index.html)
* Download the Git Repo and open `index.html` in a browser.

## Jasmine Tests

##### Test Suite 'RSS Feeds'
* The allFeeds variable is defined and not empty (there are feeds available)
* Feeds have a URL provided
* Every feed has a name provided

##### Test Suite 'The menu'
* Menu bar is hidden by default
* Menu bar gets visible by click on the menu toggle icon and gets invisible again on another click

##### Test Suite 'Initial Entries'
* At least one entry element is within the feed-container

##### Test Suite 'New Feed Selection'
* Checks if the content of the feeds actually changes when a new feed is loaded