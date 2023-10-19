# Ex03 Time Table
## DATE: 09/10/23
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

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<center>
<img src ="logo.png" width="200" cellspacing="2" cellpaddin="2" border="2" bgcolor="white">
</center>
<title>TIME DEVADARSHAN A S (212222110007)</title>
</head>
<body>

<table align="center" width="600" cellspacing="2" cellpadding="2" border="2" bgcolor="white">
<caption><b>TIME TABLE-DEVADARSHAN A S(212222110007)</b></caption><br>

<th align bgcolor="cyan" >Date/Day</td>
<td align bgcolor="cyan" >Monday</td>
<td align bgcolor="cyan" >Tuesday</td>
<td align bgcolor="cyan" >wednesday</td>
<td align bgcolor="cyan" >Thursday</td>
<td align bgcolor="cyan" >Friday</td>
<td align bgcolor="cyan" >Saturday</td>
</tr>
</tr>
<tr align="center">
<td align bgcolor="PURPLE">8-10</th>  
<th colspan="2" bgcolor="pink">FREE</th>    
<td align bgcolor="orange">MATH</th>
<td align bgcolor="lightgreen">FREE</th>
<td colspan="1" bgcolor="pink">EDM</th>    
<td align bgcolor="lightgreen">FREE</th>
</tr>
<tr>
<tr align="center">
<td align bgcolor="PURPLE">10-12</td>
<th align="color" colspan="1" bgcolor="GREY">FREE</th>  
<td align bgcolor="#CCCCFF">EDM</td>
<td align bgcolor="#CCCCFF">MATH</td>
<td align bgcolor="#FA8072"> MC</td>
<td align bgcolor="orange">FREE</th>
<th align="color" colspan="1" bgcolor="GREY">FREE</th>  
</tr>
<tr>
<tr align="center">
<td align bgcolor="PURPLE">12-1</td>
<td colspan="6" align bgcolor="gold">LUNCH</td>
<tr>
<tr align="center">
<td align bgcolor="PURPLE">1-3</td>
<td align bgcolor="	#C0C0C0">MATH</td>
<th align="color" colspan="1" bgcolor="pink">MC</th>  
<td align bgcolor="violet"> EDM</td>
<th align="color" colspan="2" bgcolor="pink">Free</th>  
<td align bgcolor="	#C0C0C0">FREE</td>
</tr>
<tr>
<tr align="center">
<td align bgcolor="PURPLE">3-5</td>
<th align="color" colspan="1" bgcolor="GREY">FREE</th>  
<td align bgcolor="lightgreen">EDM</th>
<th align="color" colspan="2" bgcolor="GREY">FREE</th>  
<td align bgcolor="violet"> MC</td>
<td align bgcolor="#FA8072"> WEB</td>
</tr>
</table>
</body>
</table>
</br>
<br>
<table align="center" cellspacing="3" cellpadding="3" border="4">
<tr align="center">
<th align >S.No</td>
<th align >Subject Code</td>
<th align >Subject Name</td>
</tr>
<tr>
<tr align="center">
<th align >1</td>
<th align >19AI414</td>
<th align >Fundamentals of Web Application Development</td>
</tr>


<tr>
<tr align="center">
<th align >2</td>
<th align >19AI401</td>
<th align >EDM</td>

</tr>


<tr>
<tr align="center">
<th align >3</td>
<th align >19CS408</td>
<th align >DBMS</td>
</tr>


<tr>
<tr align="center">
<th align >4</td>
<th align >19EE309</td>
<th align >Programming Microcontrollers</td>
</tr>


<tr>
<tr align="center">
<th align >5</td>
<th align >19MA217</td>
<th align >Algebra and number theorey</td>

</tr>
<tr>
<tr align="center">
<th align >6</td>
<th align >19MA222</td>
<th align >Transfroms and its application</td>

</tr>

</html>
```

## OUTPUT
![sllot output](https://github.com/DEVADARSHAN2/slot/assets/119432150/98885035-8daf-4737-a26f-deb206f5ac5e)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
