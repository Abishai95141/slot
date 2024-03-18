# Ex03 Time Table
## Date:

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
```<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - ABISHAI K C (212223240002)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td colspan="1" align="center">PHY</td>
<td>Transforms</td>
<td>WEB</td>
<td>PHY</td>
<td>Stats</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>Free Slot</td>
<td> WEB </td>
<td>DL</td>
<td>Transforms</td>
<td>CS</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>WEB</td>
<td>FREE SLOT</td>
<td>DE</td>
<td>Statistics</td>
<td>Free Slot</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="5" align="center">FREE SLOT</td>
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
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI413</td>
<td>Deep Learning and its Appication</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH214</td>
<td>Physics for Quantum Computing(PHY)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA219</td>
<td>Transforms and its Applications</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical Methods</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY702</td>
<td>Creative Skills</td>
</tr>
<tr>
    <td align="center">7.</td>
    <td align="center">19EE404</td>
    <td>Digital Electronics(DE)</td>
    </tr>
</table>
</body>
</html>
```

## OUTPUT
![timetable](https://github.com/Abishai95141/slot/assets/139335314/44015e3b-574d-456d-9e05-4572742ca220)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
