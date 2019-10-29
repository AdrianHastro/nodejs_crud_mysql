# nodejs express crud mysql
nodejs, express, ejs, mysql 

# Config lib
npm install express -save

npm install express-validator -save
npm install body-parser -save
npm install method-override -save
npm install express-flash -save
npm install cookie-parser -save
npm install express-session -save

npm install ejs -save
npm install mysql -save

npm install express-myconnection -save

# coinfig conn DB in file config.js
var config = {
	database: {
		host: 'localhost', port: 3306,
		user: 'root', password: 'xxx',
		db: 'xxx'
	},
	server: { host: '127.0.0.1', port: '3000' }
}

# config package
"main": "app.js",
...
...
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node app.js"
},
