# create-react-app Demo

[![TravisCI](https://img.shields.io/travis/patsissons/cra-demo/master.svg?label=TravisCI)](https://travis-ci.org/patsissons/cra-demo) [![CircleCI](https://img.shields.io/circleci/project/github/patsissons/cra-demo/master.svg?label=CircleCI)](https://circleci.com/gh/patsissons/cra-demo) [![Coverage Status](https://img.shields.io/coveralls/github/patsissons/cra-demo/master.svg)](https://coveralls.io/github/patsissons/cra-demo) [![Github License](https://img.shields.io/github/license/patsissons/cra-demo.svg)](https://github.com/patsissons/cra-demo/blob/master/LICENSE.md) [![eslint](https://img.shields.io/badge/eslint-Shopify-117D6B.svg)](https://github.com/Shopify/eslint-plugin-shopify) [![jest](https://jestjs.io/img/jest-badge.svg)](https://github.com/facebook/jest)

Demo deployed to [Github Pages](https://patsissons.github.io/cra-demo/)

## Demo scripts

### `yarn server`

Run this after `yarn build` to test a production build before deploy

### `yarn docs`

build and deploy to `docs`

### `yarn lint`

Run the linter (also `yarn lint:stats` to narrow down rule violations)

### `yarn pretty`

Run the formatter

### `yarn build:stats`

Webpack bundles can be profiled to validate optimized bundling, minimizing size, and deduplication of modules. Profiled bundles produce a `build/bundle-stats.json` file that the following tools can be used for visualizing the bundler stats:

- https://webpack.github.io/analyse/
- https://chrisbateman.github.io/webpack-visualizer/
- https://alexkuz.github.io/webpack-chart/
- https://alexkuz.github.io/stellar-webpack/

## create-react-app Scripts

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
