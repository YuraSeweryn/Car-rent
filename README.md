# Car-Rent

This project has been developed based on Multi-Layered Architecture. 
Front-End part is coded with Angular, Back-End part is coded with C#. 
MSSQL Local Database is used for the database. 

<h2>
Database
</h2>
MSSQL Localdb was used for database in the project. 
<br>

Create Database
Then execute the table creation query on this database. 
Thus the tables required for the project will be created. 
<br>

<h2>
Back-End
</h2>
C# was used in the back-end part of the project. Development was made on the basis of multi-layered architecture. I want to give information about what layers do; <br>
<b>1-Entities Layer:</b> It is where the classes of objects to be used throughout the program are defined. 
<br>
<b>2-Data Access Layer:</b> It is the layer on which database connections and operations are made.
<br>
<b>3-Business Layer:</b> It is the layer where business rules are defined and controlled.
<br>
<b>4-Core Layer:</b> It is the part where extensions and tools to be used in common in all layers are coded.
<br>
<b>5-Presentation Layer:</b> It is the layer that appears to the user.
<br>
<b>6-Service Layer (Web API):</b> It is the part where the services that enable the Front-End part and other platforms to communicate with the program and perform operations are written. 
<br>

<br>
1- First, you need to install the Node modules used in the project. <br>
```
npm install
```
2- Finally, we will open a new terminal and run the project on localhost. <br>
```
ng serve
```
