
# Name: Samuel NIYONSHUTI
# Student ID: 28329  
# Instructor: Eric Maniraguha 
# courses: Database development with PL/SQL  

## TASK1: create new pluggable database ( pdb  ) 
I used cmd to connect to my Oracle database using SQL*Plus.I logged in to Oracle Database as SYSDBA and created a new pluggable database following the required format.
![image alt](https://github.com/Sam925-pro/Creation-of-pluggable-database-samuel-niyonshuti/blob/main/Creation%20of%20pldb.png)        
**fig 1:** creating first pruggable database


## Task 2: Create and Delete a PDB
This task involved creating a PDB for the specific purpose of practicing the deletion process. 
First, I created the pluggable database named sa_to_delete_pdb_28329, following the 
specified format.

![image alt](https://github.com/Sam925-pro/Creation-of-pluggable-database-samuel-niyonshuti/blob/main/to-%20delete%20pldb.png)   
**fig 2:** creation of pruggable database sa_to_delete_pdb_28329

  ### Checking if pluggable database and delete a pdb works
![image alt](https://github.com/Sam925-pro/Creation-of-pluggable-database-samuel-niyonshuti/blob/main/show%20pdbs.png)
**fig 3:** checking if it is really created

![image alt](https://github.com/Sam925-pro/Creation-of-pluggable-database-samuel-niyonshuti/blob/main/drop.png)     
**fig 4:** closing and deletion of pluggable database



## Task 3: Oracle Enterprise Manager (OEM) Dashboard
I opened Oracle Enterprise Manager in my browser and logged in using the SYS account. The dashboard displayed my username and the list of databases clearly. I confirmed that the OEM connection was working and captured a screenshot showing the system dashboard and my account details.
![image alt](https://github.com/dariusmutabazi-commits/Pluggable-Database--Darius-MUTABAZI/blob/main/OEM.PNG)         
**fig 7:** Oracle Enterprise Manager dashboard

## Issues and Fixes
During the exercise, I encountered the error ORA-65005, which occurred because the FILE_NAME_CONVERT clause was missing the source and target file paths. I corrected it by including both paths in the statement. I also faced the error ORA-65025 while dropping the PDB, which happened because the PDB was still open. I solved this by closing the PDB first with the ALTER PLUGGABLE DATABASE CLOSE IMMEDIATE command before dropping it.
## Result and short summary
All required tasks were completed successfully. I created, opened, verified, and deleted pluggable databases without further errors. I also accessed Oracle Enterprise Manager and confirmed my account information on the dashboard. The entire setup worked correctly and met all given requirements.
