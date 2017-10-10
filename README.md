```sh
yarn add react@^16.0.0 react-dom@^16.0.0 react-test-renderer@^16.0.0 enzyme@^3.0.0 enzyme-adapter-react-16@^1.0.1 react-faux-dom@4.0.3
```

```sh
cat node_modules/enzyme-adapter-utils/node_modules/react/package.json
{
  "name": "react",
  "description": "React is a JavaScript library for building user interfaces.",
  "version": "15.6.2",
  "keywords": [
    "react"
  ],
  "homepage": "https://facebook.github.io/react/",
  "bugs": "https://github.com/facebook/react/issues",
  "license": "MIT",
  "files": [
    "LICENSE",
    "addons.js",
    "react.js",
    "addons/",
    "dist/",
    "lib/"
  ],
  "main": "react.js",
  "repository": "facebook/react",
  "engines": {
    "node": ">=0.10.0"
  },
  "dependencies": {
    "create-react-class": "^15.6.0",
    "fbjs": "^0.8.9",
    "loose-envify": "^1.1.0",
    "object-assign": "^4.1.0",
    "prop-types": "^15.5.10"
  },
  "browserify": {
    "transform": [
      "loose-envify"
    ]
  }
}%    
```
