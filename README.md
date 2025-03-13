# Ex03 Time Table
## Date:

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

<!DOCTYPE html>
<html lang="en">
    <th></ol>
        <center><img src="sav.jpg" height="150px" width="700px" alt="Something went wrong"></th></center>
<head>
    <center><title>Slot time table</title></center>
    <style>
        table {
            width: 65%;
            border-collapse: collapse;
            margin: 40px auto;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        th, td {
            border: 2px solid black;
            padding: 10px;
        }
        th {
            background-color: yellow;
            font-style:inherit ;
        }
        .highlight {
            background-color: cyan;
        }
        .title {
            text-align: center;
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
            font-style: unset;
        }
    </style>
</head>
<body>

    <div class="title">SLOT TIME TABLE - S Abiav aaditya (24002354)</div>

    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr class="highlight">
            <td>8-10</td>
            <td colspan="3">FREE SLOT</td>
            <!-- <td>FREE SLOT</td> -->
            <td>PHY</td>
            <td>CHE</td>
            
        </tr>
        <tr class="highlight">
            <td>10-12</td>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
        </tr>
        <tr class="highlight">
            <td>12-1</td>
            <td colspan="5"><B>L U N C H B R E A K </td>
        </tr>
        <tr class="highlight">
            <td>1-3</td>
            <td colspan="2">FREE SLOT</td>
            <!-- <td>FREE SLOT</td> -->
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
        </tr>
        <tr class="highlight">
            <td>3-5</td>
            <td colspan="2">FREE SLOT</td>
            <!-- <td>FREE SLOT</td> -->
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
        </tr>
    </table>

    <table>
        <tr>
            <th>S. No.</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19PH206</td>
            <td>Physics for Quantum Computing</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19EN612</td>
            <td>German Basic (GER)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY701</td>
            <td>Career Development</td>
        </tr>
    </table>

</



## OUTPUT

![image](https://github.com/user-attachments/assets/70ed4492-5332-44cb-b6a0-2416bd0d6cf1)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
