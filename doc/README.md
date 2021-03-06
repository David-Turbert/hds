
# HDS

Hierarchical data store

## What is HDS ?

This library is designed to help create a database using Mongo DB and storing any kind of (possibly) hierarchical data,
along with attachments (files) and a powerful yet simple way to execute queries.
There is also a system to manage groups and roles for every piece of information.

## What technology is used ?

* [mongoose](http://mongoosejs.com/) - Main library used for most of the interactions with mongoDB
* [Mongo DB](https://github.com/mongodb/node-mongodb-native/) - The native Node JS driver is used to manage files in GridFS
* ES6 promises - Asynchronous code uses promises.

## How to use it ?

`$ npm install hds`

```js
var hds = require('hds');
```

## [Getting started](guide.md)

## Table of contents
...
