# FEND FeedReader Test

It is a web-based application that reads RSS feeds. In this project testing is being performed using the [Jasmine](http://jasmine.github.io/) Test Framework. Jasmine is included in the project and can be found in the `/jasmine/spec` folder.


## Instructions

1. Download the files or press the clone button and copy the link to the clipboard
2. Open the terminal and write command cd `/usr/name-of-folder` to select the directory
3. Write `git clone` and paste the link by pressing ctrl+shift+v or cmd+shift+v (on Mac) and press enter
4. open index.html

- Jasmine test suite results can be seen below the blog.
- If they all are green, then our test cases are satisfied.
- Below are the tests in `feedreader.js` file:


### Test Suits

###### Rss Feeds
* Must be defined
* Each contain an url and is not empty
* Each contain a name and is not empty

###### The Menu
* The side menu is hidden by default
* Menu is visible when the menu icon is clicked
* Visibility toggles when the icon is clicked again

###### Initial Entries
* Atleast 1 feed entry is displayed after the API call

###### New Feed Selection
* The feed content changes if a new feed is selected from the menu


## Libraries used

- JavaScript Testing Framework [Jasmine](http://jasmine.github.io/)
- jQuery


## License

Change whatever and do whatever you want with it. Make it your own. :)

Licensed under MIT License details [here](https://github.com/gautamgahlawat/feedreader-test/blob/master/LICENSE)