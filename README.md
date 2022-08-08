# SensorsDB

The third task of IoT track in the summer internship with Smart Methods is to use the sensors with the database to collect data and use it in the web.

Firstly, we need to design the database.

Secondly, we chose MongoDB npm with the sensor models.

The name of database is sm-sensor.

Next, we start with setting the server which we will use express npm for easier use, we need to fetch the data from the database, and we used the GET method.

Then, we fetch the data and pass it to the index page.

Next, we simulate the DB data through seeding fake values.

Finally, we display the data on the index page by using loops that will loop over the object returned by database. Used .ejs for dynamic pages.
