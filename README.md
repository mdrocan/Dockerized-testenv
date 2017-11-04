# An example of a Dockerized test environment

### About

The demo creating a test environment that includes Jenkins, InfluxDB and Grafana, all running on Docker. Its original purpose was to create a test environment for web application testing and creating the necessary test reports. The solution has been tested and designed together with the following project: https://github.com/mdrocan/Protractor-tests-for-Jenkins

### Installation

- Use docker-compose to build it and start it up.

### Configuration

Usefull stuff to add and configure to Jenkins:
- Changes to software project fetched from version control
- Publish HTML test reports
- Publish JUnit test result
- Publish test data to InfluxDb

Configurations via ansible or anything else is not done.
Most likely a future improvement.

### About

The Jenkins Debian has some stuff that could be removed and thus simplify the environment.
Could be a future improvement.

## Author

Designed by Mikko Drocan.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
