# BYOB Submission Form

[Project Spec](http://frontend.turing.io/projects/build-your-own-backend.html)

------

# Basics

#### Link to the GitHub Repository for the Project
[BYOB](https://github.com/davidjryan/BYOBlockchain)

#### Link to the Deployed Application
[Heroku](https://byoblockchain.herokuapp.com)


## Completion

#### Were you able to complete the base functionality?

* Documented all available endpoints and their usage in the README?
(Yes)

* Seeded a database with at least 2 tables and 1 relationship?
(Yes)

* Had at least 10 endpoints that returned responses with appropriate status codes?
(Yes)

* Secured at least 4 endpoints with JWTs?
(Yes)

* Enforced a linter and wrote code that conformed to it?
(Yes)

* Wrote tests for both happy and sad paths for each endpoint?
(Yes/No)

* Setup automatic deployments with CircleCI to a production app on Heroku?
(Yes)

# Code Quality

#### Link to a specific block of your code on GitHub that you are proud of
[happy code DJR](https://github.com/davidjryan/BYOBlockchain/blob/2a71d84928e01719dbe8f65850a4e11a8ca879dd/server.js#L210-L223)

[happy code Jesse](https://github.com/davidjryan/BYOBlockchain/blob/47e66a9c041e5609c8a072e97466c695a6354aff/server.js#L33-L59)

* Why were you proud of this piece of code?
- DJR - I was proud because this further solidified my understanding of sql logic and knex syntax.  Sort of proved to myself that I'm really grasping whats going on and my salesforce experience is helping me to grasp relational database design patterns.

- Jesse - I was proud of this code because he somewhat figured out what was going on after hours of breaking the project. I see the value in JWT's 

#### Link to a specific block of your code on GitHub that you feel not great about
[sad code Jesse](https://github.com/davidjryan/BYOBlockchain/blob/47e66a9c041e5609c8a072e97466c695a6354aff/server.js#L61-L73)

[sad code DJR](https://github.com/davidjryan/BYOBlockchain/blob/b041ec175101694f9a06138de489953457188b7b/server.js#L61-L73)

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
Jesse - This code was tough because it took forever to figure out. The time limit on the project caused me to rush writing middleware without really understanding how it works so although I got the code to work and have a decent understanding of it now, I'm still sad when I think about how much time I put into this.

DJR - JWT is still fuzzy for me.

#### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

BYOBlockchain is running on 3000. env: test
  Client Routes
    ✓ should return the homepage
    ✓ should return a 404 if the page is not found

  API Routes
    GET api/v1/wallets
Seeding complete!
      ✓ should return all the wallets
    GET api/v1/wallets
Seeding complete!
      ✓ should return a single wallet
    POST api/v1/wallets
Seeding complete!
      ✓ should post a wallet
Seeding complete!
      ✓ should return a 422 when a required param is missing
    DELETE api/v1/wallets
Seeding complete!
      ✓ should delete a wallet
    DELETE api/v1/transactions
Seeding complete!
      ✓ should delete a wallet
    GET api/v1/transactions
Seeding complete!
      ✓ should return all transactions
    GET api/v1/transactions/:id
Seeding complete!
      ✓ should return one transaction
    POST api/v1/transactions
Seeding complete!
      ✓ should post a transaction
    PATCH api/v1/transactions/:id
Seeding complete!
      ✓ should edit one transaction amount
    PATCH api/v1/wallets/:id
Seeding complete!
      ✓ should edit one wallet balance


  13 passing (325ms)

#### Attach a screenshot or paste the output from your terminal of the result of your linter running.

⚡ yarn run eslint
yarn run v1.3.2
$ ./node_modules/eslint/bin/eslint.js *.js
✨  Done in 1.04s.

#### Attach a screenshot of your CircleCI build passing

[circleCI build](https://github.com/davidjryan/BYOBlockchain/blob/master/Screen%20Shot%202018-02-09%20at%207.16.47%20PM.png)
- This is a screenshot of how CircleCI is acting. We don't understand why it works when I push a branch but not after the branch is merged into master.
-----

#### Please feel free to ask any other questions or make any other statements below!

Anything else you wanna say?

We need to write more tests for sad paths which will continue to work on. If we have more time than that we would explore the transaction functionality of knex.

-----


# Instructor Feedback (Instructor Name)

The following set of points are distributed at the discretion of the instructor.

### Documentation

**x points**:(10 possible points) Lorem ipsum dolor set amet

### Feature Completion

**x points**: (60 possible points) Lorem ipsum dolor set amet

### Testing & Linting & Error Handling

**x points**: (40 possible points) Lorem ipsum dolor set amet

### JavaScript Style

**x points**: (40 possible points) Lorem ipsum dolor set amet

### Workflow

**x points**: (20 possible points) Lorem ipsum dolor set amet

## Project is worth 170 points

## To get a 3 on this project, you need to score 125 points or higher
## To get a 4 on this project, you need to score 145 points or higher

# Final Score: x / 170
