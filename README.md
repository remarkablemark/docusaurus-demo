# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## Installation

```sh
npm install
```

## Local Development

```sh
npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```sh
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```sh
USE_SSH=true npm run deploy
```

Not using SSH:

```
GIT_USER=<Your GitHub username> npm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## Scripts

Inside the directory, you can run several commands:

```sh
npm start
```

Starts the development server.

```sh
npm run build
```

Bundles your website into static files for production.

```sh
npm run serve
```

Serves the built website locally.

```sh
npm deploy
```

Publishes the website to GitHub pages.
