# House Party

This is a project following a tutorial by Tech With Tim on YouTube.

https://www.youtube.com/playlist?list=PLzMcBGfZo4-kCLWnGmK0jUBmGLaJxvi4j

## Setup

in music_controller
- python manage.py runserver

in music_controller/frontend
- npm run dev

## Video #1

The first video went over how to setup a django backend.

- pip install django djangorestframework
- django-admin startproject music_controller
- cd music_controller
- django-admin startapp api
- add apps to settings.py
- python manage.py makemigrations
- python manage.py migrate

## Video #2

The second video went over how to setup the models, serializers, and views.

- python manage.py makemigrations
- python manage.py migrate

## Video #3

The third video went over how to setup the frontend.

- django-admin startapp frontend
- cd frontend
- npm init -y
- npm i webpack webpack-cli --save-dev
- npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
- npm i react react-dom --save-dev
- npm install @material-ui/core
- npm install @babel/plugin-proposal-class-properties
- npm install react-router-dom
- npm install @material-ui/icons
- setup babel.config.json
- setup webpack.config.js
- npm run build
- npm run dev

## Video #4 

The fourth video went over styling, component creation, and react router.

## Video #5

The fifth video went over how to handle a POST request.

## Video #6

The sixth video went over how to create the Create Room ui in React and implement it into the backend.

## Video #7

The seventh video went over how to call API endpoints from react. 

## Video #8 

The eighth video went over how to create the room join page and set it up in the backend.

## Video #9

The ninth video went over how to handle a previous session when getting to the home page. 

## Video #10

The tenth video went over how to leave/delete rooms.

## Video #11

The eleventh video went over how to update a room's settings.

## Video #12

- npm install @material-ui/lab

The twelth video went over how to create default props and setup callbacks for data refresh.

## Video #13

- python manage.py startapp spotify

The thirteenth video went over how to connect the app to the Spotify API and authorize users.

## Video #14

The fourteenth video goes over how to use the Spotify API. (Display the currently playing song)

## Video #15

The fifteenth video goes over how to play/pause a song on Spotify API.

## Video #16

The sixteenth video went over how to skip a song via the Spotify API with votes.

## Video #17

In the last video, Tim went over the basics of a functional component.