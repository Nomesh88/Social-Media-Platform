# Social Media Platform

## Description

This social media platform is designed to offer a seamless experience for users to interact, post updates, like and comment on posts, and upload multimedia content. Developed with a dual focus on backend and frontend technologies, this platform utilizes Express.js for backend operations and React for a dynamic and interactive user interface.

## Features

- **User Authentication**: Secure sign-up and login functionalities.
- **CRUD Operations**: Create, read, update, and delete posts.
- **Likes and Comments**: Users can like and comment on posts.
- **Multimedia Uploads**: Support for uploading images and videos using Multer.
- **Interactive UI**: Responsive and engaging user interface built with React.
- **Real-time Updates**: Dynamic content updates without refreshing the page.

## Technologies Used

- **Frontend**: React, Axios
- **Backend**: Express.js, Multer
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **File Uploads**: Multer
- **API Communication**: Axios
- **CORS**: Configured for secure API communication

## Installation

### Prerequisites

- Node.js
- npm or yarn
- MongoDB

### Clone the Repository

```bash
git clone https://github.com/yourusername/social-media-platform.git
cd social-media-platform
```

### Frontend Setup

1. Navigate to the frontend directory:

    ```bash
    cd connect-now
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

### Backend Setup

1. Navigate to the backend directory:

    ```bash
    cd Backend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `server` directory with the following environment variables:

    ```bash
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. Start the server:

    ```bash
    npm start
    ```

### Database Setup

1. Set up your database (e.g., MongoDB) on your local machine or use a cloud-based service.
2. Ensure the `MONGODB_URI` in the `.env` file is configured to connect to your database instance.

## Configuration

- **CORS**: Configured in the Express server to allow communication between frontend and backend.
- **API Endpoints**: Ensure that the frontend correctly points to the backend API URLs.

## Testing

Run end-to-end tests to ensure that all components work seamlessly together:

1. Navigate to the `server` directory:

    ```bash
    cd Backend
    ```

2. Run tests:

    ```bash
    npm test
    ```

## Usage

1. **User Registration**: Create a new account via the signup page.
2. **Login**: Log in with your credentials.
3. **Post Creation**: Create new posts and upload multimedia content.
4. **Like and Comment**: Interact with posts by liking and commenting.
5. **Profile Management**: Manage your profile and view your posts.

## Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a Pull Request.

