# Software Requirements Specification For Team 7
 **January 4, 2020 Version 1**
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

**Prepared By:**
Matteo Corsi


### Table of Contents
**1 INTRODUCTION** 4<br>
1.1 Overview<br>
1.2 Goals and Objectives<br>
1.3 Scope<br>
1.4 Definitions<br>

**2 GENERAL DESIGN CONSTRAINTS** 5<br>
2.1 Webserver Marconi Environment<br>
2.2 User Characteristics<br>
2.3 Mandated Constraints<br>

**3 NONFUNCTIONAL REQUIREMENTS** 5<br>
3.1 Operational Requirements<br>
3.2 Security Requirements<br>
3.3 Documentation and Training<br>
3.4 External Interface<br>
3.4.1 User Interface<br>
3.4.2 Software Interface<br>

**4 FUNCTIONAL REQUIREMENTS** 6<br>
4.1 Required Features<br>
4.1.1 Use Case 1<br>
4.1.2 Use Case 2<br>
<br>

**Revision History**
| Version | Date | Name | Description |
|--|--|--|--|
| 1 | 04/01/2020 | Matteo Corsi | Initial document |



## 1  Introduction
### 1.1 Overview 
The Webserver will be available to all ITI Marconi's students, teachers and student's parents.
The website will provide an easy access to all the services the school offers.

This document provides information on the requirements for the Webserver. Project goals, scope and definitions are given in the introduction.  Design constraints and application environment are described in the following section.

Project constraints will be included in separate documentation.  The Software Project Management Plan will give specifics on project budget and schedule.  A separate Test Plan document will address  test specifications and procedures.

### 1.2 Goals and Objectives

The main objective of this project is to allow students, teachers and student's parents an easy way to access all the services that the school offers.
The Webserver is expected to:
1. Provide a unique place where students, teachers and student's parents could access school's services.
2. Function in a simple and intuitive manner.

### 1.3 Scope
The Webserver will provide users to use all the facilities of the school in a single place. Users will be able to login to view private news and timetables.

### 1.4 Definitions

**Webserver Marconi** – the product that is being described here; the software system specified in this document.

**Project** – activities that will lead to the production of the Webserver.

**Client** – the person or organization for which this Webserver is being built.

**User** – the person or persons who will actually interact with the Webserver.

**Use case** – describes a goal-oriented interaction between the system and an actor. A use case may define several variants called scenarios that result in different paths through the use case and usually different outcomes.

**Scenario** – one path through a user case

**Actor** – user or other software system that receives value from a user case.

**Developer** – the person or organization developing the system, also sometimes called the supplier.

**Stakeholder** – anyone with an interest in the project and its outcomes. This includes clients, customers, users, developers, testers, managers and executives.

## 2 General Design Constraints

### 2.1 Webserver Marconi Environment

The Webserver will interface with an http server of our design. The server will interface with the school website and the timetable database.

### 2.2 User Characteristics

**Webserver Users**: ITI Marconi students, faculty or staff who could use a web browser. 

### 2.3 Mandated Constraints

The application will run on every updated web browser. 

## 3 Nonfunctional Requirements

### 3.1 Operational Requirements

Usability: 100% of users will not need to read the user manual to be able to use the Webserver.

### 3.2 Security Requirements

The Webserver has two features.  For the first feature, Use Case 1, Roo Bucks account security is provided by secure login using Campus credentials. Login information input will not be stored.
For the second feature, Use Case 2, no security is required and access to all other utilities is available to all users.

### 3.3 Documentation and Training

The Webserver will be delivered to users as a url without documentation or training.  A user guide and system documentation will be provided to project stakeholders.

### 3.4 External Interface

#### 3.4.1 User Interface

The user interface will be eye-catching and visually appealing. The Webserver will be make use of smooth animations to provide an appealing visualization.

The interface will be intuitive. No training will be provided and it is expected that 100% of users will be able to use the Webserver without any training.

#### 3.4.2 Software Interface

The http server will serve as an interface between the Webserver and ITI Marconi website .  It will enable interaction between the user, the remote website and database.

## 4 Functional Requirements

### 4.1 Required Features

#### 4.1.1 Use Case: 1

**Description: User Login / Check private news or timetable**

Actors: any user
Value = high
Cost = high

Basic Path

1. User open a web browser.
2. In the search bar user will write the Webserver url.
3. In the Webserver user will click on the icon on the top-right corner.
4. A menu will apear showing some general informations.
5. The user click the login button.
6. System prompts user to enter private serial number and password.
7. User enters correct private serial number and password and clicks Login.
8. System displays now also private news and Orario button.
9. User clicks Logoff.
10. System now don't show private news and timetable. 

Alternate Path

1. User open a web browser.
2. In the search bar user will write the Webserver url.
3. In the Webserver user will click on the icon on the top-right corner.
4. A menu will apear showing some general informations.
5. The user click the login button.
6. System prompts user to enter private serial number and password.
7. User enters incorrect private serial number and password and clicks Login.
8. System displays error message: "Invalid serial code and/or password. "
9. User may choose to login again, remaining on the public area or exit.

#### 4.1.2 Use Case: 2

**Description: Access public services**

Actors: any user
Value = high
Cost = high

Basic Path

1. User open a web browser.
2. In the search bar user will write the Webserver url.
3. User now could click on the desired service and access a separated website.
