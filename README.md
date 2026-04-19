# ThessPoto

ThessPoto is a Java desktop application developed with NetBeans.  
The project focuses on managing beverage-related business operations through a graphical user interface.

## Features

- User login screen
- Main menu navigation
- Product catalog interface
- Stock / availability management
- Supply / procurement-related screens
- Java Swing-based graphical interface
- NetBeans project structure

## Technologies Used

- Java
- Java Swing
- NetBeans IDE
- MySQL / database connection

## Project Structure

```text
ThessPoto/
├── src/                  # Java source files and UI forms
├── images/               # Application images and icons
├── nbproject/            # NetBeans project configuration
├── build.xml             # Ant build file
├── manifest.mf           # Manifest file
└── README.md
```

## Main Screens / Classes

Some of the main project files include:

```text
eisodos.java          # Login screen
menu.java             # Main menu
katalogos.java        # Product catalog
diathesimotita.java   # Availability / stock screen
promithia.java        # Supplies / procurement screen
katopin.java          # Additional navigation or form screen
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/ThessPoto.git
```

2. Open the project in **NetBeans IDE**.

3. Make sure the required database is available locally.

4. Configure the database connection according to your local setup.

## Database Configuration

For security reasons, database credentials should **not** be uploaded to GitHub.

If the project uses a database connection file such as `dbconnect.java`, replace hardcoded credentials with your own local values or use environment variables.

Example:

```java
String url = "jdbc:mysql://localhost:3306/YOUR_DATABASE";
String user = "YOUR_USERNAME";
String password = "YOUR_PASSWORD";
```

Do **not** commit real usernames, passwords, or database URLs containing sensitive information.

## How to Run

### Option 1: Run with NetBeans

1. Open NetBeans.
2. Select **File > Open Project**.
3. Choose the `ThessPoto` folder.
4. Right-click the project.
5. Select **Run**.

### Option 2: Build with Ant

If Apache Ant is available, the project can be built using:

```bash
ant clean build
```

## Git Ignore Recommendation

The following files and folders should not be committed:

```gitignore
/build/
/dist/
nbproject/private/
*.class
*.jar
*.log
.DS_Store
Thumbs.db
```

## Notes

This project was created as a Java desktop application using NetBeans.  
The repository should contain only the source code, images, forms, and configuration files required to rebuild and run the application.

Compiled files, local IDE settings, and private database credentials should remain outside the repository.

## Author

Developed by Vasilis Mouratidis.
