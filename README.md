# Attendance Management System (HAZRI)

A Java-based attendance management project built with Java Servlets, JSP/JSTL, Spring JDBC, MySQL, and a Java Swing desktop client.

## Project contents

The original project archive is available as `AttendanceSystem.zip` in this repository. It contains the Maven `pom.xml`, Java servlet classes, JSP views, CSS, SQL database setup script, and Swing client.

## Local setup

1. Install JDK 8 or a compatible JDK, Maven, MySQL (or XAMPP), and Apache Tomcat 8.5/9.
2. Create the database by importing `database/attendance_db.sql` in phpMyAdmin or running it with MySQL.
3. Open the project in NetBeans or import it as a Maven project.
4. Build the WAR with `mvn clean package` and deploy it to Tomcat.
5. Open `http://localhost:8080/AttendanceManagementSystem/`.

## Demo login

- Username: `teacher1`
- Password: `teacher123`

These are sample credentials included in the SQL seed data for local demonstration only. Change them before using the application beyond a classroom demo.

## Database configuration

The current `Dao.java` uses the local XAMPP/MySQL default connection (`localhost:3306`, database `attendance_db`, user `root`, empty password). Update this configuration in `Dao.java` to match your local MySQL setup. Do not use default credentials in a production environment.

## Technology stack

- Java 8
- Java Servlets and JSP/JSTL
- Spring JDBC (`JdbcTemplate`)
- MySQL
- Maven WAR packaging
- Java Swing

## Note

This repository is a student project/demo. Review authentication, database configuration, and deployment security before production use.
