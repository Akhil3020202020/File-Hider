# File Hider in MySQL Database

This simple Java application allows you to hide local files in a MySQL database. I created this project to securely store and retrieve files from a database using Java, MySQL, and email functionality.

## Prerequisites

Before you begin, ensure that you have the following installed:

1. **Java** (I used version 21)
2. **MySQL Server** (I used version 8.0.35)
3. **Apache Maven** for dependency management
4. **Google-generated app password** for sending emails (Not your regular Google account password)

## Maven Dependencies

The project uses the following Maven dependencies:

1. **mysql-connector-java** – for MySQL connectivity
2. **javax.mail** – for email functionality

Add these dependencies to your `pom.xml` file:

```xml
<dependencies>
    <!-- MySQL connector -->
    <dependency>
        <groupId>mysql</groupId>
        <artifactId>mysql-connector-java</artifactId>
        <version>8.0.33</version>
    </dependency>

    <!-- Java Mail API -->
    <dependency>
        <groupId>com.sun.mail</groupId>
        <artifactId>javax.mail</artifactId>
        <version>1.6.2</version>
    </dependency>
</dependencies>
