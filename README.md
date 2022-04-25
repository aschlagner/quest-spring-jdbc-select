# SEA8 - Spring JDBC Quest 01 - Select

## Challenge: Selection of magic schools


*Fork* the following repository: https://github.com/WildCodeSchool/quest-spring-jdbc-select.

You are tasked with developing a Harry Potter fan site in order to add additional functionality. As it stands, the site displays the list of all the characters within the wizarding universe described in the series.

You're going to have to import the database *spring_jdbc_quest* which is available to download here.

Then, in *MySQL*, create a user with the id *h4rryp0tt3r* and the password *Horcrux4life* and give this user all possible permissions over the database *spring_jdbc_quest*.

> You will start by testing the site and see how it works.

**Be sure to check all the classes listed in the repo before starting the challenge!**

1. Import the database: *spring_jdbc_quest*
2. In *MySQL*, create the user *h4rryp0tt3r* with the password *Horcrux4life* and give all permissions for *spring_jdbc_quest* to the user
3. Test that the site is working correctly
4. Make it so that a list of all schools is displayed on the route: */schools*
5. Make it so that it is possible to search schools by ID on the route: */school?id=$id*
6. Make it so that it is possible to search schools by country on the route: */school?country=$country*

## Validation criterias

- The project runs well using the required database and user credentials.
- It is possible to display a list of all schools.
- It is possible to search for a school by its id.
- It is possible to search for a school by country.
- The *JDBC* code is in a *repository* class and not in a *controller* class.
- JDBC resources are closed properly.
- The code is available on GitHub.
