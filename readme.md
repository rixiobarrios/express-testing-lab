# Express Testing Lab

Today, you will be adding automated testing to the [Express API](https://git.generalassemb.ly/seir-826/w06d01-seir826-express-api-lab) lab from last week. Please work off of the [`testing-starter` branch](https://git.generalassemb.ly/seir-826/w06d01-seir826-express-api-lab/tree/testing-starter). You should have tests for each of the endpoints:

* GET `/gifs` which will list out all gifs
* GET `/gifs/:id` which will get a gif with a specific ID
* POST `/gifs` which will add a new gif and return that new gif
* PUT `gifs/:id` which will update a gif and return that gif
* DELETE `gifs/:id` which will delete a gif

Your code should make sure that each endpoint returns what it is supposed to. Directions for setting up testing and implementing tests can be found in the [Express Testing](https://git.generalassemb.ly/seir-826/w06d02-seir826-express-tdd) lesson. 

### Set Up

Fork the `express-api-lab` repo. Then clone your fork. Afterwords, fetch the `testing-starter` code and checkout that branch. Also, seed the database.

```
$ git clone git@git.generalassemb.ly:your-fork/w06d01-seir826-express-api-lab.git
$ git fetch origin testing-starter
$ git checkout testing-starter
$ npm install
$ nodemon
$ node db/seed.js
```

If you don't have access to the original, do the following:
```
$ git remote add original https://git.generalassemb.ly/seir-826/w06d01-seir826-express-api-lab/
$ git fetch original testing-starter
$ git checkout testing-starter
```
Make sure you have `mongod` running as well!

## Bonus: Add Testing to your MEHN Lab

If you have time, look up how to test a non-JSON webpage endpoint. Add testing to your MEHN lab using your research! You could also convert your application to an API and add testing to it that way if you prefer.
