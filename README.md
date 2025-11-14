# Ex03 Time Table
## Date:14.11.25

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
        <title>slot Timetable</title>    
    </head>
    <body>
        <center>
            <img src="logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="10" border="5" bgcolor="white">
<caption><b>ABINAYA A 212224230004</b></caption>
<tr bgcolor="lightblue" align="center">
<th>Day/Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
<th>Saturday</th>
</tr>
<tr align="center">
<th bgcolor="lightblue">8-10</th>
<td>BEEE</td>
<td>QA</td>
<td>Stock Market</td>
<td>Stock Market</td>
<td>Statistics</td>
<td>FREE SLOT</td>

</tr>
<tr align="center">
<th bgcolor="lightblue">10-12</th>
<td>SE</td>
<td>Intro to ds</td>
<td>web</td>
<td>advance c programming</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="lightblue">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="lightblue">1-3</th>
<td>Web</td>
<td>BEEE</td>
<td>MENTOR</td>
<td>FREE SLOT</td>
<td>SE</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="lightblue">3-5</th>
<td>statistics</td>
<td>FREE SLOT</td>
<td>Advance c programming</td>
<td>FREE SLOT</td>
<td>Intro to ds</td>
<td>FREE SLOT</td>


</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="4" border="5">
<tr align="center">
<th bgcolor="lightblue">s. No.</th>
<th bgcolor="lightblue">Subject Code</th>
<th bgcolor="lightblue">Subject Name</th>
</tr>
<tr bgcolor="lightblue">
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Appilication Development(FWAD)</td>
</tr>
<tr bgcolor="lightblue">
<td align="center">2.</td>
<td align="center">19CS408</td>
<td>Software Engineering(SE)</td>
</tr>
<tr bgcolor="lightblue">
<td align="center">3.</td>
<td align="center">19AI305</td>
<td>Advance C programming </td>
</tr>
<tr bgcolor="lightblue">
<td align="center">4.</td>
<td align="center">19AI403</td>
<td>Introduction To Data Science</th>
</tr>
<tr bgcolor="lightblue">
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>Statisical and Numerical Method</td>
</tr>
<tr bgcolor="lightblue">
<td align="center">6.</td>
<td align="center">19MS155</td>
<td>Stock Market and Company Operation</td>
</tr>
<tr bgcolor="lightblue">
<td align="center">7.</td>
<td align="center">19MEY710</td>
<td>Quantitative ability(QA)</td>
</tr>
<tr bgcolor="lightblue">
<td align="center">8.</td>
<td align="center">19EE305</td>
<td>Basic Electrical,Electronics and Measurement Engineering(BEEE)<td>
</tr>
</tr>
</tr>
</table>
</body>
</html>
```


## OUTPUT

![500340151-92496c25-64f8-4273-91e2-eef2e10e3ee4](https://github.com/user-attachments/assets/d1a807b3-8af7-4cc8-9066-42f7550b8646)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
