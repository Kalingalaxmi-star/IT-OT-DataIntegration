Project Title

IT-OT Data Integration

Description

This platform facilitates seamless communication between Information Technology like an ERP system and Operational Telemetry (OT) systems, ensuring efficient automation and data synchronization. The critical components include APIs for data exchange and a user interface for monitoring and configuration.

Getting Started

These instructions will let you know how to perform testing on the POSTMAN tool and the strategy for the testing approach. 

What needs to be tested and Why is testing required?
During the course of API testing, we will be focusing on below points
->Status code check
->Response validation
->Data validation (Min-max length, data type)

API testing verifies that the API behaves as expected in response to valid and invalid inputs, ensuring that it meets the functional requirements.

Prerequisites
POSTMAN Software 8.0 
GitHub
EureQA Automation tool (UI automation tool)

Installation :
POSTMAN : 
Download: Go to the Postman website and download the Postman installer for Windows.

Install: Run the downloaded installer file (.exe) and follow the on-screen instructions. Postman will be installed on your system.

Launch: Once the installation is complete, you can launch Postman from the Start menu or by double-clicking the desktop shortcut.

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

 Repository Management steps :
 Clone the project
 Create own branch
 Changes updated on your collection add to the Git
 Commit changes with the comments
  


