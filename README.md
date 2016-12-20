# 5imalone

Topic : Create a bulletin board using Web applications

Member : Song Hyeon Soo(2016003618)

Language : JAVA Script and HTML5 and SQL

Final goal : Create a printable bulletin board.

Predictive Function :

1.Add login function.

2.Add the ability to store written articles

3.Creating multiple bulletin boards

4.Add modified, erase functionality

5.Keep the notice in a special format.

6.If you write a lot, you add extra features (later in mind).

7.Inability to infringe on Admin credentials


Real Function : 

1. Add list

2. Add Write Function

3. Add Viewing Function

4. Add Delete Function

5. Add Modify Function

6. Make Database


-------------------------
Function 
-------------------------
list.jsp

This is the starting point of all functions. This shows a list of articles.
Tap the title of the article to view the text.(This is connected to the view function.)
After all the functions have been completed, they come back here. 
Stores information by connecting to a data base.


write.jsp

This function is writing. 
You can store and save titles, names, passwords, and content.

write_ok.jsp

Associates the information stored in write.jsp with the database.
This confirms whether you store the article.

view.jsp

Show the information of the stored articles. 
The database displays numbers, views, names, days, titles, content, and content with this function.
Links with Reply, List, Modify, and Delete functions.

delete.jsp

It is the ability to delete article.
You must use the password entered earlier.

delete_ok.jsp

Delete information in the database.
If the password is wrong, deny it.

modify.jsp

You can correct your writing with this function.

modify_ok.jsp

Modify the information in the database. It's connected to an modify.jsp.

reply.jsp
reply_ok.jsp

It was originally a function to reply. But there was an error. 
I can't fix myself with my ability. So I give up.

-------------------------
Used Programs
-------------------------

Eclipse IDE Java EE Developers

Tomcat v7.0.

Microsoft Access 2010


-------------------------
License
-------------------------
GPL 3.0

