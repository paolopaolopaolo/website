---
# Don't edit this file directly, it was copied using scripts/download-readmes.js: 
id: version-6.x-babel-plugin-transform-es2015-block-scoped-functions
title: babel-plugin-transform-es2015-block-scoped-functions
sidebar_label: transform-es2015-block-scoped-functions
original_id: babel-plugin-transform-es2015-block-scoped-functions
---

## Installation

```sh
npm install --save-dev babel-plugin-transform-es2015-block-scoped-functions
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["transform-es2015-block-scoped-functions"]
}
```

### Via CLI

```sh
babel --plugins transform-es2015-block-scoped-functions script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["transform-es2015-block-scoped-functions"]
});
```

