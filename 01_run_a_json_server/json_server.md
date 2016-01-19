#Server Side

#Objective
  Run a Json server  

#Requirement
1. Mac or Linux;
2. Javascrit/nodejs;

#Install and config
1. install, in console,
  ```
  $ npm install -g json-server
  ```
2. create db.json;
3. ```
  json-server db.json;
  ```
4. reference source, [link](https://github.com/typicode/json-server/blob/master/README.md)

#Content
  None

#Issue


#Notes
db.json sample
  ```
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
