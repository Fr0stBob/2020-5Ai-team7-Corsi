# System Requirements Specification
### Team 1  

April 29, 2020

### Team Members
Matteo Corsi  
Riccardo Convertino  
Tommaso Osti  
Riccardo Scardoni  

### Revision History

| Version | Date | Name | Description |
| -- | -- | -- | -- |
| 1 | 19/04/2020 | Matteo Corsi | Initial Document |

## 1  Introduction
The Webserver website allows users to simply access all ITI Marconi utilities in a single website.
This documentation will provide instruction for accessing the website.

## 2  Access Website Code
Access to the internet and the GitHub repository used to store the code are required. To access the code is needed also the permission from the group of developement or teachers involved in the project.

## 3  System Maintenanced
The interface consist of two main areas, the buttons area and the side nav. Each of them is implemented in the HTML + CSS + JS code. The server-side code is implemented in a separate PHP file.
When accessing the website will be displayed the page with limited buttons available and the side nav. In the side nav the user is able to login with Classeviva Gruppo Spaggiari Parma credentials. By doing that the leggod in user is able to view all the buttons available and use all the elements of the website. The buttons allow users to access different school utilities while in the side nav there are the login/user area, a simple calendar and a section with the latest news.

## 4  Orario Section
One of the buttons available is the Orario button. It shows a section inside the website with the timetable of classes, teachers and classrooms retrieving the informations from the school MySql database using PHP code.
