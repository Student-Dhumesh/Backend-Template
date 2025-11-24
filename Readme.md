```
$ mkdir backend
$ cd backend
$ npm init

```

```
package name: (backend)
version: (1.0.0)                            
description: basic app
entry point: (index.js)
test command: node src/index.js
git repository:
keywords:
author:
license: (ISC)

```

```
$ touch .gitignore
```

```
https://mrkandreev.name/snippets/gitignore-generator/#Node
```

```
$ npm install -D nodemon
```

```
"type": "module",
"scripts": {
    "test": "node src/index.js",
    "start": "node src/index.js",
    "dev": "nodemon src/index.js"
},
```

```
npm i mongoose express dotenv
```