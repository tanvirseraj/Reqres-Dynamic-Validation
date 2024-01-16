# Reqres_Validation_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run Reqres-Dynamic-Validation.postman_collection.json -e Reqres-Dynamic-Validation.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run Reqres-Dynamic-Validation.postman_collection.json -e Reqres-Dynamic-Validation.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/31249794/2s9YsQ7pFG

## Test case list:
1. ### LIST-USERS

2. ### SINGLE-USER
	
3. ### SINGLE-USER-NOT-FOUND

4. ### LIST-<RESOURCE>

5. ### SINGLE -<RESOURCE>

6. ### SINGLE <RESOURCE>-NOT-FOUND
	
7. ### CREATE
	
8. ### UPDATE
  
9. ### UPDATE
  
10. ### DELETE
  
11. ### REGISTER-SUCCESSFUL

12. ### REGISTER-UNSUCCESSFUL

13. ### LOGIN-SUCCESSFUL

14. ### LOGIN-UNSUCCESSFUL

15. ### DELAYED-RESPONSE


	
## Newman Report Summary:
![image](https://github.com/tanvirseraj/Reqres-Dynamic-Validation/assets/85784149/ac96af05-8443-40ef-84f0-757ecf4e4a69)



![image](https://github.com/tanvirseraj/Reqres-Dynamic-Validation/assets/85784149/5f93e720-a953-4f4a-97e2-c2590740ae56)

