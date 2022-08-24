# Chatverse
The tourist will be  able to communicate with guides with the help of a discord-like
application which will be created using Django. The users can join a group relating
to their preferences and they can interact with other members of the group. Among
the number of guides hat we provide the users can communication with these
guides via this chat-box and select the one that they prefer. This way , the
tourists/users know what to expect from their guides, can suggest what they want
to do during their trips and can prepare accordingly.


## Chatbox using Django:
Step 1: Create virtualenv -- to create new isolated environments to isolates your
Python files on a per-project basis

Step 2: Create web pages using django templates
eg. {% include ‘navbar.html’ %} OR {% extend ‘main.html’ %}
This code helps to ‘include’ the content of one html to another or ‘extend’
to the content of one html to another.

Step 3: CRUD to create , read , update , delete (backend)
1. views.py -> create view i.e what user sees or what context are presented
on the web
2. urls.py -> create url for the created view (this url lead to the view)
3. update home page with the url


## Chatbox feature:
 -  the main home page have 3 segments for topics of the rooms present in the
	database, feeds which shows the rooms , and activities segment which
	shows the activities of all the user.
- 	only registered user can create a room of their choice and chat in any room on their feeds.
-	only the one user who created the respective room can update or delete
	them.
-	user can only delete their own messages. 
-	user can update their own profile.
