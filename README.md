
# MERN STACK Chat Application

This is a real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Firebase storage for media handling and Google authentication for user-specific chat rooms.


## Features

- **Real-time Messaging**: Send and receive messages instantly.
- **User Authentication**: Google authentication for secure login and user-specific chat rooms.
- **Firebase Storage**: Upload and store media files (images, videos) in Firebase storage.
- **User-specific Chat Rooms**: Private chat rooms for one-on-one communication.
- **Notifications**: Real-time notifications for new messages.

## Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB
- **Authentication**: Google Authentication using Firebase
- **Storage**: Firebase Storage
- **State Management**: Redux Thunk
- **Styling**: Tailwind CSS

### Prerequisites

Ensure you have the following installed:
- Node.js (v16+)
- npm or yarn
- MongoDB
- Firebase Project Setup

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/rakeshrkzzz/chat-app-mern.git
cd chat-app-mern
```
2. **Install dependencies for the frontend:**
```bash
cd frontend
npm install
```
3. **Install dependencies for the backend:**
```bash
cd ../backend
npm install
```
4. **Create environment variables:**
Create a ```.env``` file in the ```server``` directory with the following variables:
```bash
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
FIREBASE_APP_ID=your_firebase_app_id
```
Update the ```.env``` file in the ```client``` directory for Firebase configuration if needed.

## Running the Application
1. **Start the backend server:**
```bash
cd backend
npm run dev
```
2. **Start the frontend:**
```bash
cd ../frontend
npm start
```
3. **Open your browser:**
Navigate to ```http://localhost:3000``` to view the application.

## Folder Structure
### Client (React)
- src
    - components: Reusable UI components.
    - features: Redux slices and actions.
    - pages: Different pages for routing.
    - utils: Utility functions.
    - assets: Images, icons, and other static assets.
### Server (Node.js/Express)
- controllers: Application logic for handling requests.
- models: Mongoose models for MongoDB.
- routes: Express routes for API endpoints.
- middleware: Authentication and other middleware.
- config: Configuration files (e.g., database connection).

## Contributing
Feel free to contribute to this project by submitting issues or pull requests.

## License
This project is licensed under the MIT License.

## Contact
For any questions or feedback, please contact [Rakesh](https://github.com/rakeshrkzzz) .