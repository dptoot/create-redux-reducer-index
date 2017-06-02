# redux-create-reducer-index
CLI utility to create an ./index.js file in supplied target directories.  The generated index file will import all sibling reducer files within the directory and export a single reducer using redux's combineReducer utility.

### Installation
```js
npm install --save-dev redux-create-reducer-index
```

### Usage
```js
redux-create-reducer-index ./src/reducers
```

