This project was bootstrapped with Create React App for Chrome Extension.

## Screenshot, when you click on the extension in Chrome
![Screenshot](https://s20.postimg.cc/na5j4c80t/react.png)


## Folder Structure

After creation, your project should look like this:

```
my-app/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
    logo.svg
    manifest.json
  src/
    App.css
    App.js
    App.test.js
    index.css
    index.js
    logo.svg
```

For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](#running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!



### Chrome Manifest v2

```json
{
  "manifest_version": 2,

  "name": "My Extension",
  "description": "This extension is a starting point to create a real Chrome extension",
  "version": "0.0.1",

  "browser_action": {
    "default_popup": "index.html",
    "default_title": "Open the popup"
  },
  "icons": {
    "16": "logo.svg",
    "48": "logo.svg",
    "128": "logo.svg"
  },
  "permissions": [
  ]
}
```
