# Ex03 Time Table
## Reg no:212221223003
## Date:25/09/2024

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
<html>
    <head>
        <title>My TimeTable</title>
    </head>
    <body>
         <center>
        <center>
        <img src="logo.png" height="100">
        </center>
        <table border="3" bgcolor="cyan">
            <caption align="center"><b>SLOT TIME-TABLE PRIYANGHA G (23012857)</b></caption>
            <tr bgcolor="violet">
               <th bgcolor="violet">DAY</th>
               <th colspan="2">8:00-10:00</th>
               <th colspan="2">10:00-12:00</th>
               <th colspan="2">12:00-1:00</th>
               <th colspan="2">1:00-3:00</th>
               <th colspan="2">3:00-5:00</th>
            </tr>
            <tr>
                <th bgcolor="violet">Mon</th>
                <td colspan="2">EDM</td>
               <td colspan="2">Public Speaking</td>
               <td colspan="2" rowspan="5" align="center" bgcolor="yellow">LUNCH</td>
               <td colspan="2" bgcolor="Snow">FREE</td>
               <td colspan="2">Phy</td>
            </tr>
            <tr>
                <th bgcolor="Violet">Tues</th>
                <td colspan="2">Python</td>
                <td colspan="2" bgcolor="Snow">FREE</td>
                <td colspan="4" align="center" bgcolor="Snow">FREE</td>
            </tr>
            <tr>
                <th bgcolor="violet">Wed</th>
                <td colspan="2">FWAD</td>
                <td colspan="2">Com Arch</td>
                <td colspan="2" align="center">Free</td> 
                <td colspan="2">Python</td>
            </tr>
            <tr>
                <th bgcolor="violet">Thu</th>
                <td colspan="2">Soft Skills</td>
                <td colspan="2">FWAD</td>
                <td colspan="2">Public Speaking</td> 
                <td colspan="2">MAT</td
            </tr>
            <tr>
                <th bgcolor="violet">Fri</th>
                <td colspan="2">MAT</td>
                <td >CA</td>              
                <td >Phy</td>
                <td colspan="2">FWAD</td>
                <td colspan="2">EDM</td>

            </tr>

        </table>
        <br><br>
        <table border="3">
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19MA201</td>
                <td>Calculus and Matrix Algebra(MAT)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19EY701</td>
                <td>Soft Skills</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19AI301</td>
                <td>Python Programming(Python)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19CS305</td>
                <td>Computer Architecture</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19EN105</td>
                <td>Public Speaking</td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">19AI302</td>
                <td>Engineering Design and Modelling</td>
            </tr>
            <tr>
                <td align="center">8.</td>
                <td align="center">19PH214</td>
                <td>Physics for Quantum Computing</td>
            </tr>
            
            
        </table>
</center>
    </body>
</html>
```

## OUTPUT
![slot03](https://github.com/user-attachments/assets/720795ed-af11-4823-9e55-4a9c7247c554)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
