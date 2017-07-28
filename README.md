# URLockBox


## This is an app that stores urls for you to read later
+ See it live [here](https://safe-beach-18611.herokuapp.com/)

## Setup

+ this app is configured to run on a Postgres DB. If you do not have a PG server running, you will need to set that up.
+ Clone down the repo
+ run `bundle`
+ run `rake db:create`

## Development

+ The App is setup around two models: User and Link.
+ The User model uses Bcrypt to store passwords securely.
+ Users have many Links.
+ Much of the view functionality is in the JavaScript. If there is a problem in a view, this is definitely where it is.

## Hot Link Service

+ In the JS files there are two AJAX calls made to an implementation of the [Hot Reads app.](https://mighty-ocean-52812.herokuapp.com/) The URL is hardcoded, and should be changed if you want to use your own service.
