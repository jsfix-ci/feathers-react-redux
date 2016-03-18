Feathers React Redux
=========================

[![npm version](https://img.shields.io/npm/v/feathers-react-redux.svg?style=flat-square)](https://www.npmjs.com/package/feathers-react-redux)

Unofficial [Feathers](http://feathersjs.com/) bindings for React-Redux.

# Overview

[React-Redux](https://github.com/rackt/react-redux) is great. [Feathers](http://feathersjs.com/) is fantastic. feathers-react-redux aims to tie these two together.

# Features

* Redux stores mirror feathers services through reducers.
* Dispatched actions are consistently named and follow proper [Flux Standard Action conventions](https://github.com/acdlite/flux-standard-action).
* React Components define what they need, whether it be an initial client side load, initial server side load, or keeping up to date with feathers events.

# Installation

```
npm install --save feathers-react-redux
```

This assumes that you’re using [npm](http://npmjs.com/) package manager with a module bundler like [Webpack](http://webpack.github.io) or [Browserify](http://browserify.org/) to consume [CommonJS modules](http://webpack.github.io/docs/commonjs.html).

# Usage

## API

### `<ServiceComponent>` TODO

* `serviceName` TODO
* `sliceName` TODO

### `collectionReducer(resource)`

Returns a reducer that reduces to an object that is keyed by the objects' ```id```'s. Uses each object's ```__v``` to know if actions should replace the current object's values.

### `actions(app, serviceName)` TODO

### `serverActionsReducer(state, action)` TODO

### `serverRender(element, store, actions, callback)` TODO
