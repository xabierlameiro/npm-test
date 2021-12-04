
### `npx create-react-app npm-test`
### `cd npm-test`
### `yarn start`
### `Remove all files inside /src less App.js and index.js`
### `npm install --save-dev @babel/core @babel/cli @babel/preset-env`
### `npm install -save @babel/polyfill`
### `create babel.config.json`
### `replace build command un package.json for "build": "rm -rf dist && NODE_ENV=production babel src/lib --out-dir dist --copy-files"`
### `npm run build`