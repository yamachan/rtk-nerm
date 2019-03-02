# rtk-nerm

NERM stands for Node.js, Express, React and Material-UI. The repository is a simple sample of NERM application.

This repository was made as a sample package for the following (Japanese) tutorial page.

* [NERM (Node.js + Express + React + Material-UI) ベースなWebアプリ開発用のシンプルなビルド環境 2019年3月版](https://qiita.com/yamachan360/items/7892084573abda091dee)

# How to build

```
npm run build
```

# How to start the application

For the local environment, type the following command, then open http://localhost:3000/ by web browser.

```
npm start
```

If you have an IBM Cloud account, type the following command to start it on the cloud (Need to change the application name to unique one);

```
cf login
cf push -m 128M -c "node Server.js" rtk-nerm
```

# Setup packages

If you want to create a new repository from scratch, please type the following commands;

```
npm init -y
npm install --save express
npm install --save react react-dom @material-ui/core
npm install --save-dev browserify babelify
npm install --save-dev @babel/core @babel/preset-env @babel/preset-react
```
