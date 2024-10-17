# Ex03 Time Table
## Date: 17.10.24

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
Name : VISHNU KM
Reg no: 212223240185


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: green; /* Changed background color to green */
        }
        table {
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: blue;
            color: white;
        }
        caption {
            font-size: 1.5em;
            margin: 10px;
        }
    </style>
</head>
<body>
    <center>
        <img src="sec1.png" height="100" width="540" alt="Logo">
    </center>
    <br>
    <table width="540" border="5" bgcolor="gold">
        <caption><b>SLOT TIMETABLE - NAME : VISHNU KM/ REG.NO: 212223240185</b></caption>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <th>8-10</th>
            <td>FREE</td>
            <td>Compiler Design</td>
            <td>WEB</td>
            <td>FREE</td>
            <td>Transforms and its Application</td>
            <td>FREE</td>
        </tr>
        <tr>
            <th>10-12</th>
            <td>ANT</td>
            <td>Programming Microcontrollers</td>
            <td>Transforms and its Application</td>
            <td>ANT</td>
            <td>FREE</td>
            <td>Operating System</td>
        </tr>
        <tr>
            <th>12-1</th>
            <td colspan="6">LUNCH BREAK</td>
        </tr>
        <tr>
            <th>1-3</th>
            <td>ML</td>
            <td>FREE</td>
            <td>MENTOR MEET</td>
            <td>QUANTITATIVE</td>
            <td>FREE</td>
            <td>Compiler Design</td>
        </tr>
        <tr>
            <th>3-5</th>
            <td>FREE</td>
            <td>FREE</td>
            <td>FREE</td>
            <td>Operating System</td>
            <td>FREE</td>
            <td>FREE</td>
        </tr>
    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI303</td>
            <td>Engineering Mechanics and Product Development</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI410</td>
            <td>Intro to Machine Learning</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS406</td>
            <td>Compiler Design</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS579</td>
            <td>Programming Microcontrollers</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EY710</td>
            <td>Quantitative Ability I</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19MA211</td>
            <td>Transforms and its Application</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19MA212</td>
            <td>Algebra and Number Theory</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>19AI305</td>
            <td>Advanced C Programming</td>
        </tr>
        <tr>
            <td>9.</td>
            <td>ECA-M</td>
            <td>Mentor Meet</td>
        </tr>
    </table>
</body>
</html>

## OUTPUT
![image](https://github.com/user-attachments/assets/bc346345-bdaa-4a18-b071-635b53e847ed)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
