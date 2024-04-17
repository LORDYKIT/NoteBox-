# NoteBox Project

Welcome to NoteBox – Your Personal Note-Taking Haven!

## Project Overview

NoteBox is a note-taking web application developed using Node.js, Express, and MongoDB. It provides users with a platform to effortlessly create, organize, and collaborate on notes. This README file serves as a guide to help you set up and run the NoteBox project locally.

## Getting Started

To get started with NoteBox on your local machine, follow these simple steps:

### Prerequisites

1. **Node.js:** Make sure you have Node.js installed on your machine. You can download it [here](https://nodejs.org/).

2. **MongoDB:** Install and set up MongoDB on your machine. You can download it [here](https://www.mongodb.com/try/download/community).

### Installation

1. Clone the NoteBox repository to your local machine:

   ```bash
   git clone https://github.com/LORDYKIT/notebox.git
   ```

2. Navigate to the project directory:

   ```bash
   cd notebox
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root of the project with the following content:

   ```env
   PORT=your_preferred_port
   MONGODB_URI=your_mongodb_uri
   ```

   Replace `your_preferred_port` with the port number you want the server to run on, and `your_mongodb_uri` with your MongoDB connection URI.

### Running the Application

1. Start the Node.js server:

   ```bash
   npm start
   ```
This will install the following dependencies:

* bcrypt: Library for hashing passwords.
* connect-mongo: MongoDB session store for Express.
* dotenv: Loads environment variables from a .env file.
* ejs: Embedded JavaScript templates for rendering HTML.
* express: Web framework for Node.js.
* express-ejs-layouts: Layout support for EJS in Express.
* express-session: Session middleware for Express.
* method-override: Middleware for handling HTTP method overrides.
* mongoose: MongoDB object modeling for Node.js.
* nodemon: Utility that monitors for changes and automatically restarts the server.


   The application will be accessible at `http://localhost:your_preferred_port` in your browser.

2. Open your browser and navigate to the specified port.

3. Enjoy using NoteBox!


## License

This project is licensed under the [MIT License](LICENSE.md).

## Acknowledgments

- Special thanks to Dr. Charbel for helping us complete this project.

Feel free to reach out if you have any questions or issues. Happy note-taking!
