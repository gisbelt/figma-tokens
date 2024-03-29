## :rocket: Getting Started

#### Figma design tokens example

**Figma file:** [https://www.figma.com/file/IGr2xoqcZX91CU7CDr4ZsI](https://www.figma.com/file/IGr2xoqcZX91CU7CDr4ZsI)

### Get your figma file id
![image](https://user-images.githubusercontent.com/1427623/92307876-c73e3900-ef99-11ea-8df4-c9d41eae0ac9.png)

### Get your figma API key
https://www.figma.com/developers/api

### Install dependencies:
`$ npm install --save-dev figma-tokens`

### Modify config with your figma API key and figma id 
![image](https://user-images.githubusercontent.com/1427623/92307902-f3f25080-ef99-11ea-94e4-69a06c0ad35a.png)
`$ figma.config.json`
```json
{
    "FIGMA_APIKEY": "384117-f83cea21-557b-4317-a799-40ff318a656c",
    "FIGMA_ID": "GWnnS47lU4AQIVj5j2yXhF"
}
```
#### Add scripts package.json
```json
"scripts": {
    "figma-tokens": "npm run figma-tokens:api && npm run figma-tokens:build",
    "figma-tokens:api": "node node_modules/figma-tokens/bin/figma-tokens-api",
    "figma-tokens:build": "node node_modules/figma-tokens/bin/figma-tokens-build"
  },
```
\$ npm run figma-tokens

\$ npm run figma-tokens:api Generate tokens data base (only figma)

\$ npm run figma-tokens:build Generate all plattforms tokens vars with a figma data base

Here, I'll give you a taco: 🌮


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
