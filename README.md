# Todo-app-using-angularjs-and-loopback

Step 1:Install strongloop

    ## npm install -g strongloop

Step 2:create a folder structure

    ## slc loopback todo

step 3:create model

    ## slc loopback model

step 4: run the created model

   ## node .

step 5: create .bowerrc file to set the file location 

    {
    "directory": "client/lib"
    }
 
 step 6: install angular and bootstrap

   ## bower install angular angular-resource bootstrap

step 7 : we will use the Loopback AngularJS client to create a service, compatible with the angular-resource module, to access the backend API. Create a js folder into the client folder and then type the command below in the console.

   ## lb-ng server/server.js client/js/lb-services.js

check into the js folder if the lb-services.js file is created.
