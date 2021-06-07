# React and Snowpack template with gh pages deployments
__taken the TL;DR comment related to the [issue](https://github.com/snowpackjs/snowpack/discussions/2419)__

## Run `git init`
To initialize any necessary details in your `package.json`

## To run with gh pages
### npm i gh-pages
To install gh-pages

#### In your `package.json` file...
add under the `scripts` :
```
    "deploy": "gh-pages -d build"
```
And to deploy to gh pages
### npm run deploy

