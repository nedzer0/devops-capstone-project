**As a** Developer
**I need** automation to build and test every pull request
**So that** I do not have to rely on manual testing of each request, which is time-consuming
      
### Details and Assumptions
    * GitHub Actions will be used for the automation workflow
    * The workflow must include code linting and testing
    * The Docker image should be postgres:alpine for the database
    * A GitHub Actions badge should be added to the README.md to reflect the build status

### Acceptance Criteria     
    Given code is ready to be merged
    When a pull request is created
    Then GitHub Actions should run linting and unit tests
    And the badge should show that the build is passing
