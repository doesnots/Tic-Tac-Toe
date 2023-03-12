<h1>Tic-Tac-Toe Game in React</h1>
This is a simple Tic Tac Toe game built with React. You can play the game in your web browser. Follow the instructions below to deploy the game on your local machine.

<h2>Prerequisites</h2>
Before deploying the game, make sure you have the following software installed on your machine:
<div>
<ul>
  <li>Node.js and npm (Node Package Manager)</li>
  <li>Git (optional, but recommended)</li>
</ul>
</div>
<h2>Installation</h2>
To install the game, follow these steps:
<ol>
  <li>Clone the repository to your local machine using Git: <br>
    ```
    git clone https://github.com/username/Tic-Tac-Toe.git
    ``` <br>
    Alternatively, you can download the source code as a ZIP file and extract it to a directory on your machine.
  </li>
  <li>Open a terminal or command prompt window and navigate to the directory where you cloned or extracted the source code.</li>
  <li>Install the dependencies by running the following command:
    ```bash
    npm install
    ```
  </li>
</ol>
<h2>Running the Game</h2>
To run the game, follow these steps:
<ol>
  <li>Open a terminal or command prompt window and navigate to the directory where you cloned or extracted the source code.</li>
  <li>Run the following command to start the game:
    ```bash
    npm start
    ```
  </li>
  <li>To play the game, click on a square to make a move. The game will automatically detect if someone has won or if the game is a draw.</li>
</ol>
<h2>Building and Deploying the Game</h2>
To build and deploy the game to a production server, follow these steps:
<ol>
  <li>Open a terminal or command prompt window and navigate to the directory where you cloned or extracted the source code.</li>
  <li>Run the following command to build the game:
    ```bash
    npm run build
    ```
  </li>
  <li>Deploy the contents of the build directory to a web server of your choice. You can use any web server that supports serving static files, such as Apache or Nginx.</li>
  <li>If you want to serve the game on a specific port, you can use a package like `serve` to serve the build files:<br>
    ```bash
    npm install -g serve <br>
    serve -s build -l 3000
    ```
  </li>
</ol>
This will start a web server on port 3000 and serve the game from the build directory.
