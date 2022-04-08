
## Usage
* Run npm install.
* Add your firebase config details to Server/firebase.js. 
* Run "npm run devStart" to start the app locally
 
 ## Setup your own firebase realtime datastore
 * Navigate to: https://firebase.google.com/
 * Log in with a google account
 * go to console
 * add project
 * enter arbitary name
 * disable google analytics
 * create project
 * Click the webapp ( </> ) icon to add an app 
 * enter arbitary name
 * uncheck firebase hosting offer
 * click register app
 * continue to console
 * click 'Authentication' in left hand menu
 * click 'get started'
 * click on the cog icon to the right of 'project overview'
 * see Web API Key - copy this and past it into the Server/firebase.js code
 * click on realtime database
 * click on create database
 * select geo location
 * start in test mode - can edit the rules to remove the read write permission expiry
 * copy the link at th etime of database window - looks like : https://xxxx-xxxx-default-rtdb.asia-southeast1.firebasedatabase.app/
 * Past it into the Server/firebase.js code
 * You now have linked your database
