# Full-Stack Developer Capstone Project

## Project Overview

This project is a comprehensive demonstration of my skills as a Full-Stack Developer, integrating various technologies and methodologies learned during my coursework and experience. The application showcases a web-based solution that includes both front-end and back-end components, utilizing modern development practices and cloud services.

## Features

- **User Authentication**: Secure login and registration using JWT.
- **Responsive Design**: Mobile-first design approach using React and Bootstrap.
- **RESTful API**: Backend API built with Node.js and Express.
- **Database Integration**: MongoDB for data storage with Mongoose for ORM.
- **Cloud Deployment**: Deployed on IBM Cloud for scalability and reliability.
- **Real-time Updates**: Implemented using WebSockets.
- **Error Handling**: Comprehensive error handling and logging mechanisms.

## Technologies Used

- **Front-end**:
  - React.js
  - Bootstrap
  - HTML5 / CSS3
  - JavaScript

- **Back-end**:
  - Node.js
  - Express.js
  - JWT for authentication
  - WebSockets

- **Database**:
  - MongoDB
  - Mongoose

- **Cloud Services**:
  - IBM Cloud

- **DevOps**:
  - Docker
  - Kubernetes
  - CI/CD with GitHub Actions

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/a1monge/xrwvm-fullstack_developer_capstone.git
    cd xrwvm-fullstack_developer_capstone
    ```

2. **Install dependencies**:
    ```bash
    npm install
    cd client
    npm install
    cd ..
    ```

3. **Set up environment variables**:

    Create a `.env` file in the root directory and add the following:
    ```plaintext
    PORT=5000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the application**:

    Start the backend server:
    ```bash
    npm run server
    ```

    Start the frontend development server:
    ```bash
    cd client
    npm start
    ```

5. **Access the application**:

    Open your browser and navigate to `http://localhost:3000`.

## Usage

1. **Register**: Create a new account.
2. **Login**: Authenticate with your credentials.
3. **Explore**: Use the application features, including real-time updates.

## Deployment

The application is deployed on IBM Cloud. To deploy your own version:

1. **Create a container image**:
    ```bash
    docker build -t your_image_name .
    ```

2. **Push the image to a container registry**:
    ```bash
    docker tag your_image_name your_registry/your_image_name
    docker push your_registry/your_image_name
    ```

3. **Deploy on Kubernetes**:
    - Create a Kubernetes cluster on IBM Cloud.
    - Deploy your application using Kubernetes manifests or Helm charts.
      

*This project was created as part of the Full-Stack Capstone Project course on Coursera, in collaboration with IBM Cloud.*
