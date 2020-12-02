# Accessible Cross-Browser Forms

This course uses the static site generator [Eleventy](https://11ty.dev) as the build processing tool, and Nunjucks templating to composite the form partials into screens. Knowledge of either is not required to complete the course or to extend the solutions to other platforms and contexts.

The `start` script includes Sass compilation complete with autoprefixing for accuracy of cross-browser testing.

Knowledge of Eleventy is not required, but if you'd like to learn more you can learn to create an Eleventy site from scratch by [completing my other egghead course](https://egghead.io/playlists/build-an-eleventy-11ty-site-from-scratch-bfd3?af=2s65ms).

## Project scripts

All of the following scripts are run in the root package.

1. `yarn` installs all dependencies.
1. `yarn start 01` (replace with lesson number or keyword) runs the project in the browser.
1. `yarn latest` updates all dependencies.
1. `yarn clean:node_modules` deletes `node_modules` recursively.

Individual lessons include their own `package.json` with `start` and `build` commands that can be run via node or yarn.
