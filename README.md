# Ex03 Time Table
# Date:22.10.2025
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sree lakshmi</title>
    <Style>
        body{
            display:flex;
            flex-direction: column;
            justify-content:center;
            align-items:center;
            height:100vh;
            background-color:#f8f9fa;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }
        table{
            border-collapse:collapse;
            width:60%;
            margin: 10px auto;
            font-size:15px;
            text-align:center;
            background-color:white;
            box-shadow:0px 4px 10px rgba(0,0,0,0.2)
        }
        th,td{
            border:2px solid purple;
            padding:15px;
        }
        th{
            background-color:#dcc4e9;
        }
        tr:nth-child(even){
            background-color:#f3e5f5;
        }
        tr:nth-child(odd){
            background-color:#ede7f6;
        }
        h1{
            text-align:right;
            color:black;
        }
    </Style>
</head>
<body>
    
    <h1>CLASS TIME TABLE - SREE LAKSHMI B (25015545)</h1>
    <table border="3">
        <tr>
            <th>Day/Hours</th>
            <th>8.00 a.m - 10.00 a.m</th>
            <th>10.00 a.m - 12.00 p.m</th>
            <td rowspan="7">L <br><br><br> U <br><br><br> N <br><br><br> C <br><br><br> H</td>
            <th>1.00 p.m - 3.00 p.m</th>
            <th>3.00 p.m - 5.00 p.m</th>
        </tr>
               
    
        <tr>
            <th>MONDAY</th>
            <td>WEB </td>
            <td>-</td>
            <td>C PROGRAMMING</td>
            <td>-</td>
        </tr>
        <tr>
            <th>TUESDAY</th>
            <td>ENGLISH</td>
            <td>ENGLISH</td>
            <td colspan="2">-</td>
        </tr>
        <tr>
            <th>WEDNESDAY</th>
            <td>WEB</td>
            <td>WEB</td>
            <td>MENTOR MEET</td>
            <td>C PROGRAMMING</td>
        </tr>
        <tr>
            <th>THURSDAY</th>
            <td>ENGLISH</td>
            <td>C PROGRAMMING</td>
            <td>ENGLISH</td>
            <td>C PROGRAMMING</td>
        <tr>
            <th>FRIDAY</th>
            <td>C PROGRAMMING</td>
            <td>WEB</td>
            <td colspan="2">-</td>
        </tr>
        <tr>
            <th>SATURDAY</th>
            <td>ENGLISH</td>
            <td>WEB</td>
            <td>ENGLISH</td>
            <td>-</td>
        </tr>
    </table>
    <h2>Subjects</h2>
    <table>
        <tr>
            <th>S.NO</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19A1414</td>
            <td>Fundamentals Of Web Applicatin And Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19EN101</td>
            <td>Communicative English</td>
        </tr>
    </table>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-09-22 081412.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
