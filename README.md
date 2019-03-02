# ShouNs-portfolio

> A Vue.js project on docker

## Start Develop

``` bash
# start docker
docker-compose up -d --build

# install firebase tools
doker-compose exec vue_app npm install -g firebase-tools

# serve with hot reload at localhost:8080
docker-compose exec vue_app npn run dev
```

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
