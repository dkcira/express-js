https://egghead.io/courses/getting-started-with-express-js

npm init -y
npm i -S express
touch index.js

node index.js
open browser at localhost:3000

if you add
 "scripts": {
    "start": "node index.js"
  },
 in package.json
 you can use 'npm start' for starting the server

 npm i -D nodemon
 add
     "dev": "nodemon index.js"
to package.json
run: npm run dev
now when you make changes to index.js the server starts automatically

