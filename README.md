# simple-auth-client

[![Build Status](https://travis-ci.org/akifo/simple-auth-client.svg?branch=master)](https://travis-ci.org/akifo/simple-auth-client)
[![npm](https://img.shields.io/npm/v/simple-auth-client.svg)](https://www.npmjs.com/package/simple-auth-client)
[![npm](https://img.shields.io/npm/l/simple-auth-client.svg)](https://github.com/akifo/simple-auth-client/blob/master/LICENSE.md)

**Don't use!! It's still dev**

## Features

- Server unnecessary
- Simple authentication system that operates only on the browser side
- Not secure

## Installation

### Donwload Manually

[Github](https://github.com/akifo/simple-auth-client/archive/master.zip)

### Bower

```bash
$ bower install simple-auth-client --save
```

### NPM

```bash
$ npm install simple-auth-client --save
```

## Usage

### Load from HTML

```javascript
<script src='/lib/simple-auth-client.min.js'></script>

<script>
  SimpleAuthClient.start({
    password: 'foo'
  });
</script>
```

### With a module system

```javascript
import SimpleAuthClient from 'simple-auth-client'

SimpleAuthClient.start({
  password: 'foo'
});
```

## Options

now writing...

## Development

```bash
# install
$ npm install

# flow-typed CLI installed
$ npm install -g flow-typed
# flow-typed install
$ flow-typed install

# serve livereload and watch at http://localhost:8080/
$ npm run watch 

# build for production
$ npm run build
```

## For only Japanese 
[How to build a module with using **rollup**(Japanses/日本語)](rollup.md)