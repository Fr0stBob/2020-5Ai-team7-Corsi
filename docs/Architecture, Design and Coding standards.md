## Architecture, Design and Coding standards
**Team 7**
April 19, 2020

**Team Members**  
Matteo Corsi  
Riccardo Convertino  
Tommaso Osti  
Riccardo Scardoni  

Document Control

**Change History**

| Revision | Change Date | Description of changes |
| -- | -- | -- |
| v1.0 | 19/04/2020 | Initial release |


**Document Storage**
This document is stored in the project documentation's GitHub repository at: [https://github.com/Fr0stBob/2020-5Ai-team7-Corsi/tree/master/docs](https://github.com/Fr0stBob/2020-5Ai-team7-Corsi/tree/master/docs)

**Document Owner**
Convertino Riccardo is responsible for developing and maintaining this document.

## 1 Introduction
The Team 7 architecture document was designed to illustrate and identify the high-level architecture systems used to design and implement the Web Server application. The document contains an overview of the classification of the components used.

## 2 Components Classification
### 2.1 Presentation Layer
**Purpose:** To display forms, controls and images to the user to create a fluid and efficient user experience.

**Specific Nature:** The presentation layer will be in charge of displaying appropriate images and menus to the user. When a user clicks a menu on the GUI, the code corresponding to that event will be called. This layer will also be in charge of the spawning of appropriate threads. The need of spawning extra threads is due to the fact that the main thread of the app will be watching for event clicks, but we also need another thread constantly running to get the users current position.  

**Subcomponents:** Image Viewer **–** That it is used during the Walking Tour and during the Interactive Map mode of the application. Its responsibility is to display the appropriate image as determined by the Landmark held in the Current State.

### 2.1 Database Layer
**Purpose:** This layer is in charge of storing data in persistent storage.

**Specific Nature:** This layer will consist of SQL files. These together will be our database management system. These SQL files will store all the data needed for the application.

### 2.1 Data interaction Layer
**Purpose:** This level is used to pass data from the database to the application.

## 3 Design Goal

Our priorities for the design are:

- The project must minimize complexity and development effort.

- The project must take into account the development environment, which consists of 1 small team with complementary skills working in time and space. Ideally, the project should lead to 3-4 components of equal size and complexity. If the components have well-defined interfaces each team member can work independently by coding the interfaces of the other components. The concerns of each component should be narrowed down so that each member can specialize in a particular technology or skill.
