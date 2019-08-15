# Memoization

## In order to test the code, run:
npm run test

## The required dependencies are:
+ mocha
+ chai
+ lolex

to install those dependencies, if you have NODE.JS installed, open a console, navigate to your project root folder and run:
npm install mocha chai lolex

If you require a verbose option when running the code, you can set the variable debug = true 
Inside the memoize function within the memoizaton.js file.

## Testing Summary:

Data type testing summary:
+ undefined type does not work with memoized   ***
+ number type is memoized succesfully, see firt IT
+ boolean type is memoized succesfully
+ string type is memoized succesfully
+ symbol type does not work with memoized      ***
+ object type is memoized succesfully
+ object type null is memoized succesfully
+ object type function is memozed succesfully

Timeouts and the system clock were altered using lolex.
In order to verify cache age, without waiting.

The overall test of data types and cache age/timeouts was succesfull
