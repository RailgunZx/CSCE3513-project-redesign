In the spring semester of 2022 my team and I created a laser tag game management application in Java for my software engineering class. The app we made allows users to enter player IDs into an input field which will cause the software to check with a Heroku server we set up to see if there are any usernames with that ID. If one is found, the software will fetch the username and populate another input field with the name. Otherwise, a username can be created for the given ID. The game can then be started and the software will listen for UDP traffic communicating players "tagging" each other in a game of laser tag. The software will update player and team scores according to the data received.

The project in this repository is a work-in-progress recreation of that software redesigned as an Electron application for the sake of learning.

Link to the original project repository: https://github.com/saloper/CSCE3513-Project
