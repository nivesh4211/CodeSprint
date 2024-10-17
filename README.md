# CodeSprint

**CodeSprint** is a LeetCode-like coding platform designed to help developers practice coding problems, test their solutions in real time, and improve their programming skills. Built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js), CodeSprint offers a clean, user-friendly interface and integrates a real-time code execution engine using the **Piston API**.

## Features

- **Real-Time Code Execution**: CodeSprint uses the Piston API to execute code instantly across multiple programming languages.
- **User-Friendly Interface**: A simple, intuitive UI that provides easy navigation through problems and solutions.
- **MERN Stack**: A modern web architecture with:
  - **MongoDB** for storing user data, coding problems, and submissions.
  - **Express.js** and **Node.js** for the backend logic and API handling.
  - **React.js** for the frontend, providing a dynamic and responsive user experience.
- **Problem Library**: A growing collection of coding problems ranging from beginner to advanced levels.
- **Code Submission & Evaluation**: Submit your code and receive immediate feedback on correctness and performance.

## Installation

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** and **npm** (or **yarn**)
- **MongoDB**
- An API key for [Piston API](https://piston.rs/)

### Steps to Set Up Locally

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/codesprint.git
    cd codesprint
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the root directory and add your **MongoDB URI** and **Piston API key**:
    ```bash
    MONGO_URI=your_mongodb_uri
    PISTON_API_KEY=your_piston_api_key
    ```

4. **Start the development server:**
    ```bash
    npm run dev
    ```

    The frontend should be running on `http://localhost:3000` and the backend on `http://localhost:5000`.

5. **View and interact with the platform:**

    Navigate to `http://localhost:3000` in your browser to start using CodeSprint.

## Technologies Used

- **Frontend**: React.js, CSS, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **API**: Piston API (for real-time code execution)

## How It Works

- **Users** can select from a list of coding problems, write their code in the editor, and submit it.
- The code is sent to the **Piston API** for real-time execution.
- Feedback on the correctness and performance is displayed instantly.
- **User data**, including problem submissions and scores, is saved to **MongoDB**.

## Contribution

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request explaining your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
