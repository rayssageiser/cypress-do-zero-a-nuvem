# Cypress, from Zero to the Cloud

Sample projeto for the "cypress, from Zero to the Cloud" course of the Talking About Testing online School.

## Pre-Requirements

It is required to have git, Node.js and npm installed to clone and run this project

> I've used versions `2.56.0`, `24.21.0` and `11.19.0` of git, Noje.js and npm, respectively. I suggest you use the same or later LTS versions.

## Installation

Run `npm install` (or `npm i` for the shot version) to install the dev dependencies.

## Tests

In this project, you can run the tests on a desktop or mobile viewport.

### Desktop

Run `npm test`(or `npm t` for the short version) to run the test in headless mode on a desktop viewport.

Or, run `npm run cy:open` to open the Cypress App on a desktop viewport.

### Mobile

Run `npm run test:mobile` to run the test in headless mode on a mobile viewport.

Or, run `npm run cy:open:mobile` to open the Cypress App on a mobile viewport.