Simple Website Boilerplate
==========================

A simple website boilerplate with BrowserSync and Sass.

## Features

* Compile Sass with node-sass
* Live reload changes with BrowserSync
* Publish a gh-pages with a GitHub actions workflow or a single command

To setup automated publishing with GitHub actions, you'll need to setup the following secrets: `DEPLOY_GITHUB_TOKEN`, `DEPLOY_GITHUB_EMAIL`, `DEPLOY_GITHUB_USER`. A personal token is necessary for deploy because the token available by default in GitHub actions doesn't work for publishing to GitHub pages

## Usage

* `yarn start` - Start development server with BrowserSync and Sass
* `yarn serve` - Start the BrowserSync server
* `yarn build` - Build the CSS files
* `yarn watch` - Watch for changes in the Sass files
* `yarn gh-pages` - Publish the website to the `gh-pages` branch
