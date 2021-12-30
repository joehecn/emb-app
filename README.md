# emb-app

## Install
``` bash
npx create-electron-app@latest emb-app
cd emb-app
code .
sudo node ./node_modules/electron/install.js
npm start
```

## package
https://dev.to/erikhofer/build-and-publish-a-multi-platform-electron-app-on-github-3lnd
``` bash
git add .
git commit -m "xxx"
npm version minor
git push --follow-tags
```