# Attendance Management System (HAZRI)

A Java-based attendance management project built with Java Servlets, JSP/JSTL, Spring JDBC, MySQL, and a Java Swing desktop client.

## Technology stack

- Java 8
- Java Servlets and JSP/JSTL
- Spring JDBC (`JdbcTemplate`)
- MySQL
- Maven WAR packaging
- Java Swing

## Project source

The project archive was provided for this repository setup. The source files have **not yet been uploaded** to this repository; this initial commit contains the project overview only. The repository will be complete once the source files and database script are added.

## Local setup (based on the supplied project instructions)

1. Install JDK 8 or a compatible JDK, Maven, MySQL (or XAMPP), and Apache Tomcat 8.5/9.
2. Import `database/attendance_db.sql` into MySQL/phpMyAdmin.
3. Open the Maven project in NetBeans or another Java IDE.
4. Build the WAR with `mvn clean package` and deploy it to Tomcat.
5. Open `http://localhost:8080/AttendanceManagementSystem/`.

## Demo credentials in the supplied SQL seed data

- Username: `teacher1`
- Password: `teacher123`

These are demonstration credentials only. Change them before any deployment beyond a local classroom demo.

## Database configuration

The supplied `Dao.java` uses the local XAMPP/MySQL defaults (`localhost:3306`, database `attendance_db`, user `root`, empty password). Update the connection settings to match your local environment. Do not use default credentials in production.

## Note

This is a student project/demo. Review authentication, database configuration, and deployment security before production use.
