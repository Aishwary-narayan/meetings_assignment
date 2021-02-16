**meetings_assignment**


**Apis:**

1. Create meeting:
   POST : meetings
   BODY:  title, participants, startTime, endTime 
   Response: { meetings: \<details\> }
  
2. Get meeting by id:
   GET : /meeting/:<meeting_id>
   Response: { meetings: \<details\> }
  
3. Get all meetings between a given time interval
   GET: /meetings
   params: startTime, endTime ,page(optional)
   
   
**.env configuration keys needed:**
 
PORT=
DBUSER=\<your db username\>

DBHOST=\<db host\>

DBNAME=\<db name\>

DBPASS=\<db password\>

DBPORT=\<db port\>

DATEFORMAT='YYYY-DD-MM'  //add date format that will be sent in apis for start and end time
  
**Steps to run:**

1. npm i

2. node app.js
  
  
