# NoSQL-Ch-18
This application demonstrates using noSQL database, MongoDB and storing information that simulates a social media networking website. The application allows you to add users, add friends, make comments, and add reactions. The other CRUD operations are also available for all of these actions. There is a live demonstation of the application in use that show cases all functionalities.

## User Story
- AS A social media startup
- I WANT an API for my social network that uses a NoSQL database
- SO THAT my website can handle large amounts of unstructured data

## Acceptance Criteria

- GIVEN a social network API
- WHEN I enter the command to invoke the application
- THEN my server is started and the Mongoose models are synced to the MongoDB database
- WHEN I open API GET routes in Insomnia for users and thoughts
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete users and thoughts in my database
- WHEN I test API POST and DELETE routes in Insomnia
- THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list


### Installation/Operation Guide
- Begin by running npm i to download all of the necessary dependencies
- Then start your Mongo database noSQL server, via mongod
- Then run npm start, which whill run your node server.js file and begin the application


### Screenshots from Insomnia and VSCode Route Information

<img width="1179" alt="Screen Shot 2022-10-13 at 9 07 44 PM" src="https://user-images.githubusercontent.com/105763252/195740253-889dc09b-387b-4f81-9de5-2d753f473b44.png">


<img width="1326" alt="Screen Shot 2022-10-13 at 9 09 06 PM" src="https://user-images.githubusercontent.com/105763252/195740254-e62f4f0c-5d9d-46e9-9d4e-b259a74102a3.png">


