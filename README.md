# Ex03 Time Table
## Date:
8-04-2025
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
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
</head>
<body>
    <h1>Slot Timetable</h1>
    <table border="1">
        <tr>
            <th>Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td>9:00 - 10:00</td>
            <td>Math</td>
            <td>Science</td>
            <td>History</td>
            <td>Geography</td>
            <td>English</td>
        </tr>
        <tr>
            <td>10:00 - 11:00</td>
            <td>English</td>
            <td>Math</td>
            <td>Science</td>
            <td>History</td>
            <td>Art</td>
        </tr>
    </table>
</body>
</html>

## OUTPUT
![Screenshot 2025-04-08 143422](https://github.com/user-attachments/assets/cd1c78b4-812a-4e31-bda6-2baa07bfd6f0)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
