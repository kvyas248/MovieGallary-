# MovieGallary-
Your friend asks you to help him to build a simple web application where he can track his movies. You have to allow him to create, update, delete and list movies in a table (with pagination, 10 movies per page). He also wants to keep a small review for each movie. The following criteria have to be fulfilled:

Impliment three microservices -
User/Accounts serivce
Movie Service
Review Service
The micro service must be implemented with Spring Boot.
You can use any database you like (preferred any in-memory database eg.: H2).
Any JPA framework can be used eg.: EclipseLink, Hibernate
The service has to provide a REST API for the client.
The client and the server must communicate with JSON objects.
The server has to reject save and update requests when the required fields are not filled in. (Spring supports JSR-303 validation. You should use @Valid and @NotNull annotations to make it work)
You can use any javascript framework to call REST api. (Preferred ones are Angular JS, React JS or any modern JS framework)
The database must be pre-populated with some initial data.
A movie has the following attributes:

Id
Name (required)
Cover image url
Release date (required)
Genre
Lead Actors/Actresses (should be a many-to-many connection to actors table in the database) (required)
Director (should be a one-to-many connection to director table in database) (required)
The data table must show all of these properies. In case of the joined entities the name has to be displayed.

An Actor has the following attributes:

Id
Name
A Director has the following attributes:

Id
Name
A User has the following attributes:

First Name
Last Name
Email
Joining timestamp
