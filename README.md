# Goals manager app created with the MERN stack

This was a basic app created with the MERN stack to learn its basics following this [tutorial](https://youtu.be/-0exw-9YJBo?list=PL3jF6w77jsS-kn6Km2bvLEt2J-2ByIzsj)

## Backend abilities learned
- Creating databases and clusters in the MongoDB Cloud
- Using Mongoose to connect to the database on ExpressJS
- Creating the server.js as the main file for the app
- Creating middleware files to add functionalities and overriding default behaviours like the error handler
- Creating and managing routes with the express router
- Creating models and controllers to manage the entities in the app
- Setting up script to execute different commands
- Configuring the JWT to encrypt passwords

## Frontend abilities learned
- Creating a basic React app with the Redux template
- Using Redux to control "global variables"
- Using the useNavigate method from react-router-dom to redirect users
- Using the useEffect and useState method from react to manipulate state variables
- Using the useSelector and useDispatch methods from react-redux to get and dispatch methods from the "global variables"
- Using the createSlice and createAsyncThunk from @redux-toolkit to manage the global variables and methods
- Using Axios to connect to the API endpoints
- Using toast messages to show error messages

## How to run the app
- Make sure the NODE_ENV variable is set to development
- Set the PORT, MONGO_URI, and JWT_SECRET environment variables to your needs
- Run `npm install`
- Run `concurrently \"npm run server\" \"npm run client\`
- Go to `localhost:[port-you-set-in-the-frontend]` and see the app
