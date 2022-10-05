# dmoney-api-jmx

## Technology and Tool Used
- Apache JMeter
- Java

## Requests
1. Login to user
2. Get user list
3. Create a user
4. Search the newly created user by id
5. Search the newly created user by phone number
6. Search the newly created user by email
7. Update the user phone number
8. Delete the user

## How to run this project
- clone this project
- copy the Dmoney-Load-Test.jmx file into bin folder of installed location of Jmeter
- open the Dmoney-Load-Test.jmx file with jemeter & run the project
- to Generate report on the command prompt, delete the already copied .csv file and Report folder from the project
- hit the following command:
- $ jmeter -n -t Dmoney-Load-Test.jmx -l Dmoney-Load-Test.csv -e -o Reports

## Prerequisite
- Jmeter and Java must be installed

## Generated Html Report
![Screenshot (48)](https://user-images.githubusercontent.com/29010350/194117178-00cf969d-f4fe-4bc6-a85c-896d563e7b16.png)
![Screenshot (49)](https://user-images.githubusercontent.com/29010350/194117235-618dfbd7-e934-470f-8544-64cd92182edc.png)

## Summary Report
![Screenshot (46)](https://user-images.githubusercontent.com/29010350/194118069-c7f62945-854c-464b-ab13-51fe43477f01.png)

## Requests Screenshot:
![Screenshot (50)](https://user-images.githubusercontent.com/29010350/194118471-ee0bc6b4-8b72-4e7f-9ef2-0f1f641be007.png)


