# Meeting Scheduler Application

This JAVA based application support users to login, add,delete, or modify Customers and Appointments.
Furthermore , users can view related  reports and developed  from the Appointment and Customer data.
The application connects to a remote MySQL database in the application  backend.

## Getting Started

This software solutuon  features a full GUI written withJavaFX. Improvements to this app could include a
GUI layed out in a relative, rather than absolute fashion.To query Appointment and Customer information, the
app connects to a MySQL database using the JDBC
protocol.



### Objectives

**Frontend**
- Accepts username and password and provides an appropriate error message
- Determines the user’s location (i.e., ZoneId) and displays it in a label on the log-in form
- Displays the log-in form in English or French based on the user’s computer language setting to translate all the text, labels, buttons, and errors on the form.
- Automatically translates error control messages into English or French based on the user’s computer language setting


**Backend**
- Customer records and appointments can be added, updated, and deleted.
- When adding and updating a customer, text fields are used to collect the following data: customer name, address,
  postal code, and phone number.
- DCountry and first-level division data is prepopulated in separate combo boxes or lists in the user interface for the user to choose.
  The first-level list should be filtered by the user’s selection of a country (e.g., when choosing U.S., filter so it only shows states)
- When a customer record is deleted, a custom message should display in the user interface.




## Application info
- **Author Travis Wu** 
- **Application Date 10/1/2023**
- **Application Version 1.0.3** 
- **JDK version 17.0.1**
- **JDBC connector version 8.1.23**
- **InteliJ idea version IntelliJ Community 2020.01**


	
	

### Prerequisites

Requirements for the software and other tools to build
- [WGU STUDENT PORTRAL](https://tasks.wgu.edu/student/010408706/course/26280010/task/3276/overview)
- [INTELIJ IDEA ](https://www.jetbrains.com/idea/)
- [MYSQL  ](https://www.mysql.com/)


### Output

- Sample output of the executable  file

  ![image](https://github.com/ShalithaJayamal/ReactNodeMongoConnection/blob/master/x1.)

### Headings Used

    - package com.example.demo6.controller;

    - import com.example.demo6.model.User;
    - import javafx.fxml.FXML
    - import javafx.scene.control.Button;
    - import javafx.scene.control.Label;
    - import javafx.scene.control.TextField;

    - import java.io.File;
    - import java.io.FileWriter;
    - import java.io.IOException;
    - import java.sql.SQLException;
    - import java.time.ZoneId;
    - import java.time.ZonedDateTime;
    - import java.util.Locale;

    gcc sender.cpp -o sender.out
    gcc reciever.cpp -o reciever.out
    ./sender.out
    ./reciever.out


## References

  - https://my.wgu.edu/courses/course/26280010
  - https://www.reddit.com/r/WGU/comments/lv6773/c195_software_ii_advanced_java_passed_in_12_days/
  - http://codingheartily.blogspot.com/2016/06/how-i-completed-my-entire-wgu-software.html

