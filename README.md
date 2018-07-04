# service-unavailable
A static page to display when everything goes wrong

## Prerequisites

You need [NodeJS with NPM](https://nodejs.org/) to build this project.

## Deploying

Clone the repo and run

    $ npm i && npm run build

This will build the static page into the ``build`` folder.

## Development

Start watch task to build whenever the files in ``src`` are changed.

    $ npm run watch

### Project structure

| What        | Source           |
| ------------- |-------------|
| HTML      | ``./src/index.html`` |
| CSS      | [kungbib-styles package](https://www.npmjs.com/package/kungbib-styles) and ``./src/style.css``      |
| Assets      | [kungbib-styles package](https://www.npmjs.com/package/kungbib-styles) |
| JavaScript      | There is none      |