# RMDB
## Table of Contents

- [Introduction](#introduction)
- [For the developers](#notes)
- [Features](#features)
- [Built With](#built-with)
- [Install](#install)

## Introduction

A ReactJS TMDB movie listing application. Data sourced from [TMDB](https://www.themoviedb.org). This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app) which has been built by the ReactJS devs.

## For the developers
* Filtering of popularity
Solution: Create an array of popularity's and the highest number would become the slider component MAX value. When the user clicks the slider it would call a method which gets the popularity number selected from the slider and stores it in a state. Looping through the existing movie data set any movies with popularity higher than the popularity number selected would be removed from the movie set. The slider could also do with a scale at the bottom in numbers but thats personal preference.

* Hiding the Filters on the movie page.
Solution: In the NavBar I would use this.props.location to detect if the user on a detail page and if so hide the components and not render any logic associated with them.


* Loading Screens
Notes: This is in place however could be more intuitive. We should have loading and error screens separate not one for all.
.

## Features

* Displays a list of movies, each showing their title & poster image. 
* Movies are ordered by popularity (most popular first).
* Movies are filterable by multiple genres. (Not complete)
* search function.
* View detail movie info including poster, trailers

## Technical Notes

* Responsive design using [React-Bootstrap](https://react-bootstrap.github.io/)
* Environment set-up using [Create-React-App](https://github.com/facebookincubator/create-react-app)

## Built-With

- Node v9.8.0
- NPM v5.6.0
- ReactJS

## Install

* Clone my Git "https://github.com/ArchnaJha93/RMDB.git" repository using GitBash or download the zip folder in local.
```
git clone https://github.com/ArchnaJha93/RMDB.git
```
* Move to that local folder.
* Install node dependancies by using node.js command prompt and below command.
```
npm install
```
* Start application
```
npm start
```
* You will be taken to the application
```
http://localhost:30000
```
