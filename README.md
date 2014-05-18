![image_squidhome@2x.png](http://i.imgur.com/RIvu9.png) 

# Sails-Neo4j 

A Sails/Waterline adapter for the Neo4j graph database. 
This is currently in development for sails v0.10.

## Getting started
This version is currently unstable/unusable, and under development. If you have ant experience with waterline and/or Neo4j please offer you assistace, so that we may git this fuctional.

## How to test your adapter
1. Run `npm link` in this adapter's directory
2. Clone the sails.js core and modify the tests to use your new adapter.
3. Run `npm link sails-boilerplate`
4. From the sails.js core directory, run `npm test`.

## Submitting your adapter
1. Do a pull request to this repository (make sure you attribute yourself as the author set the license in the package.json to "MIT")  Please let us know about any special instructions for usage/testing.
2. We'll run the tests one last time.  If there are any issues, we'll let you know.
3. When it's ready, we'll update the documentation with information about your new adapter
4. Then we'll tweet and post about it on our blog, adoring you with lavish praises.
5. Mike will send you jelly beans.


## About Sails.js and Waterline
http://SailsJs.com

Waterline is a new kind of storage and retrieval engine for Sails.js.  It provides a uniform API for accessing stuff from different kinds of databases, protocols, and 3rd party APIs.  That means you write the same code to get users, whether they live in mySQL, LDAP, MongoDB, or Facebook.
