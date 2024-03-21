# Ex:03 Time Table
## Date:21.03.2024

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
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="C:\Users\91755\Pictures\Screenshots\logo.png" width="965">
        </center>
        <br>
        <table align="center" width="540">
            <caption><b><h1>Timetable KISHORE.B (212222110020)</h1></b></caption>
            <tr align="center">
                <th bgcolor="blue">Day/Time</th>
                <th bgcolor="blue">Monday</th>
                <th bgcolor="blue">Tuesday</th>
                <th bgcolor="blue">Wednesday</th>
                <th bgcolor="blue">Thursday</th>
                <th bgcolor="blue">Friday</th>
                <th bgcolor="blue">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="blue">8-10</th>
                <td bgcolor="yellow">Fundamentals of Web Application Developement</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">INTRODUCTION TO I.O.T</td>
                <td bgcolor="yellow">SYSTEM OF NUMERICAL AND LOGICAL TERMINOLOGY</td>
                <td bgcolor="yellow">INTRODUCTION TO I.O.T</td>
                <td bgcolor="yellow">OPERATING SYSTEM</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">10-12</th>
                <td bgcolor="yellow">FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">PROTOTYPING OF I.O.T SYSTEMS</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">SOFTWARE ENGINEERING</td>
                <td bgcolor="yellow">FREE SLOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">12-1</th>
                <td bgcolor="yellow">LUNCH</td>
                <td bgcolor="yellow">LUNCH</td>
                <td bgcolor="yellow">LUNCH</td>
                <td bgcolor="yellow">MENTOR MEET</td>
                <td bgcolor="yellow">LUNCH</td>
                <td bgcolor="yellow">LUNCH</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">1-3</th>
                <td bgcolor="yellow">PROTOTYPING OF I.O.T SYSTEMS</td>
                <td bgcolor="yellow">SOFTWARE ENGINEERING</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">FUNDAMENTALS OF WEB APPLICATION</td>
                <td bgcolor="yellow">FUNDAMENTALS OF WEB APPLICATION</td>
                <td bgcolor="yellow">FREE SLOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">3-5</th>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</td>
                <td bgcolor="yellow">OPERATING SYSTEMS</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td><font color="green">Fundamentals of Web Application Development (FWAD)</font></td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19CS420</td>
                <td><font color="blue">PROTOTYPING OF I.O.T</font></td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AM508</td>
                <td><font color="yellow">INTRODUCTION TO I.O.T</font></td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19AI405</td>
                <td><font color="green">FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</font></td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19CS405</td>
                <td><font color="blue">OPERATING SYSTEMS</font></td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19CS408</td>
                <td><font color="blue">SOFTWARE ENGINEERING</font></td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">19EY703</td>
                <td><font color="red">SYSTEM OF NUMERICAL AND LOGICAL TERMINOLOGY</font></td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
<img width="860" height=" 400" alt="Screenshot 2024-03-21 192302" src="https://github.com/KSIHORE/slot/assets/151484879/5a868ecb-a7cc-424b-9f94-19ae3dc07d1e">

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
