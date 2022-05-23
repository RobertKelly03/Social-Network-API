#Social Networking API

     

#Description
An API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

video of the application:
![social-network-api](./assets/users.gif)

![gif1](https://user-images.githubusercontent.com/55413812/169722690-f2809c26-3a05-46fc-9f10-58f9c1c5525c.gif)



#User Story

AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
Acceptance Criteria

GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list


#Installation

clone down

npm install

Usage

npm start

