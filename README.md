

# ToDo List Web Application

## Overview
This ToDo List web application is built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to create, view, update, and delete tasks in a simple and intuitive interface.

## Features
- **Task Management**: Create, view, update, and delete tasks.
- **User Authentication**: Register, login, and logout securely.
- **Responsive Design**: Works seamlessly across devices of all sizes.
- **Docker Support**: Easily deploy the application using Docker.

## Technologies Used
- **Frontend**:
  - React.js
  - HTML
  - CSS

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (using Mongoose)

- **Deployment**:
  - Docker

## Getting Started
To run the application locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/to-do-list.git
   cd to-do-list
   ```

2. **Install Dependencies**:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the `server` directory.
   - Define environment variables such as `MONGODB_URI` for connecting to your MongoDB database and `JWT_SECRET` for JWT authentication.

4. **Start the Application**:
   ```bash
   # Start the frontend server
   cd client
   npm start

   # Start the backend server
   cd ../server
   npm start
   ```

5. **Access the Application**:
   Open your web browser and navigate to `http://localhost:3000` to access the ToDo List application.

## Docker Deployment
To deploy the application using Docker, follow these steps:

1. **Build the Docker Image**:
   ```bash
   docker build -t to-do-list-app .
   ```

2. **Run the Docker Container**:
   ```bash
   docker run -d -p 8080:8080 to-do-list-app
   ```

3. **Access the Application**:
   Open your web browser and navigate to `http://localhost:8080` to access the ToDo List application.

## Contribution
Contributions are welcome! Feel free to submit bug reports, feature requests, or pull requests to help improve this project.

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README file according to your project's specific details, such as installation instructions, usage guidelines, and any additional features or functionalities your ToDo List web application may have.
