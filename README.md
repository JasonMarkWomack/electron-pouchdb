# electron-pouchdb-demo
Demonstrating use of pouchdb wrapped in electron
Simple Electron App withh the DB connection.

To get the app running :

Clone this repo
Cd into the app directory
Run npm install && npm start 

PouchDB is an in-browser database that allows applications to save data locally, so that users can enjoy all the features of an app even when they're offline. Plus, the data is synchronized between clients, so users can stay up-to-date wherever they go. PouchDB also runs in Cordova/PhoneGap, NW.js, Electron, and Chrome apps. It is framework-agnostic, and you can use it with Angular, React, Ember, Backbone, or your framework of choice. There are many adapters, or you can just use PouchDB as-is.”  It is suited for our project.  However, if the group wants a relational db structure  there is an adapter for pouchdb called "sqllite3". That should not be to hard to fully fully implement.
If storage limits become an issue,  we can utilize an adapter (sqllite3, leveldb), which as far as I can tell , is only limited by the storage available on the hard drive containing the database(ie a users computer).
# electron-pouchdb
