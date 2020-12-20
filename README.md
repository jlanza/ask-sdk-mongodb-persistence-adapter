[![codecov](https://codecov.io/gh/xavidop/ask-sdk-mongodb-persistence-adapter/branch/main/graph/badge.svg?token=C8KSGME1OG)](https://codecov.io/gh/xavidop/ask-sdk-mongodb-persistence-adapter)
![.github/workflows/main.yml](https://github.com/xavidop/ask-sdk-mongodb-persistence-adapter/workflows/.github/workflows/main.yml/badge.svg?branch=main)
[![Maintainability](https://api.codeclimate.com/v1/badges/f8a3c3da83264e28c7cc/maintainability)](https://codeclimate.com/github/xavidop/ask-sdk-mongodb-persistence-adapter/maintainability)
![Technical debt](https://img.shields.io/codeclimate/tech-debt/xavidop/ask-sdk-mongodb-persistence-adapter)
[![npm version](https://img.shields.io/npm/v/ask-sdk-mongodb-persistence-adapter.svg)](https://npmjs.org/package/ask-sdk-mongodb-persistence-adapter)
[![npm license](https://img.shields.io/npm/l/ask-sdk-mongodb-persistence-adapter.svg)](https://npmjs.org/package/ask-sdk-mongodb-persistence-adapter)
[![npm type definitions](https://img.shields.io/npm/types/ask-sdk-mongodb-persistence-adapter)](https://npmjs.org/package/ask-sdk-mongodb-persistence-adapter)
![npm](https://img.shields.io/npm/dt/ask-sdk-mongodb-persistence-adapter)
![GitHub issues](https://img.shields.io/github/issues/xavidop/ask-sdk-mongodb-persistence-adapter)

ASK SDK MongoDB Persistence Adapter package contains implementation of persistence adapter in Core SDK ('ask-sdk-core') based on AWS SDK.

## What is ASK SDK MongoDB Persistence Adapter

The ASK SDK v2 for Node.js is an open-source Alexa CustomSkill Development Kit. ASK SDK v2 for Node.js makes it easier for you to build highly engaging skills, by allowing you to spend more time on implementing features and less on writing boiler-plate code.

## Installing
ASK SDK MongoDB Persistence Adapter package is an addon package for the core SDK ('ask-sdk-core') and thus has peer dependency of the core SDK package. From within your NPM project, run the following commands in the terminal to install them:

```
npm install --save ask-sdk-mongodb-persistence-adapter
```

## Usage and Getting Started

TODO

## Usage with TypeScript
The ASK SDK MongoDB Persistence Adapter package for Node.js bundles TypeScript definition files for use in TypeScript projects and to support tools that can read .d.ts files. Our goal is to keep these TypeScript definition files updated with each release for any public api.

### Pre-requisites
Before you can begin using these TypeScript definitions with your project, you need to make sure your project meets a few of these requirements:
- Use TypeScript v2.x
- Includes the TypeScript definitions for node. You can use npm to install this by typing the following into a terminal window:

```
npm install --save-dev @types/node
```

### In Node.js
To use the TypeScript definition files within a Node.js project, simply import ask-sdk-mongodb-persistence-adapter as below:

In a TypeScript file:

```typescript
import * as Adapter from 'ask-sdk-mongodb-persistence-adapter';
```

In a JavaScript file:

```javascript
const Adapter = require('ask-sdk-mongodb-persistence-adapter');
```

## Opening Issues
For bug reports, feature requests and questions, we would like to hear about it. Search the [existing issues](https://github.com/xavidop/ask-sdk-mongodb-persistence-adapter/issues) and try to make sure your problem doesn’t already exist before opening a new issue. It’s helpful if you include the version of the SDK, Node.js or browser environment and OS you’re using. Please include a stack trace and reduced repro case when appropriate, too. 

## License
This Adapter is distributed under the Apache License, Version 2.0, see LICENSE for more information.
