# Super Simple Static Site
> A template for the structure of a web site, including an easily
 customisable gulp setup, which by default processes CoffeeScript, SASS and Jade.
 
## File Structure
````
/site
--/src/
----/resources/
----/scripts/
----/styles/
----/views/
----/locals.json
````
 
## Setup

1. Clone the repo: `git clone https://github.com/Lissy93/super-simple-static-site.git`
and navigate into the directory `cd super-simple-static-site`

2. Install Dependencies `npm install` 

3. Install gulp global (if not already done) `npm install gulp -g`

4. Build the app `npm run build`

5.a. Run the app on an node server, run `npm start` and visit http://localhost:8080 

5.b. OR to just run the app locally open production/index.html in your web browser


## Modifying

Run `npm run watch` to watch for changes in the working directory and recompile necessary files

If you are using the node server, to save having to restart it on every file change, use nodemon (`npm install nodemon -g`). 
Run `nodemon server` from the root directory. It will restart automatically on file change


