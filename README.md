# PWA Budget Tracker

![image](https://user-images.githubusercontent.com/47426171/125886715-63d8a911-248c-452c-874e-32b100364aba.png)



This application uses mongoDB, mongoose, and express to create a workout tracker app that creates dynamic reports of the user's workouts.

## Table of Contents

* [Installation](#installation)

* [Usage](#usage)

* [Technologies used](#Technologies)

* [Questions](#questions)



## Installation Instructions <a name="installation"></a>
To use with a local database, clone the git repository and install the dependencies using ```npm install```. Then create and seed the database with  db/schema.sql and seeds/index.js. Finally run server.js to start listening for requests.

Otherwise, the app is deployed live in heroku, and can be found [here](https://smg061-budget-tracker.herokuapp.com/)

## Usage <a name="usage"></a>

Users can choose to add expenses or deposits to their budget. The users expenses and deposits will saved on displayed on the main page's plot area
![img](https://user-images.githubusercontent.com/47426171/125994754-f6773da8-7d9c-4e4c-9b51-d984f6ef7123.png)


Users can install the app to their desktop from the chrome navigation bar and open the app offline.


![img](https://user-images.githubusercontent.com/47426171/125995013-2fa0261e-7b80-4407-bd8f-1c4985d35572.jpg)


If the user is offline, expenses will be stored in IndexedDB temporarily until internet connection is available again. Once there is internet connection, the cached expenses/deposits will be saved to the database.



## Technologies used <a name="technologies"></a>
  ** Node.js
  ** Express.js
  ** MongoDB
  
  


## Questions <a name="questions"></a>
My Github profile can be found [here](https://github.com/smg061). 
You can reach me at: max.go.95@gmail.com




