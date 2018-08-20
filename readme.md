# digital-form-builder

DEFRA's digital form builder is a metadata-driven framework that builds on our robust, enterprise backend tech stack and the new gov.uk frontend Design System and allows form based gov.uk sites to be easily built using a graphical design tool.

The framework is flexible. It is capable of handling a number of different scenarios where form based page are required. E.g. Collecting data in a transactional service or checking if a service is suitable for an end user.

Using the graphical design tool, users can build sites from a toolkit of common GDS patterns that includes Pages, Sections and Navigation elements along with Components like Text Fields, Radios Buttons, Checkboxes and Date Fields.

## Getting started

### Prerequisites
Install Node.js v8.x.x

Install `npm i -g browser-refresh` (optional). 
This is like `nodemon` and restarts the server when files change.
Additionally it reloads the browser page is useful during development.

### Clone and build

Clone this repo

`$ git clone https://github.com/DEFRA/digital-form-builder`

`$ cd digital-form-builder/`


Install dependencies

`$ npm i`


Run the build to build govuk-frontend css

`$ npm run build`


Finally, config files [don't get stored](https://github.com/davidjamesstone/glupe/blob/master/docs/readme.md#config) in the repo so we need to create one.
A copy of the example config will do for now.

`$ cp config/server.example.json config/server.json`

You are now ready to start.

`$ browser-refresh`


Open your browser at

`http://localhost:3009/split`