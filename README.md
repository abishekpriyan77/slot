# Ex03 Time Table
## Date:16/11/2024

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
~~~
<html>
     <head>
        <title>slot timetable</title>
     </head>
    <body>
     <center>
        <img src="logo.png" height="100" width="540">
     </center>
     <br>
     <table align="center" width="540" cellspacing="4" border="5" bgcolor="cyan">
      <caption><b>SLOT TIME TABLE- Abisheik priyan V (24900599)</b></caption>
      <tr align="center">
        <th bgcolor="yellow">Day/time</th>
        <th bgcolor="yellow">Monday</th>
        <th bgcolor="yellow">Tuesday</th>
        <th bgcolor="yellow">Wednesday</th>
        <th bgcolor="yellow">Thursday</th>
        <th bgcolor="yellow">Friday</th>
      </tr>  
      <tr align="center">
        <th bgcolor="yellow">8-10</th>
        <td>FUNDAMENTAL OF WEB APPLICATION AND DEVELOPMENT</td>
        <td>PYTHON PROGRAMMING</td>
        <td>INTRO TO DS</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>CDS</td>
      </tr>
      <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td>FREE SLOT</td>
        <td>CDS</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>PYTHON PROGRAMMING</td>
        <td>INTRO TO DS</td>
      </tr>
      <tr align="center">
        <th bgcolor="yellow">12-1</th>
        <td colspan="5" align="center">LUNCH</td>
        
      </tr>
      <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>PYTHON PROGRAMMING</td>
        <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
        <td>FREE SLOT</td>
      </tr>
      <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td> CAREER DEVELOPMENT</td>
        <td>FREE SLOT</td>
        <td>BEEE</td>
        <td>FUNDAMNETALS OF WEB APPLICATION AND DEVELOPMENT</td>
        <td>FREE SLOT</td>
      </tr>
     </table>
    <br>
<table align="center" cellspacing="2" cellspacing="4" border="2">
<tr align="center">
    <th>S.NO.</th>
    <th>subject code</th>
    <th>subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td align="center">fundamentals of web application and development</td> 
</tr>  
<tr>
    <td align="center">1.</td>
    <td align="center">19A1305</td>
    <td align="center">career development</td> 
    </tr> 
    <tr>
        <td align="center">1.</td>
        <td align="center">19AI342</td>
        <td align="center">iot</td> 
        </tr> 
        <tr>
            <td align="center">1.</td>
            <td align="center">19A1403</td>
            <td align="center">Intro to data science</td> 
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19EN101</td>
                <td align="center">Communicative english</td> 
                </tr> 
                <tr>
                    <td align="center">1.</td>
                    <td align="center">19A1301C</td>
                    <td align="center">python programming</td> 
                    </tr> 
                    <tr>
                        <td align="center">1.</td>
                        <td align="center">19A1310</td>
                        <td align="center">BEEE</td> 
                        </tr> 
</table>  
 </body>
</html>
~~~

## OUTPUT

![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
