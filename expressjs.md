

express 

`````
npm i -g express-generator
express nodefolder # create folder 'nodefoler'
cd nodefolder
npm install #install packages in package.json
npm start
`````


http://localhost:3000

`````
cd ./www
vi www
`````

`````
  7 var app = require('../server');
  8 var debug = require('debug')('nodefolder:server');
  9 var http = require('http');

 15 var port = normalizePort(process.env.PORT || '5000');
 16 app.set('port', port);
`````



`````
npm install --save concurrently  #run multiple command
npm install --save nodemon       #monitor change
`````
