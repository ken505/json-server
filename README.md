## In this project, you can use json-server to create a mockAPI.

### Getting started

#### Github

https://github.com/typicode/json-server

#### Install JSON Server

`npm i json-server`

#### Create a db.json file with some data

- /db.json

```diff
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

#### Register with script

- /package.json

```diff
"scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint",
+    "json-server": "json-server --watch db.json --port 3001"
  },
```

`npm run json-server`

### Create Repositori

- 6th/August/2021

##### [Reference](https://www.youtube.com/watch?v=y0kPrFjfggk&t=16s)
