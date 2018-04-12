# Express Testing Lab

Today, you will be adding automated testing to the [Express API](https://git.generalassemb.ly/ga-wdi-exercises/express-api-lab) lab from last week. If your code was incomplete, please contact the instructors. You should have tests for each of the endpoints:

* GET `/gifs` which will list out all gifs
* POST `/gifs` which will add a new gif and return a list of all gifs
* PUT `gifs/:gifId` which will update a gif and return a list of all gifs
* DELETE `gifs/:gifId` which will delete a gif and return a list of all gifs

Your code should make sure that each endpoint returns what it is supposed to and accepts the correct content type. Directions for setting up testing and implementing tests can be found in the [Express Testing](https://git.generalassemb.ly/ga-wdi-lessons/express-tdd) lesson. **Please submit your final project as an issue to this repository.** If you use a separate branch for testing, please link to that branch in your issue so we know where to look to grade it.

## Bonus: Add Testing to your MEHN Lab

If you have time, look up how to test a non-JSON webpage endpoint. Add testing to your MEHN lab using your research! You could also convert your application to an API and add testing to it that way if you prefer.
