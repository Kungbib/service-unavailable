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
| Layout      | ``./src/index.html`` |
| Styling      | [kungbib-styles package](https://www.npmjs.com/package/kungbib-styles) and ``./src/styles/style.scss``      |
| Assets      | [kungbib-styles package](https://www.npmjs.com/package/kungbib-styles) and [Font Awesome](https://fontawesome.com/) |
| JavaScript      | There is none      |