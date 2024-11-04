**As a** customer account manager  
**I need** a microservice to manage customer accounts  
**So that** we can create, read, update, delete, and list customer information efficiently on the e-commerce website  

### Details and Assumptions
* The microservice should have a well-formed REST API
* Other microservices should be able to call this service as needed
* A database model and `POST` endpoint for creating a customer account are already in place
* Additional endpoints are required to read, update, delete, and list accounts
* This service will be built in an online lab environment, which must be set up for development

### Acceptance Criteria  
```gherkin
Given an e-commerce platform with customer accounts
When a request is made to the microservice
Then the service should allow creating, reading, updating, deleting, and listing customer accounts via REST API endpoints
