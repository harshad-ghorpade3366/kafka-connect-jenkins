[![Build Status](https://snap-ci.com/yaravind/kafka-connect-jenkins/branch/master/build_image)](https://snap-ci.com/yaravind/kafka-connect-jenkins/branch/master)

# Kafka Connect Jenkins

Kafka Connect Connector for Jenkins Open Source Continuous Integration Tool.

## What is it?

To do

## What can I do with it?

In an organization, there can be one or more CI/CD servers (usually Jenkins) managing the day to day builds
and deployments of various components or services. We usually see each business unit (or vertical) managing
their own Jenkins instance. Any such organization can benefit from treating **build events** same like any other
transactional or master data.

These **build events** enable the following use-cases

- Management of Value Streams of all its products
   - Frequency of builds and deployments
        - Once per day
        - Many times a day
        - Once per week
        - Several per week
        - Once per month
        - Less often
   - Cycle times of deployments
   - Build times
   - Build statuses
- Consolidation opportunities thus reducing technical debt
    - Diversity of technology stack (versions, libraries etc.)
    - Diversity of source control systems
    - Diversity of testing libraries
    - Diversity if build systems (Ant, Maven etc.)
    - Diversity of usage
        - Build
        - Test
        - Deploy
        - SCA
        - Batch tasks
        - Operations
    - Diversity of build infrastructure deployments
        - Number of Masters, Build Agents and Executors
- Enterprise wide Release Health Scorecards
    - Trends on bugs
    - Trends on security checks
- Cost saving opportunities
    - Is Jenkins usage growing?
    - Proper reuse of existing infrastructure across business units an teams
    - Data driven forecasting of future infrastructural needs
- Other
    - Plug-ins being used in Jenkins
    - Etc.

## How to use it?

To do

### Dependencies

- Maven 3.x
- JDK 1.8 or more
- [Spock Framework](https://spockframework.github.io/spock/docs/1.0/index.html)


### Configurations

To do

## Contribute

- Source code: https://github.com/yaravind/kafka-connect-jenkins
- Issue tracker: https://github.com/yaravind/kafka-connect-jenkins/issues

## License

The project is licensed under the Apache 2 license.