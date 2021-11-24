# Requirements
## Introduction
Library management systems provides an online interface to allow visitors to view or reserve library resources. Now a days there are so many ideas and views regarding each topic that are being penned down proportionately number of authors and so are books increasing. Keeping track of these numerous books ,retrieval and submission back, after borrowing manually can prove to be very hectic. Hence this software to keep track of all the details and retrieve any data in a jiffy.

## Research
Day by day topics, books, and readers all are increasing. All the details are being stored. In small libraries in manual registers and in huge ones using a computer system. 
Largest library is in London, United Kingdom.
The main objective of the Library Management system is discipline of the planning, organizing and managing the library tasks . Library Management is entering the records of new book and retrieving the details of book available in the library.

## Benefits
1. Simple & Easy to Use
2. Increased Library Engagement
3. Efficient Cloud Data Management
4. Highly Secure, Scalable & Reliable
5. Mobile Access
6. Dynamic Reports
7. Fully Customizable
8. Cost-effective

## Cost And Features with time
* COST – more features more more cost
* FEATURES
   * Add books
   * Search books
   * View books
   * Delete books
   * Update Credentials

## Defining Our System
Libray Management System is where the manager(The Librarian) can login to system by providing username and password, 
add books by providing details like *Book ID, Book name, Author's Name, Student who Issued, Date Issued, Return date
delete book by providing book id, search book by its name, display/view all books and update username and password.

### Explanation
* Library Management System have few inbuilt features like:
    * Add book
    * Delete book
    * Search a book
    * View Book
    * Update Username and Password


## SWOT ANALYSIS
![SWOT Analysis](https://github.com/Diptiman1999/LTTS_MiniProject_C/blob/master/1_Requirements/swot.png)

# 4W&#39;s and 1&#39;H

## Who:
Schools, Colleges and Universities have started using this library management system.
## What:
Able to manage books efficiently and effectively.
## When:
Earlier library managers used to store books informations in registers. But with new technology it will save time aswell as efforts.
## Where:
This system is used all over the world.
## How:
This system will help to store books information effectively search,delete them efficiently.


# Detail requirements
## High Level Requirements: 
User here refers to Librarian.

| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR01 | User shall be able to login to system | Techincal | Implemented |
| HR02 | User shall be able to add new book | Techincal | Implemented | 
| HR03 | User shall be able to display books | Techincal | Implemented |
| HR04 | User shall be able to delete book | Techincal | Implemented |
| HR05 | User shall be able to search book | Techincal | Implemented |
| HR06 | User shall be able to update credentials | Techincal | Implemented |
| HR07 | Data should not be lost in case of failure | Scenario | FUTURE |
| HR08 | Data should always be stored when closing the system | Technical | Implemented |


##  Low level Requirements:
| ID | Description | HLR ID | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
| LR01 | User shall only be able to login to system by providing username and password | HR01 | Implemented |
| LR02 | If login is successfull then the file where data will be stored should be checked for existence, if YES then it will append to file otherwise it will create a new file | HR01 | Implemented |
| LR03 | User shall be able to add book by providing details like id,name of the book, author's name and date when added | HR02 | Implemented |
| LR04 | Return date is calculated by adding 30 days to issued date and store it in return date variable | HR02 | Implemented |
| LR05 | User shall be able display all book details like id,name,author and date added | HR03 | Implemented |
| LR06 | User need to search by id for the book to be deleted, if no such book name is available then "Book doen't exist" Message should be displayed | HR04 | Implemented |
| LR07 | User need to search by name for book details, if no such book is available then "Book doen't exist" Message should be displayed | HR05 | Implemented |
| LR08 | User need to provide new username and password to update the credentials  | HR06 | Implemented |
| LR09 | User shall be able to save book details to the files, if file already exists then it should append to file and should not overwrite it and if file does not exists then it should create a new file | HR02, HR03, HR04, HR05,HR06 | Implemented |
| LR010 | If opening the file fails, then the system shloud prompt the message "File not exist" and should not end the program execution | HR02, HR03, HR04, HR05,HR06 | Implemented |
| LR011 | When user exit the system, file should be automatically saved and "Thank You" message should be displayed | HR08 | Implemented |


