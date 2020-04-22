# DBMS
LAB PROGRAMS

1 Consider the following relations:
	    Student(snum:integer,sname:string,major:string,level:string,age:integer)
	    Class(cname:string,meets at:string,room:string,fid:integer)
	    Enrolled(snum:integer,cname:string)
      Faculty(fid:integer,fname:string,deptid:integer)
      The meaning of these relations is straightforward;for example,
	    enrolled has one record per student-class pair such that the student is enrolled in the class.
	    Level is a two chaaracter code with 4 different values(example:Junior:JR etc)
	    write the following queries in SQL.No duplicate should be printed in any of the answers.
(i).Find the names of all juniors(level=jr) who are enrolled in a class taught by prof.harshith    
(ii)Find the names of all classes that either meet in room R128 or have five or more students enrolled.
(iii).find the names of all students who are enrolled in two classes that meet at the same time.
(iv).find the names of faculty members who teach in every room in which some class is taught.
(v).find the names of faculty members for whom the combined enrollment of the courses that they tech is less than five.

2 The following relations keep track of airline flight information:
   flights( no:integer,from:string,to:string,distance:integer,departs:date,arrives:date,price:real)
   Aircraft(aid:integer,aname:string,cruisingrange:integer)
   Certified(eid:integer,aid:integer)
   Employees(eid:integer,ename:string,salary:integer)
   Note that the employees relation describes pilots and other kinds of employees as well; Every pilot is certified for some aircraft, and only pilots are certified to fly.
   Write each of the following queries in SQL
  (i). Find the names of aircraft such that all pilots ceritified to operate them have salaries more than 80,000.
  (ii) For each pilot who is certified for more than three aircrafts,find the eid and the maximum cruisingrange of the aircraft for which she or he is certified.
  (iii). Find the names of the pilots whose salary is less than the price of the cheapest route from bengaluru to frankfurt.
  (iv). For all aircraft with cruisingrange over 1000 Kms,find the name of the aircraft and the average salary of all pilots certified for this aircraft.
  (v). Find the names of pilots certified for some Boeing aircraft.
 (vi).  Find the aids of all aircraft that can be used on routes from bengaluru to New Delhi

3 Consider the following database of student enrollement in courses and books adopted for  each course .

STUDENT (regno :string , name : string , major : string , bdate : int)
COURSE (course# : int , cname : string , dept : string)
ENROLL ( regno : string , course#: int , sem : int , marks : int )
BOOK_ADAPTION ( course#: int , sem : int , book_isbn :int)
TEXT( book_isbn : int , book-title : string , publisher : string , author : string).

i)	Create the above tables by properly specifying the primary keys and the foreign key .
ii)	Enter atleast five tuples for each relation . 
iii)	Demonstrate how you add a new text book to the database and make this book be adopted by some department.
iv)	Produce a list of text books( include course # ,book_isbn,book-title) in the alphabetical order for courses offered by the cs department that use more than 2 books.
v)	List any department that has all its adopted books published by specific publisher.
vi)	Generation of suitable reports.
vii)	Create suitable front end for querying and display the results

4 . Consider the following relations for the details maintained by a book dealer.

AUTHOR (Author-id: int, Name: string, City: string, Country: string)
PUBLISHER (Publisher-id: int, Name: string, City: string, Country: string)
CATALOG (Book-id: int, title: string, author-id: int, Publisher-id: int, Category-id: int, Year: int, Price: int)
CATEGORY (Category-id: int, Description: string)
ORDER-DETAILS (Order-no : int, Book-id: int, Quantity: int)
i.	Create the above tables by properly specifying the primary keys and the foreign keys.
ii.	Enter at least five tuples for each relation.
iii.	Give the details of the authors who have 2 or more books in the catalog and the price of the books is greater than the average price of the books in the catalog and the year of publication is after 2000.
iv.	Find the author of the book which has maximum sales.
v.	Demonstrate how you increase the price of books published by a specific publisher by 10%.
vi.	Generation of suitable reports.
vii.	Create a suitable front end for querying and displaying the results.

5 Consider the following database for a banking enterprise

BRANCH (branch_name: string, branch_city: string, assets: real)
ACCOUNT (accno: int, branch_name: string, balance: real)
CUSTOMER (customer_name: string, customer_street: string, city:string)
DEPOSITOR (customer_name: string, accno: int)
LOAN (loan_number: int, branch_name: string, amount: real)
BORROWER (customer_name: string, loan_number: int)  
 
i)	Create the above tables by properly specifying the primary keys and the foreign keys.    
ii)	Enter atleast five tuples for each relation.
iii)	Find all the customers who atleast two accounts at the MAIN branch.
iv)	Find all the customers who have an account at all branches located in a specific city.
v)	Demonstrate how you delete all account tuples at every branch located in a specific city.
vi)	Generation of suitable reports.
vii)	Create suitable front end for querying and displaying the results.

