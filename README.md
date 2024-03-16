# Ex03 Time Table
## Date:15.03.2024

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
```<html>
    <head>
        <title>My Time Table</title>
    </head>
    <body>
        <img src="/static/logo.png" height="100" width="500">
    </body>
<br> 
<br> 
<body align="center">
<strong>
SLOT TIME TABLE-MERCY A (23012506)
</strong>
</body>
<table align="center" border="4" cellspacing="4" cellpadding="7" height="70" width="600" bgcolor="#98FB98">
<tr align="center"  bgcolor="73C2FB">
<th>Day/Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
<th>Saturday</th>
</tr>
<tr align="center" bgcolor="#FF0090">
<td  bgcolor="73C2FB"><strong>8-10</stron></td>
<td colspan="2" align="center">FREE</td>
<td>AC</td>
<td>JAPANESE</td>
<td>WEB</td>
<td>FREE</td>
</tr>

<tr align="center" bgcolor="#FF0090">
<td bgcolor="73C2FB"><strong>10-12</strong></td>
<td colspan="4" align="center">FREE</td>
<td>EDM</td>
<td>PMC</td>
</tr>

<tr align="center" bgcolor="#FF0090">
<td bgcolor="73C2FB"><strong>12-1</strong></td>
<td colspan="6">LUNCH</td>
</tr>

<tr align="center" bgcolor="#FF0090">
<td bgcolor="73C2FB"><strong>1-3</strong></td>
<td>FREE</td>
<td>WEB</td>
<td>FREE</td>
<td>WEB</td>
<td>FREE</td>
<td>JAPANESE</td>
</tr>

<tr align="center" bgcolor="#FF0090">
<td bgcolor="73C2FB"><strong>3-5</strong></td>
<td>FREE</td>
<td>PMC</td>
<td>JAPANESE</td>
<td>EDM</td>
<td>FREE</td>
<td>AC</td>
</tr>

<tr align="center" bgcolor="#FF0090">
<td bgcolor="73C2FB"><strong>5-7</strong></td>
<td>FREE</td>
<td colspan="4">PYTHON</td>
<td>FREE</td>
</tr>
</table>

<br>

<table align="center" border="4" cellspacing="4" cellpadding="7" height="70" width="600">
  <tr>
   <th>S.No.</th>
   <th>Subject Code</th>
   <th>Subject Name</th>
  </tr>
  <tr>
  <td>1.</td>
  <td>19AI414</td>
  <td>Fundamentals of Web Application Development(WEB)</td>
  </tr>
  <tr>
  <td>2.</td>
  <td>19AI302</td>
  <td>Engineering Design and Modelling(EDM)</td>
  </tr>
  <tr>
  <td>3.</td>
  <td>19AI301C</td>
  <td>Python and Linear Algebra(PYTHON)</td>
  </tr>
  <tr>
  <td>4.</td>
  <td>19EE309</td>
  <td>Programming Microcontrollers(PMC)</td>
  </tr>
  <tr>
  <td>5.</td>
  <td>19EN615C</td>
  <td>Japanese Basic & Advanced(JAPANESE)</td>
  </tr>
  <tr>
  <td>6.</td>
  <td>19AI305</td>
  <td>Advanced C Programming(AC)</td>
  </tr>
</table>
</html>

```

## OUTPUT

![alt text](<Screenshot 2024-03-16 094621.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
