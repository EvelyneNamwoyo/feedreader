# feedreader
feedreader is a web-based application that reads RSS feeds. The aim of the project is to write unit tests for the web-based application.
### Test suits 
 1. A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
 2. A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
 3. A test that ensures the menu element is hidden by default.
 4. A test that ensures the menu changes visibility when the menu icon is clicked.
 5. A test that ensures when the loadFeed function is called and completes its work, there is at least a single ".entry" element within the     ".feed" container.
 6. A test that ensures when a new feed is loaded by the "loadFeed" function that the content actually changes

## Getting Started
The following instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
### Prerequisites

The following are things you need to have on your machine
* Browser(preferably chrome)
* IDE(sublime/visual studio code)
* GIT

### Installing
This is a step by step process of how to get a development environment running.
1. Open your terminal and change to a directory where you want the project to live.
2. Clone the project using git clone **https://github.com/EvelyneNamwoyo/feedreader**

## Running tests
To run the tests, open the index.html in your browser.
