# Ex03 Time Table
## Date: 19/12/2024

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
<body>
    <head>
        <title align="center">SLOT TIMETABLE</title>
    </head>
     <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>        
        <center>
            <b><font color="black" size="5">SLOT TIMETABLE-HARINI S(24010678)</font></b>
        </center>
            <table align="center" border="2" cellpadding="4" bordercolor=" black" bgcolor="cyan">
                <tr>
                    <th bgcolor="yellow"><font color="black"  size="5">Day</font></th>
                    <th bgcolor="yellow"><font color="black"  size="5">8:00 to 10:00</font></th>
                    <th bgcolor="yellow"><font color="black"  size="5">10:00 to 12:00</font></th>
                    <th bgcolor="yellow"><font color="black"  size="5">12:00 to 1:00</font></th>
                    <th bgcolor="yellow"><font color="black"  size="5">1:00 to 3:00</font></th>
                    <th bgcolor="yellow"><font color="black"  size="5">3:00 to 5:00</font></th>
                </tr>
                <tr>
                    <td align="center"bgcolor="yellow"><font color="black"  size="5">Monday</font></td>
                    <td align="center"><font color="black" size="5">Free Hour </font></td>
                    <td align="center "><font color="black"  size="5">COMMUNICATIVE ENGLISH</font></td>
                    <td align="center" rowspan="6"><font color="black"  size="5"> LUNCH HOUR</font></td>
                    <td align="center"><font color="black"  size="5">BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING</font></td>
                    <td align="center"><font color="black" size="5">Free Hour</font></td>
                </tr>
                <tr>
                    <td align="center"bgcolor="yellow"><font color="black"  size="5">Tuesday</font></td>
                    <td align="center "><font color="black"  size="5">ENGINEERING DESIGN AND MODELLING</font></td>
                    <td align="center "><font color="black"  size="5">STATISTICS AND NUMERICIAL METHODS</font></td>                     
                    <td align="center"><font color="black"  size="5">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</font></td>
                    <td align="center"><font color="black"  size="5">FREE HOUR</font></td>

                </tr>
                <tr>
                    <td align="center"bgcolor="yellow"><font color="black"  size="5">Wednesday</font></td>
                    <td align="center "><font color="black"  size="5">ENGINEERING DESIGN AND MODELLING</font></td>
                    <td align="center"><font color="black"  size="5">PRINCIPLES OF CHEMISTRY IN ENGINEERING</font></td>                    
                    <td align="center"><font color="black"  size="5">MENTOR MEET</font></td>
                    <td align="center"><font color="black"  size="5">BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING</font></td>
                </tr>
                <tr>
                    <td align="center"bgcolor="yellow"><font color="black"  size="5">Thursday</font></td>
                    <td align="center"><font color="black"  size="5">COMMUNICATIVE ENGLISH</font></td>
                    <td align="center"><font color="black" size="5">Free Hour</font></td>                    
                    <td align="center"><font color="black"  size="5">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</font></td>
                    <td align="center" ><font color="black" size="5">Free Hour</font></td>
                    </tr>
                <tr>
                    <td align="center"bgcolor="yellow"><font color="black"  size="5">Friday</font></td>
                    <td align="center"><font color="black"  size="5">FREE HOUR</font></td>
                    <td align="center "><font color="black"  size="5">PRINCIPLES OF CHEMISTRY IN ENGINEERING</font></td>                    
                    <td align="center" ><font color="black" size="5">Free Hour</font></td>
                    <td align="center" ><font color="black" size="5">Free Hour</font></td>
                </tr>
                <tr>
                    <td align="center"bgcolor="yellow"><font color="black" size="5">Saturday</font></td>
                    <td align="center"><font color="black"  size="5">STATISTICS AND NUMERICIAL METHODS</font></td>
                    <td align="center "><font color="black" size="5">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</font></td>                    
                    <td align="center"><font color="black"  size="5">FREE HOUR</font></td>
                    <td align="center"><font color="black"  size="5">FREE HOUR</font></td>
                </tr>
                <br>
                <br>
            <center>    
              
            </table>
            <table border="1" cellspacing="0" cellpadding="5">
          <thead>
          <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
          </tr>
          </thead>
          <tbody>
          <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
          </tr>
          <tr>
            <td>2.</td>
            <td>19MA211</td>
            <td>STATISTICS AND NUMERICIAL METHODS</td>
          </tr>
          <tr>
            <td>3.</td>
            <td>19EN101</td>
            <td>COMMUNICATIVE ENGLISH</td>
          </tr>
          <tr>
            <td>4.</td>
            <td>19CY205</td>
            <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
          </tr>
          <tr>
            <td>5.</td>
            <td>19AI302</td>
            <td>ENGINEERING DESIGN AND MODELLING</td>
          </tr>
          <tr>
            <td>6.</td>
            <td>19EE305</td>
            <td>BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING</td>
          </tr>
        </tbody>
      </table>
    </center>
    </body>
    </html>
    ```

 ## OUTPUT
 ![Alt text](<Screenshot (79).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
