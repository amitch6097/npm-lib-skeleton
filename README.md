# NPM Lib Skeleton

### This repo is designed to help get you started with pubishing an npm typscript library

## Setup

You should first replace all of the variables within the package.json. 
### [LIB_NAME] _the name of your library_
### [YOUR_NAME] _your name_
### [DESCRIPTION] _the description of your library_
### [REPO_URL] _the link to your github repo if you have one_
  Example: [https://github.com/amitch6097/npm-lib-skeleton.git](https://github.com/amitch6097/npm-lib-skeleton.git)
### [ISSUES_URL] _the link to your issues_ 
  Example: [https://github.com/amitch6097/npm-lib-skeleton/issues](https://github.com/amitch6097/npm-lib-skeleton/issues)
### [READ_ME_URL] _the link to your repos readme.md or docs_
  Example: [https://github.com/amitch6097/npm-lib-skeleton#readme](https://github.com/amitch6097/npm-lib-skeleton#readme)
  
  ## Adding Code
  
  You will want to add files to the ./src folder.  Export all of the functions and Classes you want avalible to your library users from the ./src/index.ts file.
  ### To build your package run
  ```
  npm run build
  ````
  This will build a common js version of your library and a UMD version
  
  ## Testing 
  
  Add tests to ./__tests folder.  The testing platform is Jest.  You can find out more about Jest [here](https://jestjs.io/)
  ### To build your package run
  ```
  npm run test
  ````
  
  ## Publishing to NPM
  
  Before publishing you should update the version in the package.json.  Following that you can run 
  ```
  npm run publish
  ```
  to publish your package to npm.
  

  
