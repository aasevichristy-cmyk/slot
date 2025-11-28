# Ex03 Time Table
## Date:28.11.25
## refrence number:25014916

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
~~~~
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="#f5426c">
<caption><b>SLOT TIME TABLE - Anisha (25014916)</b></caption>
<tr align="center">
<th bgcolor="#42cef5">Day/Time</th>
<th bgcolor="#42cef5">Monday</th>
<th bgcolor="#42cef5">Tuesday</th>
<th bgcolor="#42cef5">Wednesday</th>
<th bgcolor="#42cef5">Thursday</th>
<th bgcolor="#42cef5">Friday</th>
</tr>
<tr align="center">
<th bgcolor="#42cef5">8-10</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="#42cef5">10-12</th>
<td>FREE SLOT</td>
<td>PYTHON</td>
<td>WEB APPLICATION</td>
<td>WEB APPLICATION</td>
<td>WEB APPLICATION</td>
</tr>
<tr>
<th bgcolor="#42cef5">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="#42cef5">1-3</th>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="#42cef5">3-5</th>
<td>FREE SLOT</td>
<td>PYTHON</td>
<td>PYTHON</td>
<td>PYTHON</td>
<td>WEB APPLICATION </td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI301</td>
<td>PYTHON</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>WEB APPLICATION(FWAD)</td>
</tr>
~~~~

## OUTPUT
![WhatsApp Image 2025-11-28 at 21 11 34_8c2abcde](https://github.com/user-attachments/assets/935661eb-77bf-4abd-bf1d-47df412e4f5f)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
