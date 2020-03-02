# Video gaming site

The site lists users and how many games they have played, new users can be added only with different usernames.

## TL;DR

To get started:

* clone project with `https://github.com/susumoa/video-gaming-site.git`
* install all project dependencies with `npm install`
* start the development server with `npm start`

## Usage

* Add new user:
Click Add New User button, 3 input fields appear (First name, Last name, Username). The Add button is inactive until any of the input fields is empty. Clicking the Add button hides the input fields and shows the username and how many games the user played in this format: #username played #numberOfGames games. If you try to add a user with an existing username the following warning appears: You cannot add a user that already exists.

* Hide / show the number of games played:
Clicking the toggle button (Hide the Number of Games Played / Show the Number of Games Played) hides or showes the number of the played games. When it's hidden, it shows #username played \* games.

## Create React App

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app). You can find more information on how to perform common tasks [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).
