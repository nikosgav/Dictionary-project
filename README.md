# dictionary-app
This app is a lab project, which is a small a dictionary application.It uses REST web services and returns response as a JSON object.First, it creates Login web-service which creates a string ID if the user is authenticated successfully.

Credentials are then stored in a HashMap.Then Words service returns words that match with the String ID or returns "Permission Denied" as a response if the stringID is expired. 

Database for this app is given in a 'services.sql' file.
