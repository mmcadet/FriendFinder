#Friend Finder - Node and Express Servers

Overview
This app is a compatibility-based FriendFinder off the video game Mario Kart to help users find their best gaming partner friends. This will take in results of users' surveys, then compare their answers with those from other users. The app will then display the name of the user with the best overall match.

Instructions
Survey should have 10 questions of our choosing. Each answer should be on a scale of 1 to 5 based on how much the user agrees or disagrees with a question.

server.js file has the basic npm packages: express, body-parser, path

html-routes.js file has include two routes:

A GET Route to /survey which should display the survey page. A default USE route that leads to home.html which displays the home page.

api-routes.js file contains two routes:

A GET route with the url /api/friends. This will be used to display a JSON of all possible friends. A POST routes /api/friends. This will be used to handle incoming survey results. This route will also be used to handle the compatibility logic.

Technologies used:
html, css, bootstrap, express, body-parser, path, node, jQuery.

Challenges Faced: logic behind matching the answers difference to get best match for a MK friend. Will work on matches for the next version. 

https://mmcadet.github.io/FriendFinder/
https://git.heroku.com/stormy-meadow-31498.git

- Misha Cadet