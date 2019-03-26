This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This project used [https://jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com) for mock data.  

I wrote really simple action creator and reducer and used it in a component. I feel the best way to really understand something is create the simplest version to run. Then build more complex versions of it.  This project helped me conceptualize what the action creator and reducer does.

This excercise included 'thunk'.  Thunk is a way to use action creators with api calls.  Typically they are asynchronous so thunk waits to get the response from the api call that is fetching the data, then dispatches it to the reducers.  Without thunk you will likely dispatch before the response and your reducer will fail.


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
