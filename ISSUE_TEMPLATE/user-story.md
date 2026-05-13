**As a** Customer Service Representative
**I need** the ability to create and manage customer accounts through a RESTful API
**So that**  customer information can be stored, updated, retrieved, and deleted efficiently
      
### Details and Assumptions
    * The microservice will be built on Python and Flask
    * Customer data stored in PostgreSQL
    * The app will follow Agile and DevOps best practices
    * Test-Driven Development will be used
    * Containerised using Docker
    * Deployed done on Kubernetes OpenShift
    * CI/CD pipelines implemented using GitHub
    
### Acceptance Criteria     
    gherkin 
    Given the microservice is running
    When a valid customer account request is submitted
    Then the system should create a new customer account successfully

    Given an existing customer account exist
    When a request is made to recieve the account
    Then the system should return the correct customer account details

    Given an existing customer account exist
    When updated customer infomation is submitted
    Then the system should update the customer account successfully

    Given an existing cutomer account exist
    When a delete request is submitted
    Then the system should remove the cutomer account successfully
