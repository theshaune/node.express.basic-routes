# node.express.basic-routes

This is an example based upon [express](http://expressjs.com/en/starter/generator.html). It explores an alternatie modular method of routing.
The basic idea is to have the routes loaded through the centralized `/routes/index.js` file, as opposed to the default `app.js`.

This may help apps that move to a MVC structure avoid having a complex messy `app.js` file.

I have included 3 example routes; home, store and about.

## Installation
```
npm install
```
