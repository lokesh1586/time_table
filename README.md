# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
<head>
<title> SLOT TIMETABLE </title>
</head>
<body>
    <center><img src="image.png" height="100" width="570"></center>
<br>
<table align="center" width="600" cellspacing="4" cellpadding="5" border="4" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - LOKESH.M(24900227)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">8-10</th>
<th bgcolor="yellow">10-12</th>
<th rowspan="7" bgcolor="yellow">L U N C H</th>
<th bgcolor="yellow">1-3</th>
</tr>
<tr align="center">
<th bgcolor="yellow">MONDAY</th>
<td >COMMUNICATIVE ENGLISH</td>
<td>ETHICAL HACKING</td>
<td>PTHON</td>
</tr>
<tr align="center">
<th bgcolor="yellow">TUESDAY</th>
<td rowspan="2">FREE SLOT</td>
<td> FUNDAMENTALS OF WEB </td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">WEDNESDAY</th>
<td>FUNDAMENTAL OF CRYPTOCURRENCY</td>
<td>MENTOR MEET</td>
</tr>
<tr align="center">
<th bgcolor="yellow">THURSDAY</th>
<td >UI & UX </td>
<td>SOFTWARE TESTING</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr align="center">
<th  bgcolor="yellow">FRIDAY</th>
<td> UI & UX</td>
<td> ETHICAL HACKING </td>
<td> PYTHON</td>
</tr>
</tr>
<tr align="center">
<th  bgcolor="yellow">SATRUDAY</th>
<td> FUNDAMENTAL OF CRYPTOCURRENCY</td>
<td> SOFTWARE TESTING</td>
<td> FUNDAMENTALS OF WEB</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th bgcolor="yellow">S. No.</th>
<th bgcolor="yellow">Subject Code</th>
<th bgcolor="yellow">Subject Name</th>
</tr>
<tr>
<td bgcolor="lightblue" align="center">1.</td>
<td bgcolor="lightblue" align="center">19AI414</td>
<td bgcolor="lightblue">Fundamenal of web application</td>
</tr>
<tr>
<td  bgcolor="lightblue"align="center">2.</td>
<td  bgcolor="lightblue" align="center">19AI304</td>
<td bgcolor="lightblue">Pyton programming</td>
</tr>
<tr>
<td bgcolor="lightblue" align="center">3.</td>
<td bgcolor="lightblue" align="center">19AI543</td>
<td bgcolor="lightblue"> Software testing</td>
</tr>
<tr>
<td bgcolor="lightblue" align="center">4.</td>
<td bgcolor="lightblue" align="center"> 19CS547 </td>
<td bgcolor="lightblue">Fundamentals of Cryptocurrency</td>
</tr>
<tr>
<td bgcolor="lightblue" align="center">5.</td>
<td bgcolor="lightblue" align="center">19CS549</td>
<td bgcolor="lightblue">UI and UX Design</td>
</tr>
<tr>
<td bgcolor="lightblue" align="center">6.</td>
<td bgcolor="lightblue" align="center"> 19EN101</td>
<td bgcolor="lightblue">Communicative English</td>
</tr>
<tr>
    <td bgcolor="lightblue" align="center">7.</td>
    <td bgcolor="lightblue" align="center"> 19CS417 </td>
    <td bgcolor="lightblue">Ethical Hacking Techniques</td>
    </tr>
</table>
</body>
</html>

```
# OUTPUT
![Screenshot 2025-04-14 135115](https://github.com/user-attachments/assets/ffc1f435-028c-4b9b-bae2-8c76e8fafaa5)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
