Fitbit Developer Bridge
=======================

[![Greenkeeper badge](https://badges.greenkeeper.io/Fitbit/developer-bridge.svg)](https://greenkeeper.io/)

[![Coverage Status](https://coveralls.io/repos/github/Fitbit/developer-bridge/badge.svg?branch=master)](https://coveralls.io/github/Fitbit/developer-bridge?branch=master)

This repo contains JavaScript implementations of the Fitbit Developer
Bridge.

Usage instructions
------------------

First-time set up:

  1. Install node and yarn (npm won't work)

  2. Clone this repository

  3. Run `yarn install && yarn build` from the root of the repo

Development
-----------

To run scripts found in the `./packages` directory, first you need to:
* run `yarn build` in the root directory to build the project
* run your script with `node ./packages/package-name/lib/path/to/script.js`

(to run the cli, you would run `yarn build; node ./packages/sdk-cli/lib/cli.js`)

Help
===================
For help regarding the tools please consult the [Fitbit Developer Portal](https://dev.fitbit.com) or
[Fitbit SDK Forums](https://community.fitbit.com/t5/SDK-Development/bd-p/sdk)
