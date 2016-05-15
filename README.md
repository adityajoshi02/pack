# Polymer Boilerplate

## Installation

`npm i -g gulp bower`

`npm i`

`bower i`

## Tasks

### Serve project from /src

`gulp`

### Run production build

`gulp build` 

### Serve project from /dist

`gulp serve:dist`

## Linting

### Run all lint tasks in parallel

`npm run lint -s`

### Run JavaScript lint

`npm run lint:js -s`

### Run HTML hint

`npm run lint:html -s`

## Testing

### Run tests in Chrome, open coverage report

`npm test`

### Run tests in Chrome and Firefox, open coverage report

`npm run test:all`

## Scaffolding

### Create new page in `src/components/pages` (you should then add it to router manually):

`gulp add:page`

### Create new element in `src/components/core`:

`gulp add:core`
