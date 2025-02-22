# Permaweb Writer [![Homepage](https://img.shields.io/badge/homepage-www-brightgreen.svg?style=flat)](http://www.permaweb.io)
## Contribute [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/Permaweb/Permaweb-js/issues) [![feature requests](https://img.shields.io/badge/feature-requests-blue.svg?style=flat)](https://github.com/Permaweb/Permaweb-js/issues)
## Community [![Discord](https://img.shields.io/badge/Chat-Discord-purple.svg?style=flat)](https://discord.gg/DrPFqa2) [![Matrix](https://img.shields.io/badge/Chat-Matrix%20&%20Riot-blue.svg?style=flat)](https://riot.im/app/#/room/#epona:getepona.com) [![IRC](https://img.shields.io/badge/IRC-freenode%20%23epona-brightgreen.svg?style=flat)](http://webchat.freenode.net/?channels=%23epona)

## Description
Epona is a super productive, privacy focused writing app.
* Tons of shortcuts. Mouse-free navigation.
* Super resilient. Everything you write is encrypted and decentralized.

We are building the best self-hosted tool to write and publish text.

Use cases:
* Draft notes
* Create markdown documents
* Share a pastebin
* A simple public blog

![Epona](https://getepona.com/static/screenshot-d39a4278e6019e385e47c37f632a8677.png)

## Technology
Epona runs on a series of self-hosted nodes. These are powered by [Textile.io](https://textile.io), which is acts as a digital wallet for fully encrypted, decentralized content. Content is stored using the [IPFS](https://ipfs.io) protocol, which makes Epona links unique and permanent.  This makes Epona extremely resilient: we do not have your keys, and there is no single point of failure. *You are the platform*.

* Epona uses [IPFS](https://ipfs.io) for content addressable hashing to make mirroring and mesh networking easy.
* We use [Textile](https://textile.io), the best library for distributed web applications.


## Project
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), and then the build/run configuration was customized with a `craco.config.js` file.

## Available Scripts
In the project directory, you can run:

### `yarn start`
Runs the app in the development mode.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.

You will also see any lint errors in the console.

### `yarn test`
Launches the test runner in the interactive watch mode.

See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`
Builds the app for production to the `build` folder.

It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.

Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More
You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started), and the [Craco project repo](https://github.com/sharegate/craco).

## Textile
[Textile](https://www.textile.io) provides encrypted, recoverable, schema-based, and cross-application data storage built on [IPFS](https://github.com/ipfs) and [libp2p](https://github.com/libp2p). We like to think of it as a decentralized data wallet with built-in protocols for sharing and recovery, or more simply, **an open and programmable iCloud**.

This demo is designed to showcase the features of `js-http-client`, which is available on [`npmjs.com`](https://www.npmjs.com/package/@textileio/js-http-client) under the `@textile` scope. `js-http-client` provides access to an underlying `textile-go` node's REST API, adding various simplified APIs to support in-browser and programmatic desktop access. For the most part, the API would mimic the command-line and/or mobile APIs of `textile-go`, with some browser-specific enhancements. It works well in conjunction with the Textile [desktop Tray app](https://github.com/textileio/go-textile#tray-app).
