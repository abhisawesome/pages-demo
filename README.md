# Getting started

- npm init react-app my-app
- npm install gh-pages --save-dev
- Add below in package.json

```
{
    "homepage":"http://{username}.github.io/{repo-name}",
    ....
    "scripts": {
    ...
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
    }
}
```
 - npm run deploy
