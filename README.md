# Ex03 Time Table
## Date:18-03-2024

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
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <center>
    <img src="logo.png" height="70" width="550">
    </center>
    <title>Slot Timetabe</title>
</head>
 <body>
    <table align="center" border="3" bordercolor="black" cellpadding="2" cellspacing="4">
    <caption><h2>Slot Timetable-Ashwin Akash M</h2></caption>
    <tr bgcolor="aqua">
    <th>Day/Time</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    <th>Saturday</th>
    </tr>
    <tr bgcolor="#FF00FF">
        <th bgcolor="aqua">8-10</th>
        <td>Free Slot</td>
        <td>BEEE</td>
        <td>Web</td>
        <td>Free Slot</td>
        <td>BEEE</td>
        <td>Prob</td>
    </tr>
    <tr bgcolor="#FF00FF">
        <th bgcolor="aqua">10-12</th>
        <td>Robo</td>
        <td>Web</td>
        <td>Free Slot</td>
        <td>Prob</td>
        <td>C prog</td>
        <td>EMPD</td>
    </tr>
    <tr>
        <th bgcolor="aqua">12-1</th>
        <td colspan="6" align="center" bgcolor="#FF00FF">LUNCH</td>
    </tr>
    <tr bgcolor="#FF00FF">
        <th bgcolor="aqua">1-3</th>
        <td>Web</td>
        <td>Phy</td>
        <td>Phy and hrm</td>
        <td>EMPD</td>
        <td>HRM</td>
        <td>Free Slot</td>
    </tr>
    <tr bgcolor="#FF00FF">
        <th bgcolor="aqua">3-5</th>
        <td>C program</td>
        <td>Free Slot</td>
        <td>Free Slot</td>
        <td>Creative skill</td>
        <td>Robo</td>
        <td>Free Slot</td>
    </tr>
    </table>
    <br>
    <br>
   <table border="5" align="center" bordercolor="black" cellpadding="3" cellspacing="3">
    <tr>
        <th>S.No</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamental Of Web Application Development</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19AI303</td>
        <td>Engineering Mechanics And Product Development</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19AI304</td>
        <td>Fundamental Of C Programming</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19AI533</td>
        <td>Introduction To Robotics</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19EE305</td>
        <td>Basic Electrical,Electronics and Measrement Enginnering</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19EY702</td>
        <td>Creative Skill For Communication</td>
    </tr>
    <tr>
        <td>7</td>
        <td>19MA222</td>
        <td>Probability And Queueing Models</td>
    </tr>
    <tr>
        <td>8</td>
        <td>19MS156</td>
        <td>Human Resource Management And Team Building</td>
    </tr>
    <tr>
        <td>9</td>
        <td>19PH214</td>
        <td>Physics For Quantum Computing</td>
    </tr>
   </table>


 </body>
 </html>
```

## OUTPUT
![alt text](webtable.png)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
