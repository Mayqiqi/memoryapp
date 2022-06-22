The twitter clone project allows user to create a post, update a post, like a post and delete post.

The project is mainly deployed through MERN, that is MongoDB, React, Epress.js and Node.js.

My project is constructed through two parts: the frontend client and backend server.

1. My backend is built by implementing Node.js and Express.js. I also connect mongoDB through Mongoose.

2. Then I constructed my fronted Client mainly through React.js and Redux.
3. The most important thing is using Redux to interact with the frontend. 
    I implemented redux by creating three parts: actions, reducers and store. In the actions I create the CRUD actions for the user to create a post, update a post, like a post and delete a post. In the reducers folder, the reducer could return a new state according to the different actions the user input. Then in the main file, that is my App.js file, I store all the states which allows all my component access these states.

4. In the front-end, i alsoe have two folders to manage my sinle post and all posts layout, and each file could dispatch my current state.

5. To interact with the backend, I created a controller file to implement my router by using express.js. In the controller, I get the users' actions through the asycronous function.

6. This is all how my project is implemented.

This project provides me great exprience on implemnting full stack application, which not only allows me to learn new techniques, but also give me an valuable experience on learning new things to solve problems. The final rendering is beautiful, just like a real twitter. This project also encourages me to learn new things, implement new things and create more projects.