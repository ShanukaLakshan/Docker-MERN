create mern app and dockerize

<!--  -->

npm init -y

<!--  -->

npm install express mongoose nodemon cors body-parser

<!-- Add to package.json  -->

"scripts": {
"test": "echo \"Error: no test specified\" && exit 1",
"start": "nodemon server.js"
},

<!--  -->

mongodb+srv://db_user:<password>@cluster0.nne2veg.mongodb.net/test

<!--  -->

mongoose
.connect(DB_URL)
.then(() => console.log("Database Connected Successfully"))
.catch((err) => console.log(err))

<!--  -->

Create modele -> posts.js -> craete schema and export it

<!--  -->

Create routes -> posts.js -> create routes and export it

<!--  -->

Body parser
server response convert to json

<!--  -->
