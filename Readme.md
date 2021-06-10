# Spring JPA Auditing 
This project demonstrates the use of Spring Envers library to enable auditing for JPA ORMs.

In the context of ORM, database auditing means tracking and logging events related to persistent entities, or simply entity versioning. 

Inspired by SQL triggers, the events are insert, update and delete operations on entities.

The way entity auditing is setup in this project, the audit table (table suffixed with "_aud") will contain a history of changes made to entity records.




Steps to get started -

1. Use this SQL statement to create the database -
   
   CREATE DATABASE spring_envers_db CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;

2. Start the application use the runner class

3. Use the controller endpoints to add/update/get entities


