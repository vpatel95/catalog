# catalog

 an application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.
 
##Enviroment

	python2 ONLY, flask, sqlalchemy, requests

##Requirement

	To use Google oauth API, you need to apply for an Google oauth credential.
	Then download the json file on the detail page.
	Rename it as: client_secrets.json
	Replace your file with the file in directory

##Testing

	Request the /add_data api, it will automaticlly generate some data

##Running the app

	```
		python application.py
	```
