# react-native-alt-demo

*Type in a location and see a stream of the most recent tweets for that location.*

This application demos [Alt/Flux](https://github.com/goatslacker/alt) and full ES6 integration with [React-Native](https://github.com/facebook/react-native). Develpment tools used include Webpack Dev Server to bundle and serve all files, Gulp-Eslint to keep the code syntactically awesome, and Jest to unit test.

You can quickly bootstrap your React-Native development by using the application as a boilerplate example. The application communicates with the Twitter and Google API via an [iojs server](https://github.com/mrblueblue/iojs-generators-example) I deployed to Heroku.

Build upon this as you wish!

The application demonstrates:
* The Flux pattern in React-Native
* Use of a [custom navigation bar](https://github.com/Kureev/react-native-navbar)
* Code base organization for React-Native development
* Modular UI components
* Unit testing with Jest
* Gulp integration
* Webpack Dev Server w/ React-Native

### Getting Started

To get started run `npm install` and then build the project in Xcode.

To start the webpack dev server, run `npm start`.

To test the application, run `npm test`.

To run the application on your iPhone, see instructions in `AppDelegate.m`

### Organization

The root file entry point is `src/index.js`. This points to `src/nav.js`, which renders `src/app.js`.

`src/nav.js` holds the all the logic related to app navigation. You can think of this a a 'router'.

`src/app.js` is the main application component that is hooked up to the Alt stores and actions.

### Contributing

All contributions are welcome!

<hr>
<div>
  <img src='https://github.com/mrblueblue/react-native-alt-demo/blob/master/screenshot-1.png' height=600 />
  <img src='https://github.com/mrblueblue/react-native-alt-demo/blob/master/screenshot-2.png'height=600 />
</div>
