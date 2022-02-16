# React Task Tracker
This app is used to record and track user-created tasks, which can be viewed later to plan out the day. This project is a frontend application made entirely using ReactJS, HTML, CSS and JSON server to store data. When the app is booted up, it fetches the last saved data on the JSON server using a `GET` request. Other tasks such as addition and deletion of tasks also involve sending `POST` and `DELETE` HTTP requests to the server as well.

![intro](https://user-images.githubusercontent.com/64117930/154270989-ea19338f-9f9c-4b3d-91ff-373a0659292e.jpg)

## Adding a task
To add a task, click on the button 'Add' and enter the task name, date and time, and if a reminder is required for the task. Tasks with reminders set as ON have a green indicator on the task card in the list.

![add](https://user-images.githubusercontent.com/64117930/154270200-1b04970a-77e9-4a77-b470-8fe456a8cec3.gif)


# Deleting a task
To delete a task, click on the X on the task card in the list.

![delete](https://user-images.githubusercontent.com/64117930/154270232-de6dcdbc-a612-4158-960c-c2445c3bc84f.gif)


# JSON Server
A JSON Server mimics a backend and handles `GET`, `POST` and `DELETE` requests. When starting up the app, run `npm run server` to start the JSON server. It currently starts up on port 5000, and the app starts on port 3000.

![json server](https://user-images.githubusercontent.com/64117930/154270244-2207693a-340a-4a1a-b786-ebe4c7c7fc92.jpg)

__________________________________________________________________________________________

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

You will also have to run the JSON server by running:

### `npm run server`

in another CLI.

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.
