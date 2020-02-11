# 361_se1_agile_project
We are using Reactjs library to develop our web app.

#### Run App 
`npm start` is used during development to see your changes and such. It will auto-load your changes (thank goodness). And, It should automatically open the app in your defualt browser. 

Note: It might take a while to load.


#### Deploy App
`npm run build` will create an optimized build of your app in the "build" folder. This will be used at end when we're done, or if we want to test a version.


#### Notes
- In index.js, I changed: serviceWorker.register() so our app loads faster offline. Really only matters if you are going to `npm start` your stuff a lot. But you shouldn't need to.