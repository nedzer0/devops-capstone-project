**As a** customer account manager  
**I need** a microservice with REST APIs to create, read, update, delete, and list customer accounts  
**So that** other microservices can reliably manage customer data for the e-commerce website 
      
### Details and Assumptions
    * The database model and create customer endpoint are already implemented
The microservice is built with Python Flask
The environment will be prepared for further development
REST APIs for read, update, delete, and list operations need to be added

### Acceptance Criteria     
    gherkin 
    Given the microservice is running
    When a REST API call is made to read, update, delete, or list customer accounts
    Then the correct customer data is returned, updated, deleted, or listed as expected
