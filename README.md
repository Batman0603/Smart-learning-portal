# <h1 align="center"> Smart Learning Portal </h1>

This project is a full-stack application developed during an internship.

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your machine:

*   [Git](https://git-scm.com/)
*   [Node.js](https://nodejs.org/en/)
*   [npm](https://www.npmjs.com/) (comes with Node.js)

### Cloning the Repository

First, clone the repository to your local machine.

```bash
git clone https://github.com/<your-username>/Internship-journey.git
cd Internship-journey
```

### Backend Setup

1.  Navigate to the backend directory:
    ```bash
    cd backend
    ```
2.  Install the dependencies:
    ```bash
    npm install
    ```
3.  Create a `.env` file in the `backend` directory and add the environment variables (see the format below).

4.  Start the backend server:
    ```bash
    npm start
    ```

### Frontend Setup

1.  Navigate to the frontend directory from the root project folder:
    ```bash
    cd frontend
    ```
2.  Install the dependencies:
    ```bash
    npm install
    ```
3.  Start the frontend development server:
    ```bash
    npm start
    ```

## Environment Variables (`.env`)

The backend requires a `.env` file with the following format. Create this file in the `/backend` directory.

```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```
