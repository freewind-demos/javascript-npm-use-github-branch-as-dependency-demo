JavaScript Npm Use Github Branch as Dependency Demo
===================================================

This repo has two branches:

1. `util`: define a util function, has package name `my-util` and version `0.1.0`
2. `master`: use branch `util` as dependency from github branch

```
npm install
npm run demo
```

It will print:

```
Hello, Javascript
```

Note:

Package `my-util` is installed by:

```
npm i freewind-demos/javascript-npm-use-github-branch-as-dependency-demo#util
```
