# RFID-Based-Attendance-System
This is an attempt to develop an RFID Based Attendance System to overcome the manual attendance system and automate the process of attendance in schools and colleges.

The basic idea of the system is that the students will come in and flash their id card in front of the reader. Their attendance will be recorded in a temporary database.

Attendance will be granted in a particular timeframe,  example: Let's say the lecture starts at 8:30 in the morning, then the students will be given attendance only between 8:25 am and 8:40 am.

Every teacher will have a database exclusively for him or her on which the attendance record per lecture will be displayed. Everytime a teacher conducts the lecture, all he/she has to do is flash the card given to the teacher in front of the reader and the attendance logged in the temporary database will be transferred to the teacher's exclusive database.

Note: Proxy detection is the problem I am currently struggling with.

Details: 
Hardware used-
MFRC522 RFID card reader
Raspberry Pi
Nokia 5110 LCD Display
LEDs for indication

Software used-
Python to program the Raspberry Pi
SQL to maintain the database
Django to develop a website
