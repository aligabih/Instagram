<!DOCTYPE html>
<html lang="en">
<head>
  <title>Instagram Clone</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.5;
      color: #333;
      background-color: #fafafa;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 40px;
      box-sizing: border-box;
      background-color: #fff;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    h1 {
      font-size: 32px;
      font-weight: bold;
      margin-bottom: 20px;
    }
    h2 {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 16px;
    }
    p {
      margin-bottom: 12px;
    }
    ul {
      padding-left: 20px;
      margin-bottom: 12px;
    }
    code {
      font-family: Consolas, monospace;
      background-color: #f5f5f5;
      padding: 2px 4px;
    }
    .link {
      color: #1a73e8;
      text-decoration: none;
    }
    .link:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Instagram Clone</h1>
    <p>
      This project is a clone of Instagram, a popular social media platform. It is built using React and leverages various libraries and dependencies for a seamless user experience.
    </p>
    <h2>Libraries Used</h2>
    <ul>
      <li><code>@emotion/react</code>: A library for writing CSS styles with JavaScript.</li>
      <li><code>@emotion/styled</code>: A library for creating styled components with Emotion.</li>
      <li><code>@mui/material</code>: The Material-UI library, which provides pre-built UI components based on Google's Material Design.</li>
      <li><code>@testing-library/jest-dom</code>: A library for DOM testing utilities when using Jest.</li>
      <li><code>@testing-library/react</code>: A library for testing React components using a simple and intuitive API.</li>
      <li><code>@testing-library/user-event</code>: A library for simulating user events for testing purposes.</li>
      <li><code>react</code>: The core library for building user interfaces in React.</li>
      <li><code>react-dom</code>: Provides the DOM-specific methods for React, used for rendering React components.</li>
      <li><code>react-scripts</code>: A set of scripts and configuration used by Create React App for building and running the application.</li>
      <li><code>web-vitals</code>: A library for measuring and reporting important web performance metrics.</li>
    </ul>
    <h2>Getting Started</h2>
    <p>
      To get started with the project, follow the steps below:
    </p>
    <ol>
      <li>Clone the repository: <code>git clone https://github.com/aligabih/Instagram.git</code></li>
      <li>Change to the project directory: <code>cd Instagram</code></li>
      <li>Install the dependencies: <code>npm install</code></li>
      <li>Start the development server: <code>npm start</code></li>
      <li>Open your browser and navigate to <a class="link" href="http://localhost:3000">http://localhost:3000</a> to view the app.</li>
    </ol>
    <h2>Folder Structure</h2>
    <p>
      The project structure is organized as follows:
    </p>
    <pre>
instagram-clone/
  ├── public/
  │   ├── index.html
  │   └── ...
  ├── src/
  │   ├── components/
  │   │   └── ...
  │   ├── App.js
  │   ├── index.js
  │   └── ...
  ├── .gitignore
  ├── package.json
  └── README.md
    </pre>
    <h2>Contributing</h2>
    <p>
      If you would like to contribute to this project, you can follow these steps:
    </p>
    <ol>
      <li>Fork the repository.</li>
      <li>Create a new branch: <code>git checkout -b feature/my-feature</code>.</li>
      <li>Make your changes and commit them: <code>git commit -m 'Add some feature'</code>.</li>
      <li>Push the changes to your branch: <code>git push origin feature/my-feature</code>.</li>
      <li>Open a pull request in the original repository.</li>
    </ol>
    <h2>License</h2>
    <p>
      This project is licensed under the <a class="link" href="LICENSE">MIT License</a>.
    </p>
  </div>
</body>
</html>
