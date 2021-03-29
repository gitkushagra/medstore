# WELCOME TO MY MINI PROJECT

<a href="http://kushagraprofile.xyz">
         <img alt="Go to Profile" src="https://gitkushagra.github.io/medstore/Images/home.png" width="50" height="60"></a>

## ABOUT ME

I am Kushagra Singh studying in Galgotias College of engineering and technology, Greater Noida. This project is made, when I am in third semester in IT department.

## I AM ALSO ON

## Instagram
<a href="https://www.instagram.com/kushagra_shine">
         <img alt="Kushagra_on_Instagram" src="https://gitkushagra.github.io/medstore/Images/instalogo.png"></a>

## Linkedin
<a href="https://linkedin.com/in/kushagraprofile">
         <img alt="Kushagra_on_Linkedin" src="https://gitkushagra.github.io/medstore/Images/linklogo.png"></a>
                              

                                                  ACKNOWLEDGEMENT

I am very thankful to my parents and teachers SIR RANJEET KUMAR and SIR SANDEEP SAXENA for providing me this golden opportunity in mini project. This mini project helped me a lot in revision of my concepts of JAVA, MySQL and their connectivity. My deep gratitude also goes to MySQL online reference material, which is available for free and YouTube videos explainng the concepts. All credits of images used in each panels are obtained by Google Image Search and each image credit goes to their respective owners.

## PROJECT

### MEDICAL STORE MANAGEMENT SYSTEM

It is a management system of Medical Store, to maintain and manage record of medicines, employees and transactions related information.
It is a one stop intelligent solution of problems every medical store owners faces.
Moreover, its friendly GUI makes it more useful and time saving.
Administrator can manage everything, and each employee will have there own account, thus, making each employee work private from each other. However, ADMIN can observe everything.

Employees will only have rights for adding records, and there attendance is monitored within the application. Employees can reset the password either by their unique User Name or by directly contacting the administrator of the store.

Administrator credentials are given below, they can not be reset by the admin itself, if in case lost or forgotten. Admin needs to contact the engineer for the recovery.
User Name: admin
Password: root
For this project, Java language and MySQL databases are used.

```markdown
                                                      INDEX
                1. REQUIREMENTS
                2. BACKEND WORKING
                3. GUI
                4. DATABASE
                5. ER DIAGRAM AND DATABASE
                6. NOTE
 
```



## 1. i) HARDWARE REQUIREMENTS

```markdown
              A. Minimum CPU: Platinum III or equivalent.
              Recommended CPU: intel core i3 with 6th generation or equivalent.
              B. CPU Speed of at least 1 Giga Hertz.
              C. Minimum RAM: 256MB. Recommended RAM: 4 GB.
              D. Operating System: Windows XP. Recommended: Windows 8.1 or higher.
              E. Low end graphics for visuals of at least 64 MB.
              F. Disk space: 2GB is recommended.

```

## ii) SOFTWARE REQUIREMENTS

```markdown
              A. MySQL Database.
              B. MySQL J (Connector) for MySQL database and Java connectivity.
              C. Java Development Kit (JDK) needed to be installed for Java libraries.
              D. NetBeans IDE
              E. rs2xml.jar file for editing queries into GUI table from SQL databases.
              F. Inno Setup compiler to make executable (.exe) file.
```


## 2. BACKEND WORKING

```markdown
NetBeans IDE is used for designing GUI and Java coding. As MySQL queries are initiated in Java instructions,
MySQL connector J is used which export the extracted SQL query from Java to MySQL database.
For this purpose, MySQL JDBC (Java Database Connectivity) driver is added in libraries of Java project. 
The folder containing .jar file of the connector.
The rs2xml.jar file which is added to the libraries of Java project, makes it possible to view any 
changes in table in GUI.

```

## 3. GUI (GRAPHICAL USER INTERFACE)

I have used NetBeans IDE 8.2 to design each panels and coding. All images used in panels are obtained from Google Image search, all credits of images goes to their respective
owners.
### MENU OF MEDICAL STORE MANAGEMENT

