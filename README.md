# Ex03 Time Table
## Date:15.04.2024

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
```
<!DOCTYPE html>
<html>
    <head>
        <title>Timetable</title>
    </head>
    <body>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE -   CHANDRU M(212222100009)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">8-10</th>
<th bgcolor="yellow">10-12</th>
<th bgcolor="yellow">12-1</th>
<th bgcolor="yellow">1-3</th>
<th bgcolor="yellow">3-5</th>
</tr>

<tr align="center">
<th bgcolor="yellow">Monday</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">TEC ENG</th>
<th bgcolor="cyan" rowspan="5" align="center">LUNCH BREAK</th>
<th bgcolor="cyan">CREATIVE SKILLS</th>
<th bgcolor="cyan">DBMS</th>
</tr>

<tr align="center">
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">DBMS</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">PROBABILITY</th>
<th bgcolor="cyan">FUN C</th>
<th bgcolor="cyan">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="yellow">Thrusday</th>
<th bgcolor="cyan">STATISTICS</th>
<th bgcolor="cyan">PROBABBILITY</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">FREE SLOT</th>
</tr>

<tr align="center">
<th bgcolor="yellow">Friday</th>
<th bgcolor="cyan">STATISTICS</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">TEC ENG</th>
<th bgcolor="cyan">FREE SLOT</th>
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
<td align="center">19EN102</td>
<td>Technical English (TEC ENG)</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19EY702</td>
<td>CREATIVE SKILLS FOR COMMUNICATION (CREATIVE SKILLS)</td>
</tr>

<tr>
<td align="center">4.</td>
<td align="center">19CS404</td>
<td>Data Base Management System(DBMS) </td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical Methods(STATISTICS)</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19MA222</td>
<td>Probability and Queueing Models(PROBABILITY)</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C Programming(FUN C)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![slot](https://github.com/CHANDRUMANIKANDAN/slot/assets/118644502/3cb2c677-d185-46b0-8904-9cb34124282d)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
