# DBMS Notes - Last Minute Revision ✅
Here we have last minute revision notes of DBMS. These questions will familiarize you with the most important DBMS concepts and help you ace your job interviews 🙌

## Most Asked DBMS Interview Questions
![image](https://github.com/Shubham-Bhoite/LastMinuteRevision-DBMS/assets/117765637/14d1dd0a-3a18-4e24-9e21-30b812e9b9a0)

## 1) What is DBMS?
A DBMS is software that manages databases, providing an interface to store, retrieve, and manipulate data efficiently and securely.

## 2) What is a Database?
A Database is an organized, consistent, and logical collection of data that can easily be updated, accessed, and managed. Database mostly contains sets of tables or objects which consist of records and fields.

## 3) Explain the difference between a database and a DBMS?
A database is a collection of related data, while a DBMS is software used to manage, store, and retrieve data efficiently from the database.

## 4) Advantages of DBMS over File Systems?
- ### Data Redundancy and Inconsistency:

Redundancy means repeating the data in a system. In a normal file system, there is a high chance that there can be various files of the same data used by different users for specific purposes. If any user changes the data in its files, then the changes are not reflected in all files. This creates inconsistency in the data, and it may lead to the failure of the system. But in the DBMS, there is only one repository of data, and multiple users can use it. If any user changes the data, then it is reflected to each user as they are using the same repository.
- ### Data Sharing:

In the normal file system, data sharing is too difficult because file sharing is a complex task. In DBMS, all the data is centralized, so data sharing is a very easy task.
- ### Data Concurrency:

When more than one user accesses the database simultaneously, then it is called concurrency. In a file system, when multiple users are using the files at the same time, then there may be a chance of anomalies in the data due to changes, and it does not provide any method to detect anomalies. But in DBMS, we have a locking system to detect the anomalies so we can protect the data.
- ### Data Searching:

To search the data in a file system, we have to write a specific program and run it. In DBMS, we have query languages by which we can write small queries to get the data we want from the database. We can use various query languages, like MySQL, Oracle, etc., for a database to search and retrieve the data.
- ### Data Integrity:

When we insert new data into the database, we require some specific constraints on the data like integer or not null, etc. The file system does not provide any system to check the constraints, whereas DBMS has the functionality to check the constraints on the data, and it allows user defined data types.

## 5) What is the different languages present in DBMS?
-  DDL(Data Definition Language): It contains commands which are required to define the database. \ E.g., CREATE, ALTER, DROP, TRUNCATE, RENAME, etc.
-  DML(Data Manipulation Language): It contains commands which are required to manipulate the data present in the database.
  E.g., SELECT, UPDATE, INSERT, DELETE, etc.
- DCL(Data Control Language): It contains commands which are required to deal with the user permissions and controls of the database system.
E.g., GRANT and REVOKE.
- TCL(Transaction Control Language): It contains commands which are required to deal with the transaction of the database.
E.g., COMMIT, ROLLBACK, and SAVEPOINT.

## 6) Difference between the DELETE and TRUNCATE command in a DBMS?
-  DELETE Command:
  1) It removes rows from a table one by one with transaction logging
  2) It can be rolled back if required.

-  TRUNCATE Command:
  1) It removes all rows at once without transaction logging.
  2) It can't be rolled back.

## 7) ACID properties in DBMS?
![image](https://github.com/Shubham-Bhoite/LastMinuteRevision-DBMS/assets/117765637/ede675c9-9c27-4a43-b6dd-821e5b0e9900)

ACID stands for Atomicity, Consistency, Isolation, and Durability in a DBMS these are those properties that ensure a safe and secure way of sharing data among multiple users.
-  Atomicity: This property reflects the concept of either executing the whole query or executing nothing at all, which implies that if an update occurs in a database then that update should either be reflected in the whole database or should not be reflected at all.
-  Consistency: This property ensures that the data remains consistent before and after a transaction in a database.
-  Isolation: This property ensures that each transaction is occurring independently of the others. This implies that the state of an ongoing transaction doesn’t affect the state of another ongoing transaction.
-  Durability: This property ensures that the data is not lost in cases of a system failure or restart and is present in the same state as it was before the system failure or restart.

## 8) What is meant by Normalization and Denormalization?
![image](https://github.com/Shubham-Bhoite/LastMinuteRevision-DBMS/assets/117765637/51a5ef90-0c29-4576-8334-62fc0d8d823b)

-  Normalization is a process of reducing redundancy by organizing the data into multiple tables. Normalization leads to better usage of disk spaces and makes it easier to maintain the integrity of the database.
-  Denormalization is the reverse process of normalization as it combines the tables which have been normalized into a single table so that data retrieval becomes faster. JOIN operation allows us to create a denormalized form of the data by reversing the normalization.


