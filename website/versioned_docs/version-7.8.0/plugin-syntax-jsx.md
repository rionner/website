---
id: version-7.8.0-babel-plugin-syntax-jsx
title: @babel/plugin-syntax-jsx
sidebar_label: syntax-jsx
original_id: babel-plugin-syntax-jsx
---

## Installation

```sh
npm install --save-dev @babel/plugin-syntax-jsx
```

## Usage

### With a configuration file (Recommended)

```json
{
  "plugins": ["@babel/plugin-syntax-jsx"]
}
```

### Via CLI

```sh
babel --plugins @babel/plugin-syntax-jsx script.js
```

### Via Node API

```javascript
require("@babel/core").transform("code", {
  plugins: ["@babel/plugin-syntax-jsx"]
});
```

