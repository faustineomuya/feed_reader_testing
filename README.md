# Feed Reader Testing 

This project is part of Udacity FrontEnd nanodegree program.

## Description

The project uses jasmine to test the functionality of a feed reader website.


For more information, see [spec.md](spec.md).

## Project Instruction:

- You can read the project requirements at the following url:
https://review.udacity.com/#!/rubrics/18/view

- To get started please download the original code from the following repository:
https://github.com/udacity/frontend-nanodegree-feedreader

## Steps taken to Complete the project:

1- I edited the allFeeds variable in ./js/app.js to make the provided test fail and to see how Jasmine visualizes this failure in my application. then i return the allFeeds variable to a passing state.

2- I wrote the following tests to meet the project requirements:
* Tests for allfeeds has been defined and that it is not empty
* Tests for allFeeds have a url and that the url is not empty
* Tests for allFeeds have a name and that the name is not empty
* Searches for the class of 'menu-hidden' in the body tag and checks that the menu is hidden
* Toggles on click event if the menu appears or disappears
* Tests if the loadFeed function has at least a single '.entry' within the '.feed' container
* Tests to see if two entries are not equaln.

### How to run this Project

1. Download the zip file or clone/fork the repository into your machine.
2. Extract the files to a local folder
3. Run index.html from your computer
