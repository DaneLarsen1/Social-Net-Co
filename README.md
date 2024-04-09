# Social Network API

## Description
This project presents an API for a social network web application, designed to enable users to share their thoughts, react to friends' thoughts, and manage a friend list. Developed using Express.js for efficient routing, MongoDB as a scalable NoSQL database, and Mongoose ODM for easy data modeling and interaction, this API supports a dynamic and large-scale social networking environment. Optional use of a JavaScript date library or the native JavaScript Date object enhances timestamp formatting for user interactions.

## User Story
**AS A** social media startup  
**I WANT** an API for my social network that uses a NoSQL database  
**SO THAT** my website can handle large amounts of unstructured data

## Acceptance Criteria
- **GIVEN** a social network API
- **WHEN** I enter the command to invoke the application, **THEN** my server is started, and the Mongoose models are synced to the MongoDB database.
- **WHEN** I open API GET routes in Insomnia for users and thoughts, **THEN** the data for each of these routes is displayed in a formatted JSON.
- **WHEN** I test API POST, PUT, and DELETE routes in Insomnia, **THEN** I am able to successfully create, update, and delete users and thoughts in my database.
- **WHEN** I test API POST and DELETE routes in Insomnia for reactions to thoughts and friends to a user’s friend list, **THEN** I am able to successfully create and delete reactions and manage friends.

## Installation

### Prerequisites
- Node.js
- MongoDB

### Steps
1. Clone the repository to your local environment.
2. Navigate to the project directory and run `npm install` to install the required dependencies.
3. Ensure MongoDB is running on your machine.
4. Use `npm start` to run the server, which will also connect to the MongoDB database.

## Usage
With the server running, you can use API testing tools like Insomnia or Postman to interact with the API. Available endpoints allow for managing users, thoughts, reactions, and friends.

### Key Endpoints
- **Users**: GET, POST, PUT, DELETE `/api/users`
- **Thoughts**: GET, POST, PUT, DELETE `/api/thoughts`
- **Reactions**: POST, DELETE `/api/thoughts/:thoughtId/reactions`
- **Friends**: POST, DELETE `/api/users/:userId/friends/:friendId`

## Walkthrough Video
My Insomnia isnt working so Karina gave me permission to submit without it and still get graded. The code has been tested through a friend so i know it works 

## Contributing
Contributions are welcome. Please fork the repository and submit a pull request with your enhancements, or open an issue if you find bugs or have suggestions.

## Questions
For any questions or concerns about the API, please open an issue or contact me directly.

