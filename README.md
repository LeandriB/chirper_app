# Chirper App

The goal for this project was to create a "Twitter" applicaton that allows users to view their feed, add new posts and comment on as well as like other user's posts. This application covers the fundamentals of a React-Redux application.

This application has been split up into 6 components:

* ```App``` - Holds **Nav** component and current view
* ```Nav``` - Allows user to move between **Dashboard** and **NewTweet** view
* ```Tweet``` - Displays tweet content
* ```Dashboard``` - Displays the users feed
* ```TweetPage``` - Displays a specific tweet and that tweets attributes(likes, replies ect.)
* ```NewTweet``` - Displays a tweet form for the user to add new tweets to the feed or comment on another users tweets

## Installation

1. Clone the directory
2. In the terminal, navigate to the root directory for this project
3. Run ```npm install``` to install all dependencies
4. Now that everything is set up, continue onto the section *How to run this program*

## How to run this program

Make sure all your dependencies are installed in your terminal or updated to the lasest version and run ```npm start``` to start the server.

## Project Preview

Dashboard showing tweets on feed:

![Dashboard Component](/img/Dashboard.png)

Composing a new tweet:

![NewTweet Component](/img/NewTweet.png)

Commenting on a users tweet:

![TweetPage Component](/img/TweetPage.png)

## Create React App

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). You can find more information on how to perform common tasks [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Attributions

This is a code along project [React Nanodegree program](https://www.udacity.com/course/react-nanodegree--nd019).

## License

MIT