```markdown
This is the main menu of the medical store software.
From “ATTENDANCE” tab, employees can give attendance on regular working days.
Then, they can proceed to their working and managing data.
From “ADMINISTRATOR LOGIN”, admin login panel opens, through which admins can 
manage everything throughout the application.
“EXIT” button closes the application.
```
![Menu](https://gitkushagra.github.io/medstore/Images/menu.png)



### SIGNIN/REGISTER

```markdown
This is the selection menu, where employee either proceed for login or register themselvese if in case new.
For going back to menu, MENU button will help.

```
![Signin/Register](https://gitkushagra.github.io/medstore/Images/signin.png)



### EMPLOYEE LOGIN PANEL

```markdown
This is the Employee Login Panel, through which employee can enter its unique 
username and password to continue for attendance.
However, if employee forgot/lost its password, forgot password button will help.
Exit button will close the application.

```
![employee_login](https://gitkushagra.github.io/medstore/Images/employeelogin.png)



### FORGOT PASSWORD PANEL

```markdown
This is the RESET PASSWORD window, where employee will enter its username, then check if it exists 
in the record, then enters a new strong password, once clicks on reset, the password is reset.
Password Generator tool is recommended to create the strong password. Back to login panel button will lead to 
Login wizard to enter  credentials.
```
![Forgot_Password](https://gitkushagra.github.io/medstore/Images/forgetpassword.png)



### PASSWORD GENRATOR TOOL

```markdown
This is the Password Generator tool, which can generate alphanumeric strong passwords ranging 
1 to 100 characters of length. However, employees are allowed up to 10 characters for the registration purpose.
Keeping either 5 or 6 characters length is recommended for employees.
Back to registration form and reset password buttons leads to respective panel.
```
![Password_Genrator](https://gitkushagra.github.io/medstore/Images/passgen.png)



### REGISTRATION PANEL

```markdown
This is the registration form, where employee select its unique username, enters 
desired password, and register themselves in the employee record.
Password Generator Tool is recommended. Login Panel button leads back to Login wizard.
```
![Employee_Register](https://gitkushagra.github.io/medstore/Images/register.png)



### ATTENDENCE PANEL

```markdown
This is the Attendance Panel, where employees can give there regular attendance.
Mark Present button will save there attendance as present in the given date.
Go to Dashboard button will lead to employee’s dashboard.
Menu button will open menu through which, at the end of the day, employee can exit the application.
```
![Attendence](https://gitkushagra.github.io/medstore/Images/attendence.png)



### EMPLOYEE PANEL

```markdown
This is the employee management panel, where it can—
* Add Patient Entry.
* Add Transaction Record.
* Add Medicine Record.
* Log out to the attendance panel, to exit the application.
```
![Employee_Panel](https://gitkushagra.github.io/medstore/Images/employeepanel.png)



### PATIENT ENTRY BY AN EMPLOYEE

```markdown
Through this panel, employee can add patient details to the record.
In this case, limited editing rights are given to the employee like it can not delete any patient details.
```
![Patient_Entry](https://gitkushagra.github.io/medstore/Images/patientbyemployee.png)



### EMPLOYEE TRANSACTION RECORD MANAGEMENT

```markdown
This is employee level transaction control panel, employee can only 
add the record of transaction with the customer.
In this case also, limited rights are given to the employee.
```
![Employee_Transaction](https://gitkushagra.github.io/medstore/Images/employeetransact.png)



### EMPLOYEE MEDICINE RECORD MANAGEMENT

```markdown
This is the employee medicine management console, if in case any employee attend the 
receiving of delivered  new medicine, then it can add to the record.
However, limited rights are given, like removing medicine data can not be done by an employee.
```
![Employee_Medicine](https://gitkushagra.github.io/medstore/Images/employeemed.png)



### ADMINISTRATOR LOGIN PANEL

```markdown
This is the  main admin login panel, its login credential is unique 
and given to the admin only.
Through this panel, administrator of the medical store can login to 
manage the records with administrative rights.
User Name and Password, as per provided with software, needs to 
be kept in a very safe place.
Once lost or forgot, admin cannot modify it, he/she needs 
to call an engineer for the recovery.
```
![Admin_login](https://gitkushagra.github.io/medstore/Images/adminlogin.png)



### ADMINISTRATIVE PANEL

```markdown
This is the administrative control panel, through which admin can—
* Manage employee records
* Manage medicine records
* Manage transaction records
* Any critical or important cases management
```
![Admin_Panel](https://gitkushagra.github.io/medstore/Images/adminpanel.png)



### ADMIN EMPLOYEES RECORD MANAGEMENT

```markdown
This is the employees record management console, through which admin can 
add any new employee, and provide it with its credentials.
If in any case, employee resigns from job admin can remove its data permanently.
Employees attendance can also be viewed.
```
![Employee_Record](https://kushagrasingh6.github.io/medstore/Images/adminemployee.png)



### ADMIN MEDICINE RECORD MANAGEMENT

```markdown
This is the medicine record management console with administrative rights.
Admin can add, delete and modify name of any medicine.
```
![Admin_Medicine](https://gitkushagra.github.io/medstore/Images/adminmed.png)



### ADMIN TRANSACTION RECORD MANAGEMENT

```markdown
This is the admin level transaction control panel.
Through which admin can not only add records but also can delete and modify it.
```
![Admin_Transaction](https://gitkushagra.github.io/medstore/Images/admintransact.png)



### ADMIN PATIENT RECORD MANAGEMENT

```markdown
This is admin level of Patient record management console 
with some admin rights of deleting the patient record. 
```
![Admin_Patient](https://gitkushagra.github.io/medstore/Images/adminpatient.png)



### CRITICAL/IMPORTANT CASES MANAGEMENT

```markdown
For any critical cases, like any patient is arriving after working 
hours or any personal cases etc., are managed by admin through this panel.
```
![Critical_Cases](https://gitkushagra.github.io/medstore/Images/critical.png)



## 4. DATABASES

```markdown
In this project, MySQL database management system is used,
in which a database is created under which required tuples(tables) are stored.
In this application “Admin” database is used. It contains six tables as shown.
```
![Databases](https://gitkushagra.github.io/medstore/Images/showdatabases.png)


![Tuples_list](https://gitkushagra.github.io/medstore/Images/showtables.png)

### NOTE: I HAVE ADDED ONE DUMMY RECORD USING INSERT COMMAND IN EACH TUPLE.



                                               ATTENDENCE RECORD
                                               
![Attendence_Record](https://gitkushagra.github.io/medstore/Images/attendencebase.png)


                                                 EMPLOYEE RECORD
                                               
![Attendence_Record](https://gitkushagra.github.io/medstore/Images/employeebase.png)


                                                 MEDICINE RECORD
                                               
![Attendence_Record](https://gitkushagra.github.io/medstore/Images/medicinebase.png)


                                                  PATIENT RECORD
                                               
![Patient_base](https://gitkushagra.github.io/medstore/Images/patientbase.png)


                                                 TRANSACTION RECORD
                                               
![Transaction_base](https://gitkushagra.github.io/medstore/Images/transactbase.png)


                                                 CRITICAL PATIENT RECORD
                                               
![Transaction_base](https://gitkushagra.github.io/medstore/Images/criticalbase.png)
                                               


## 5. ER DIAGRAM AND DATABASE

![ER_Diagram](https://gitkushagra.github.io/medstore/Images/erdiagram.jpg)


## 6. NOTE

![Note](https://gitkushagra.github.io/medstore/Images/note.png)

## DOWNLOAD ZIP FILE OF MY PROJECT [LOCKED]

[DOWNLOAD ZIP](https://www.mediafire.com/file/zeag38xhj7pzirl/MedStore.zip/file)

## DOWNLOAD My Prepared ppt (I exported it into pdf, so that it become uneditable)

[PPT Download](https://github.com/gitkushagra/medstore/raw/main/file/MEDICAL_STORE_MANAGEMENT_SYSTEM.pdf)

## DOWNLOAD executable (.exe) installer or MSI installer for Windows Machine of my project

NOTE: These are not using any GLOBAL database, so, most of the functions will not work and show database connectivity error, since localhost server is used.

[DOWNLOAD EXE INSTALLER](http://www.mediafire.com/file/p3tkkfjtqg63qav/Medical_Sore_Management-1.0.exe/file)

[DOWNLOAD MSI INSTALLER](http://www.mediafire.com/file/wkb7z6n9b9am4n6/Medical_Sore_Management-1.0.msi/file)


## DIFFERENCE BETWEEN EXE AND MSI INSTALLER

[EXE VS MSI](https://askanydifference.com/difference-between-msi-and-exe/)


                                            THANK YOU!
                                       ---KUSHAGRA SINGH---

