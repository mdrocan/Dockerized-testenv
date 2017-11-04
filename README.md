# An example of a Dockerized test environment
- The demo is currently utilizing Jenkins, InfluxDB and Grafana. Its original purpose was to create a test environment for web application testing.

- Use docker-compose to build it and start it up.

### Notice
Usefull stuff to add/configure to Jenkins:
- Fetch changes from version control
- Publish HTML reports
- Publish JUnit test result report
- Publish build data to InfluxDb target

### Notice 2
Configurations via ansible or anything else is not yet there. Most likely a future improvement.

### Notice 3
The Jenkins Debian has some stuff that could be removed and thus simplify the environment.
Could be a future improvement.
