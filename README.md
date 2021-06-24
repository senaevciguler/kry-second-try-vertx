# KRY assignment

The service consists of a backend service written in Vert.x (https://vertx.io/)
that keeps a list of services (defined by a URL), and periodically does a HTTP GET to each and saves the response ("OK" or "FAIL").

# Run

just a time we should execute DBMigration class.

then

    ./gradlew clean run 

    For windows
    gradlew clean run

then we can insert, update, delete and check url with interface

    http://localhost:8080/


###Frontend/Web track:

- We want full create/update/delete functionality for services
- The results from the poller are not automatically shown to the user (you have to reload the page to see results)
- We want to have informative and nice looking animations on add/remove services