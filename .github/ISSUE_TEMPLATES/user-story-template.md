**As a** software engineer  
**I need** to complete the microservice by implementing REST API's for READ, UPDATE, DELETE, and LIST  
**So that** users can perform CRUD operations on the data, and we maintain a 95% code coverage.  
      
### Details and Assumptions
    * The microservice has existing endpoints for creating and retrieving data.
    * The data is stored in a database accessible to the microservice.      
### Acceptance Criteria     
    gherkin 
    Given the microservice is running
    When a request is made to retrieve data (READ) with a valid identifier
    Then the microservice should respond with the corresponding data
    And the response should have a status code of 200.

    Given the microservice is running
    When a request is made to update data (UPDATE) with a valid identifier and new data
    Then the microservice should update the existing data
    And the response should have a status code of 204.

    Given the microservice is running
    When a request is made to delete data (DELETE) with a valid identifier
    Then the microservice should delete the corresponding data
    And the response should have a status code of 204.

    Given the microservice is running
    When a request is made to list all data (LIST)
    Then the microservice should respond with a list of all available data
    And the response should have a status code of 200.

    Given the microservice is running
    When any request is made to the existing endpoints
    Then the code coverage should be maintained at 95% or higher.