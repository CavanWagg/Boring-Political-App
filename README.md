# Boring Political Project!

**Access the app on Heroku [here](https://boringpoliticalapp.herokuapp.com/)**

*HomePage*

![Screenshot](https://cl.ly/5db314a49720/Image%2525202018-08-25%252520at%25252010.30.25%252520AM.png)



*List of Bills, dragging a bill over will display further information*



![Screenshot](https://cl.ly/7e178183289c/Image%2525202018-08-25%252520at%25252010.31.11%252520AM.png)



*Local Representative page, found using Geolocation API, or manual address entry*



![Screenshot](https://cl.ly/dd1911b8bb88/Image%2525202018-08-25%252520at%25252010.33.16%252520AM.png)


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Tech Used](#tech-used)
- [API Reference](#api-reference)
- [Installation](#installation)
- [Functionality](#functionality)
- [License](#license)
- [In Retrospect](#in-retrospect)
- [Next Steps](#next-steps)
- [Group Members Responsibilities](#Group-Members'-Responsibilities)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Tech Used

- less.js
- Bootstrap
- Firebase
- interact.js
- jQuery

### API

- ProPublica Congress
- Google Civic Information
- Geolocation
- Mapquest Reverse Geocode

## Installation

To run the application locally, first clone this repository 
```javascript
git clone https://github.com/CavanWagg/Boring-Political-App.git
```
Next, move into the project folder and install the dependencies
```javascript
cd Boring-Political-App
npm install
```
Finally, run the server locally
```javascript
node server
```
## Functionality
* User searches for topic
* User can drag and drop bills to learn more about them
* If they choose, user can click get involved button
* 'Get Involved' button asks for user's location
* Based on user's location, representatives will be shown

## License

[MIT License](https://github.com/scoslo5512/Project1/blob/geolocation-work/LICENSE)

## In Retrospect
* Start think about accessibility early on!!
* Use ESLint, Gulp - other task runners

## Next Steps

* When congressional people are shown - we would like to show how these people have previously voted on issues
* Breaking data down to show more local representatives
* Incorporate Tweets from politicians (able to obtain twitter handles from Google Civic API)


### Group Members' Responsibilities

* Project Management & Information Architecture: Maddy
* Interface/Experience Design: Majid
* Web Content and Technology: Cavan
* Web Development and Production: Robert and Dan
* Quality Assurance and Editing: Group
