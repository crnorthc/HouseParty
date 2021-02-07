# House Party

This is a project following a tutorial by Tech With Tim on YouTube.

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
