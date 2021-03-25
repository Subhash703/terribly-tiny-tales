# terribly-tiny-tales-assignment

## This is an assignment task

- Folder Structure
  - client
  - backend

### Technologies and Libraries/dependencies used

- Front-end

  - NextJS
  - axios

- Backend
  - Nodejs
  - express framework
  - axios
  - cors

### How to get up & running

- ### Clone the repository
  - Open the project in your favroite code editor
  - Open 2 terminals, 1st to run the front-end code on `PORT 3000` and second to run server on `PORT 5000` (Make sure the PORT is not being utilized somewhere else)
  - #### Run the following commands
  - For front end run : `npm or yarn install`. It will install all the dependencies and will create a gient node_modules folder
  - `yarn run dev` to start front-end application in browser.
  - For backend run : `npm or yarn install`. (Make sure your are in backend directory).
  - `nodemon start` To start the server (Make sure you are in backend directory)
  - ## That's it! We are ready to go and test the application

### Test cases

You can see a landing page in the browser having an input box with some nice animations.

- This input form takes a comma seperated integers from the user and returns some result : `Pass/Fail`

### Components of the code

- When you run the server in backend, it will start on PORT 5000 by default. The API in backend takes request from frontend in the form Array of rollNumbers.


- After that we make an async request to the external API `https://terriblytinytales.com/testapi?rollnumber=${X}` one by one for each element of the rollNumbers array.


- We return the results (Pass/Fail) Array to front-end.


- In the frontend I'm making an async POST request to the backend nodejs API which I've created.


- We get response as results Array which we show in tabular form.


## You can see the response from the API in the table

## Happy Coding!
