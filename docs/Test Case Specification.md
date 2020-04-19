# Test Case Specification For Team7
### April 19, 2020

**Prepared by:**  
Matteo Corsi

### Revisios History

| Version | Date | Name | Description |
| --| -- | -- | -- |
| 1 | 19/04/2020 | Matteo Corsi | Initial document |

## 1  Introduction
This document provides the test cases to be carried out for the Webserver website.
Each item to be tested is represented by an individual test case.
Each case details the input and expected outputs.
## 2  Test Cases: Webserver page
| Test ID | Title | Objective | Setup | Test Data | Test Actions | Expected Result |
| -- | -- | -- | -- | -- | -- | -- |
| 1.1 | Correct Links | Confirm tha all public links are functioning | A browser and internet connetion are available | None | Enter the website - Click all the buttons on the left | All the internal and external links properly function |
| 1.2 | Login and private area | Confirm the correct functioning of the login and private area section | A browser and internet connetion are available | Email: "Private information" - Password: "Private information" | Enter the website - Click on the right nav - Select Login - Enter login informations | Website displays the user info in the right nav and the orario section appears on the buttons on the right |
| 1.3 | Correct Orario | Confirm the correct functioning of the Orario section | A browser and internet connetion are available | Email: "Private information" - Password: "Private information" - Classroom = 122 - Class = 5Ai - Teacher = "Private information" | Enter the website - Login - Click on the Orario button - Select class/teacher/classroom | Website displays the timetable correctly |
| 1.4 | Correct news | Confirm the correct functioning of the news | A browser and internet connetion are available | None | Enter the website - Open the right nav | Website displays the news under the calendar and user/login area |
