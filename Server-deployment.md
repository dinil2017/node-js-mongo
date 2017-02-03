####################################################################
# node-js application server deployment
####################################################################

- Application: Node JS sample application
- Server : Digital Ocean
- Database : MongoDB


References:

	- https://www.youtube.com/watch?v=RE2PLyFqCzE  - youtube link for deployment
	- http://www.traversymedia.com/deploying-node-js-to-digital-ocean/	- commands to be executed
	- https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-16-04 - mongodb installation in server
	- https://www.howtoforge.com/tutorial/install-mongodb-on-ubuntu-16.04/ - mongodb installation in server

Dependent modules:

	- Express
	- MongoDB
	- PM2
	
	
Userful server commands:

	-	npm install - install dependency mentioned in application's package json

	-	cd node-js-mongo/    -  to go to application folder
	-	npm start	-	to start node js application
	-	npm stop	- 	to stop node js application
	-	sudo npm install -g pm2	-	install pm2 module globally, which ensures application up and running
	-	pm2 start ./bin/www --name nodejs-app	-	start application by pm2 with name 'nodejs-app'
	-	pm2 stop nodejs-app	-	stop 'nodejs-app' application started by pm2
	-	pm2 list	-	list all processes
	


