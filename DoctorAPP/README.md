# Doctor Appointment Management App using MVC Model in Java with Spring Boot

The Doctor Appointment Management App is a web application built using the Model-View-Controller (MVC) architectural pattern in Java with Spring Boot. It provides a platform for patients to book appointments with doctors and manage their medical appointments effectively.

## Prerequisites

Before running the application, ensure you have the following installed:

- Java Development Kit (JDK) 17
- Apache Maven
- MySQL database

## Technologies Used

- Java
- Spring Boot
- MySQL (as the database)

## Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/ahmedraza6377/docterApp.git

## Framework and Language
> * SpringBoot
> * Java-17

## Dataflow
> * Controllers
* controller classes in these classes i created all the api using sprinboot mapping these api response to endpoint these api connect with service classes for their busseness logic;
* AdminController.java
* AppointmentController.java
* DoctorController.java
* PatientController.java
> * Services
* Service classes in these classes I create all the method who provide all the business logic
> * utility
* hashingUtility -
PasswordEncrypter.java
* AdminService.java
* AppointmentService.java
* AuthenticationService.java
* DoctorService.java
* PatientService.java
* DoctorAppApplication.java
> * repository
* repository classes in these classes I connect with CrudRepository for doing crud Operation on entities
* IAdminRepo.java
* IAppointmentRepo.java
* IAuthTokenRepo.java
* IDoctorRepo.java
* IPatientRepo.java
> * Database Design
* I Used mysql DataBase

## DataStructure
* ArrayLits etc.


## Project Summary
> this is a simple doctor app in this application doctor can sign up sign in, patient can sign up sign in  and take appointments in this application i uesd authentication for user priavcy i used uuid for authentication
> I also used dependency like spring web,lombok,mysql,swagger, validation etc.


