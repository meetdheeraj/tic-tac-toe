# TicTacToe - A React App With Hooks

This was done with an aim to learn the react code setup from scratch (without using create-react-app) and to play with hooks (React's new feature).

The initial code for TicTacToe was copied from this [codepen](https://codepen.io/gaearon/pen/oWWQNa). It was then modified to make use of hooks.

## Minimalist React Setup

```bash
mkdir tictactoe
cd tictactoe
npm init --y
```
This will get us going with basic configuration and scaffolding for our Node project.

Next, we will install React, Webpack and Babel

```bash
npm install react react-dom
npm install --save-dev webpack webpack-dev-server html-webpack-plugin @babel/core babel-loader @babel/preset-env @babel/preset-react
```
What will each one of this do?

`react`: UI library for creating modular components\
`react-dom`: enables us to render the React within the browser DOM\
`webpack`: bundler that converts your source code into production-ready output\
`webpack-dev-server`: transforms our source code and serves it on a web server as we develop it continuously. This helps use see the output of your code in the browser.\
`html-webpack-plugin`: an extension to webpack that adds the basic index html file\
`@babel/core`: a JavaScript transpiler to converts modern JavaScript into a production-ready version that's compatible with all browsers.\
`babel-loader`: connects Babel to webpack's build process\
`@babel/preset-env`: group of commonly used Babel plugins bundled into a preset that converts modern JavaScript features into widely compatible syntax
`@babel/preset-react`: React-specific Babel plugins that convert JSX syntax into plain old JavaScript that browsers can understand


## License
[GPL](https://www.gnu.org/licenses/gpl-3.0.html)