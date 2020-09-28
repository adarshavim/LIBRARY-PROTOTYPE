# LIBRARY-PROTOTYPE
It is protoype  of application for managing details of authors, publishers and books at library.<br>

This application uses MySQL database;<br>
There are total three table used in this prototype which is as follows:<br><br><br>
![](BookLib_Screenshot/tables.png)
<br>
1)Two master(Data is rarely change) tables:<br>
 a)Author Detail<br>
 ![](BookLib_Screenshot/auth_table.png)
 <br>
 b)Publisher Table<br>
 ![](BookLib_Screenshot/publish_table.png)
 <br><br><br>
 2)And one Transaction table Book_det for addition and deletion of book.<br>
 ![](BookLib_Screenshot/Books_table.png)
 <br>
 Java GUI interface is used for managing all data in database;
 <br>
 ![](BookLib_Screenshot/dashboard.png)
 <br>
 ![](BookLib_Screenshot/authorlist.png)
 <br>
 ![](BookLib_Screenshot/publisherlist.png)
 <br>
 ![](BookLib_Screenshot/booklist.png)
 <br>
 How to run on local system.<br>
 Prerequisites are:<br>
 1)MySql server<br>
 2)MySQL connector.jar<br>
 3)JDK <br>
 Steps to run on local system:<br>
 1)Clone this repositry on your system.<br>
 2)Paste the mysql connector.jar file in this repository.<br>
 3)Run the jar application in build tool.
