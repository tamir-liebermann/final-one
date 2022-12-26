# Training talk

### Introduction

Training talk is a chat app that allows people who dont like to train alone meet other people
and share their love for sports and train together and eventually they will grow as a community.

# Training talk features:

- Users can signup and login to their accounts.
- Users can create groups and add other users.
- Search users
- Users can remove other users from groups
- one on one chat

## How to run locally

1. Clone this repository [here]
   (https://github.com/tamir-liebermann/tamir-chat-app.git)
2. type cd tamir-chat-app
3. Run npm install to install all dependencies.
4. Start the server npm start

### Usage

- git clone https://github.com/tamir-liebermann/tamir-chat-app.git
- Navigate to the project directory: cd tamir-chat-app
- install dependencies : npm install
- Run npm start to start the application
- connect to the API using Postman on port 4000.

### API Endpoints

| HTTP Verbs | Endpoints              | Action                              |
| ---------- | ---------------------- | ----------------------------------- | ----------------- |
| POST       | /api/user/registerUser | To sign up a new user account       |
| POST       | /api/user/login        | To login an existing user account   |
| POST       | /api/message           | To send a message to another user   |
| POST       | /api/chat              | To create or access one on one chat |
| POST       | /api/chat/group        | To create a group                   |
| GET        | /api/user?search:      | To search for a user                |
| GET        | /api/chat              | Fetching all chats                  |
| GET        | /api/message/chat id   | Fetch all messages from chat        |
| PUT        |                        | /api/chat/rename                    | To rename a group |
| PUT        | /api/chat/groupadd     | To add user to a group              |
| PUT        | /api/chat/groupremove  | To remove user from group           |

### Technologies Used

- [NodeJS](https://nodejs.org/) This is a cross-platform runtime environment built on Chrome's V8 JavaScript engine used in running JavaScript codes on the server. It allows for installation and managing of dependencies and communication with databases.
- [ExpressJS](https://www.expresjs.org/) This is a NodeJS web application framework.
- [MongoDB](https://www.mongodb.com/) This is a free open source NOSQL document database with scalability and flexibility. Data are stored in flexible JSON-like documents.
- [Mongoose ODM](https://mongoosejs.com/) This makes it easy to write MongoDB validation by providing a straight-forward, schema-based solution to model to application data.
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken?activeTab=readme)
  JSON Web Token (JWT) is a compact, URL-safe means of representing
  claims to be transferred between two parties
  enabling the claims to be digitally
  signed or integrity protected with a Message Authentication Code
  (MAC) and/or encrypted.

### License

This project is available for use under the MIT License.
