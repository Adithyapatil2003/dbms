# Songs Database
This application is a comprehensive software system designed to manage and organize vast music collections. It features secure user authentication, detailed song catalog management, search and filtering, playlist CRUD, and integrated audio playback. This application is accessible via responsive web design. Technologically it leverages React for the frontend, Flask for the backend, and MariaDB for the database. This enables efficient song management, discovery, and an enhanced listening experience.


# Login
<img width="738" alt="login png" src="https://github.com/Adithyapatil2003/dbms/assets/117760549/a984e20f-a3fb-4901-b0f0-92027ef5d895">

# Home
<img width="738" alt="Home" src="https://github.com/Adithyapatil2003/dbms/assets/117760549/c38714a5-6d18-4533-9281-f544aa8fc61e">

# Playlist
<img width="738" alt="Playlist" src="https://github.com/Adithyapatil2003/dbms/assets/117760549/8661e854-617e-49fc-a72e-6ee988346500">

# Search
<img width="738" alt="Search" src="https://github.com/Adithyapatil2003/dbms/assets/117760549/950f37fc-3d6e-4ac3-914b-63067d9c48c4">


# 


-   We've used MariaDB for this application, to download the latest version visit(https://mariadb.org/download/) or any other equivalent SQL database should work.
  -   Import the already created db(dummy.sql) using HeidiSQL(GUI for MariaDB)
  -   Or if you want to create the database from scratch, follow these steps
        - Create a spotify app here(https://developer.spotify.com/documentation/web-api) and paste the client-id and client-secret in client-id.txt and client-secret.txt
        - Run auth.py once this fills out our spotify access token which we use to insert metadata into our database.
        - Modify the artists.txt as you wish depending on whose info you need in your database.
        - Run serv.py also modify the connector config to your db's config
        - Now our metadata is inserted, now to make those songs playable we insert the yt links of those songs and embed them into our app.
        - Run yt.js
        - Now our database setup is complete.

## Modify the connector config in backend/app/__init__.py
### Run the run.py file

  ### git clone https://github.com/360smchandan/dbms.git

 ### cd dbms

## Available Scripts

In the project directory, you can run:
### `npm install`
### `npm start`

Congrats you have successfully setup the app!!!

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.


