# Testing A React App (Reactjs, Jest) 
## Description
This a repository of create-react-app upon which testing has been conducted using Jest. The following resources were used to learn how to make the Jest tests:
* jestjs.io/docs/getting-started 
* jestjs.io/docs/snapshot-testing
* github.com/facebook/jest/tree/main/examples/snapshot
* [HyperionDev task 15](https://github.com/kimanicharles911/testing-a-react-app/blob/master/WD_L2T15_React_VI_Testing_a_React_App.pdf)


It contains 3 Jest test:
* Link Test
* Clock Test
* Sum Test

## Deployed at
* This is for development testing purposes only hence doesn't require deployment.

## Setup/Installation Requirements
##### Install Dependencies

```
npm install
```

##### Run React Development Server

```
npm run start
```

##### Test React Application

```
npm run test
```

##### To Build for Production

```
npm run build
Know how to host at heroku.com - https://dev.to/destrodevshow/how-to-deploy-react-app-to-heroku-in-5-minutes-3dni

heroku login
git add . && git commit -m"your commit message" && git push heroku master
```

## How It Was Built
##### Create React App
```
npx create-react-app 
npm i react-test-renderer
```
##### Dependencies
* React Test Renderer

### src folder structure
```
src/
  snapshot/
    Clock.react.js
    Link.react.js
    package.json
    sum.js
  __tests__/
    __snapshots__
      clock.react.test.js.snap
      link.react.test.js.snap
    clock.react.test.js
    link.react.test.js
    sum.test.js
  App.css
  App.test.js
  index.js
  reportWebVitals.js
  App.js 
  index.css
  logo.svg
  setupTests.js
```

## License and Copyright Information.
See [my MIT LICENSE](https://github.com/kimanicharles911/testing-a-react-app/blob/master/LICENSE.txt) for details.