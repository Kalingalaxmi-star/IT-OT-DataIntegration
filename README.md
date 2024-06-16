Project Title

IT-OT Data Integration

Getting Started

These instructions will let you know how to perform testing on the POSTMAN tool and the strategy for the testing approach. 

Prerequisites
POSTMAN Software 8.0 
GitHub
EureQA Automation tool (UI automation tool)

Running the tests
To setup the testing environment, We need to run configuration-related APIs

Product Information API :
-> Adding new product information: POST call
-> Updating existing information: We will be using below API calls
 Get call-> get the  product information (unique ID will be fetched)
 Put call = using the unique ID we can update the product information
-> Product data retrieval: GET call

Order Processing API:
->  Order Placement: POST call
->  Status update: We will be using below API calls
GET call to get the  order information(a unique ID will be fetched) 
Put call = using the unique ID we can update the order information
-> Order retrieval: GET call

Dashboard :
-> Dashboard displays accurate information: Get call-> Get the  order information

Configuration :
->User creation: Post call
-> User fetch: Get call
-> User update: Put call

Data Consistency:
-> Confirm that changes made through the UI are correctly reflected in the backend data:
 Get the order information: Get call
 Get the product information update: Get call

What needs to be tested and Why is testing required?
During the course of API testing, we will be focusing on below points
->Status code check
->Response validation
->Data validation (Min-max length, data type)

 Repository Management steps :
 Clone the project
 Create own branch
 Changes updated on your collection add to the Git
 Commit changes with the comments
  


