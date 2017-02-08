# Feed Reader Test
This project is designed to test working with test-driven development using the Jasmine JavaScript testing framework.

## Getting started
### View Offline
* First clone the project directory in the root of a webserver like Apache using this command
`git clone https://github.com/TySabs/feedreader-tdd.git `
* Then navigate from the root of ```localhost``` to ```index.html``` in your web browser.

### View Online
View the project online here: [Feed Reader TDD](https://tysabs.github.io/feedreader-tdd/)

## Tests Written for this project
1. The first test for the RSS array was already provided.
2. Loop through allFeeds and ensure that every feed has a url and that url is not set to a blank string.
3. Loop through allFeeds and ensure that every feed has a name and that name is not set to a blank string.
4. Make sure the menu item is hidden by default.
5. Ensure there is at least one .entry element within the .feed container when loadFeed() is called
6. Ensure when a new feed is loaded by loadFeed(), the content changes from the old feed to the new feed
7. Expect two things from menu-icon-link toggle:

  1) That menu-icon-link hides menu when menu is visible

  2) That menu-icon-link shows menu when menu is hidden
