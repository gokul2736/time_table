# Ex-03 Time Table
# Date:27-09-2024
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

```<!DOCTYPE html>
<html lang="en">
<head>
    <title> Gokul's TimeTable</title>
</head>
<body>
    <center>
        <img src="logo.png"
        height="100"
        width="540">
    </center>
    <br>
    <table align="center" 
    width="540"
    cellspacing="2"
    cellpadding="4"
    border="5"
    bgcolor="white" > 
    <caption><b>Time Table:-M.gokul (24000042) </b><br><br></caption>
    <tr align="center">
        <th bgcolor="orange">Day/Time</th>
        <th bgcolor="orange">8-10</th>
        <th bgcolor="orange">10-12</th>
        <th bgcolor="orange" rowspan="7"> <br>L<br>U<br>N<br>C<br>H<br></th>
        <th bgcolor="orange">1-3</th>
    </tr>
    <tr align="center">
        <th bgcolor="orange"> Monday</th>
        <td bgcolor="cyan"> FREE SLOT</td>
        <td bgcolor="cyan"> ENG</td>
        <td bgcolor="cyan"> WEB</td>
    </tr>
    <tr align="center">
        <th bgcolor="orange"> Tuesday</th>
        <td bgcolor="cyan"> EDM</td>
        <td bgcolor="cyan"> PHY</td>
        <td bgcolor="cyan"> MATH</td>
    </tr>
    <tr align="center">
        <th bgcolor="orange"> Wednesday</th>
        <td bgcolor="cyan"> EDM</td>
        <td bgcolor="cyan"> CARR DEV</td>
        <td bgcolor="cyan"> MENTOR</td>
    </tr>
    <tr align="center">
        <th bgcolor="orange"> Thursday</th>
        <td bgcolor="cyan"> ENG</td>
        <td bgcolor="cyan"> PYTHON</td>
        <td bgcolor="cyan"> FREE SLOT</td>
    </tr>
    <tr align="center">
        <th bgcolor="orange"> Friday</th>
        <td bgcolor="cyan"> PHY</td>
        <td bgcolor="cyan"> WEB</td>
        <td bgcolor="cyan"> MATH</td>
    </tr>
    <tr align="center">
        <th bgcolor="orange"> Saturday</th>
        <td  align="center" bgcolor="cyan"> FREE SLOT</td>
        <td bgcolor="cyan"> WEB</td>
        <td bgcolor="cyan"> PYTHON</td>
    </tr>
    </table>
    <br>
    <table align="center"
    cellspacing="2"
    cellpadding="4"
    border="2">
    <tr align="center">
    <th>S.No</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
    </tr>
    <tr>
        <td align="center">1.</td>
        <td align="center"> 19EN101</td>
        <td> Communicative English</td>
    </tr>
    <tr>
        <td align="center">2.</td>
        <td align="center"> 19EY708</td>
        <td>Career Development Skills</td>
    </tr>
    <tr>
        <td align="center">3.</td>
        <td align="center"> SH3214</td>
        <td>Physics For Quantum Computing (PHY)</td>
    </tr>
    <tr>
        <td align="center">4.</td>
        <td align="center"> 19AI414</td>
        <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19AI301C</td>
        <td>Python and Linear Algebra</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19AI302</td>
        <td>Engineering Design and Modelling </td>
    </tr>
    </table>
</body>
</html>
```

# OUTPUT
![tym tbl](https://github.com/user-attachments/assets/f9fb77ad-312d-4c24-bb0d-5705b290d2dd)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
