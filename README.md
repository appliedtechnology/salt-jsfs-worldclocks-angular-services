# &lt;/salt&gt;

## Angular - Services and Testing

This exercise builds on the previous World Clocks exercise we did yesterday, but now we are going to introduce services. And testing.

You can continue from the app you created or recreate the app from the instructions in that repository.

Build the world clocks again, but this time:

* Create a logger service `ng generate service logger` that logs messages to a text-file `access-log`
  * Add a method that logs a message `timestamp - description of event`
  * Add a method to read the last 10 messages from the file

* Add a service to get time-zones `tz.json`
  * These timezones will drive the layout of the application.
  * Add a method to get all timezones and to get an individual timezone
  * Log each access to the file with the logger service

* Write tests
  * Unit tests for your services
    * Unit tests does not touch the network or filesystem
  * Component tests for your components
    * Using the Angular testing framework
  * E2E tests for the entire application
    * verifies that your application works - smoke test
    * 1 or 2 tests suffices

