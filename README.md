# Autominuto Frontend - SPA 

### This is the v1 of the Frontend  of autominuto my own Startup in Nodejs, angularjs and mongodb.

#### This are the steps required to set up your environment

###### Every folder in the source is a screen, in its inside has the route file, css, controllers and views. 19 folder in total
###### In APP folder is webserver, routes has all the routes of the website, and service is to call external services like helpers and so, view has some static pug files to create PDF when you download cupons, or checkouts, or bills, etc. 

1. Install Node Package Manager 

   ```   
   sudo apt-get update
   sudo apt-get install npm
   ```
2. Install project dependencies

   ```
   sudo npm install (In the project root)
   sudo npm install gulp -g (Install gulp globally)
   ```
3. Run Gulp

   ```
   npm run postinstall
   ``` 
4. Browser

   ```
   Test in localhost: http://localhost:8080
   ``` 

5. Configure variables 
   ```
   Set up all the variables in angularEnv.json

   "API_END_POINT": "API_END_POINT",
   "SOCIAL_RECOMMENDATION_URL": "SOCIAL_RECOMMENDATION_URL",
   "S3_BUCKET": "S3_BUCKET",
   "PATH_IMAGES" : "PATH_IMAGES"
   ``` 

   

### Endpoint location

- The endpoint host are defined in constants.js file
- By default, endpoint host in development environment is [http://localhost:3000/trader/][localhost_environment]


[localhost_environment]: <http://localhost:3000/trader/>
