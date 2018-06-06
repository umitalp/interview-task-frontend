# Dice Game
Simplified version of the dice game [Yahtzee](https://en.wikipedia.org/wiki/Yahtzee).

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app) and [Bootstrap](https://getbootstrap.com/).

## Table of Contents
- [How To Start](#how-to-start)
- [Folder Structure](#folder-structure)
- [Available Scripts](#available-scripts)
  - [yarn start](#yarn-start)
  - [yarn test](#yarn-test)
  - [yarn run build](#yarn-build)
  - [yarn run eject](#yarn-eject)

## How To Start
Follow these commands

`cd /path-of-app-folder`</br>
`yarn`</br>
`yarn start`

## Folder Structure
```
my-app/
  node_modules/
  public/
    index.html
    favicon.ico
  src/
    app/
      components/
        dice.js
        diceRoller.js
        footer.js
        header.js
        resultsTable.js
      containers/
        home.js
      functions.js
      index.js
    assets/
    index.css
    index.js
  .eslint.json
  .gitignore
  package.json
  README.md
```

For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.

You can delete or rename the other files.

You may create subdirectories inside `src`. For faster rebuilds, only files inside `src` are processed by Webpack.<br>
You need to **put any JS and CSS files inside `src`**, otherwise Webpack won’t see them.

Only files inside `public` can be used from `public/index.html`.<br>

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.

### `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

