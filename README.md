# LendsqerAPIAutomation

How to set up and run the test scripts

**Method 1**
Use postman runner 
1. Launch the Postman web application (https://identity.getpostman.com/login) or desktop application
2. Login/create an account
3. Create a new collection
4. Import the "Oyebode_Lendsqr_Assessment.postman_collection.json" file into the collection
5. Import the "Lendsqr_Environment.postman_environment.json" file into the collection
6. Right-click the newly created collection and select "Run Collection"
7. Click on the "environment" drop-down and select the imported collection
8. Click the "Run New Collection" button


**Method 2**
- Use Newman 
- **Pre-conditions**
The user has node installed   
The user has newman installed 

1. Download Postman collection & enviroment
2. Save collection & environment to desired location
3. Open cmd and change the root directry to where the automated file is stored - cd c:\automated filed
4. Run this command to run the automated scripts - Newman run Oyebode_Lendsqr_Assessment.postman_collection.json -e  Lendsqr_Environment.postman_environment.json -r htmlextra
5. Check the file directory the JSON files are saved
6. A folder called "newman" would be created
7. Open the newman folder
8. An automated test summary report should be saved
   
