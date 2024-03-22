# Ex03 Time Table
## Date:17-3-24

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

<html>
<head>
<title> Sample Super  Web</title>
</head>
<img src="logo.png" height="200" width="1200">
<table border ="2" cellpadding="2" width="400" heigth="400"
<caption> <h2>Camu Schedule -senthamizhan-212221040150</h2></caption>
<tr bgcolor="red">


<th>Date</th>
<th>MONDAY</th>
<th>TUESDAY</th>
<th>WEDNESDAY</th>
<th>THURSDAY</th>
<th>FRIDAY</th>
<th>SATURDAY</th>


</tr>
<tr bgcolor="violet">
<td bgcolor="red">8-10</td>
<td>creative skills</td>
<td>free</td>
<td>MPMC</td>
<td rowspan="2">FREE</td>
<td>FWAT</td>
<td>FREE</td>

</tr>
<tr bgcolor="violet">
<td bgcolor="red">10-12</td>
<td>FREE</td>
<td>MPMC</td>
<td>Drones</td>


<td>MPMC</td>
<td>Drones</td>

</tr>
<tr bgcolor="violet">

<td bgcolor="red">12-1</td>

<td colspan="6" align="center"> LUNCH BREAK</td>


</tr>

<tr bgcolor="violet">

<td bgcolor="red">1-3</td>
<td>C++</td>
<td>FWAT</td>
<td>C++</td>
<td>FWAD</td>
<td rowspan="2" align="center"> FREE</td>
<td>FREE</td>

</tr>
<tr bgcolor="violet">
<td bgcolor="red">3-5</td>
<td>Adv</td>
<td colspan="3" align="center"> FREE</td>


<td>Employement</td>
</tr>

</table>
<table border ="2" cellpadding="2" width="400" heigth="400" bgcolor="violet">
<tr bgcolor="">
<th>S.no</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1</td>
<td>19EC606</td>
<td>Drones</td>
</tr>
<tr>
<td>2</td>
<td>19EY702</td>
<td>Creative skills</td>
</tr>
<tr>
<td>3</td>
<td>19AI414</td>
<td>Fundamental Of web Development</td>
</tr>
<tr>
<td>4</td>
<td>19EY705</td>
<td>Employement Enchancement Skills</td>
</tr>
<tr>
<td>5</td>
<td>19EY704</td>
<td>Advanced Quantitative and logical Reasoning</td></tr>
<tr>
<td>6</td>
<td>19EC408</td>
<td>Microprocessor and Microcontroller</td>
</tr>
</table>
</body>
</html>

</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-03-18 224209.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
