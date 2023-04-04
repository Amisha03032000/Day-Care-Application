# DayCare Project

> GitHub repo for NEU CSYE6200 'DayCare Application' Group Project

1. Enroll students: capture data
    – Student name, age
    – Parents name, address, phone
    – GUI and CSV file input
2. Track annual student registration renewal
3. Track student immunization anniversaries
    – Immunization records from CSV file
4. Assign students to Teachers according to state regulations
5. Assign student/teacher Groups to classrooms according to state regulations
6. Track annual employee review


## Team members
- Amisha Gokhale- 002743313
- Ishita Janwale- 002743313
- Vaishnavi Bhoite- 002776319
- Cyrus Dbritto- 002922815

## Requirements
- NetBeans 12.0 
- JDK 8 with `JAVA_HOME` pointing to it
- A database viewer like [SQLite Browser](https://sqlitebrowser.org/dl/) or [Database Panel](https://www.jetbrains.com/help/idea/database-tool-window.html) in IDEA Ultimate (optional)

## Conventions
- Git message: [conventional commits](https://www.conventionalcommits.org/zh-hans/v1.0.0-beta.4/)
- Working branches: `dev/<your name>`

## Editing Guide

For NetBeans users:

- In `Tools/Plugins`, make sure `Gradle`, `Groovy and Gradle`, `Java SE`, and `Java` are all installed
- If you want to add swingx components to your GUI Designer:
    - Download `swingx.jar` from [Maven Repository](https://mvnrepository.com/artifact/org.swinglabs.swingx/swingx-all/1.6.5-1) (click jar button to download)
    - In `Tools/Palette/Swing AWT Components`, choose "Add from JAR..."
    - Select the `swing.jar` you just downloaded, and select all beans to import.
    - Now swingx components are visible on your GUI Designer palette.

## CI

```
// Mac users only
sudo xattr -rd com.apple.quarantine DayCare.app
```