# Ex03 Time Table
## Date:18/11/2024

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
<html><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252"></head>
<body><img src="logo.png">
        <table border="1" cellspacing="6" cellpadding="2">
            <caption>SLOT TIME TABLE - HARIKA S(24002063)</caption>
            <tbody><tr bgcolor="lavender">
               <th bgcolor="violet">DAY/TIME</th>
               <th>Monday</th>
               <th>Tuesday</th>
               <th>Wednesday</th>
               <th>Thursday</th>
               <th>Friday</th>
               <th>Saturday</th>
            </tr>
                <tr bgcolor="beige">
                    <td bgcolor="violet">8-10</td>
                    <td>FREE SLOT</td>
                    <td>CA</td>
                    <td>FCP</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>EMPD</td>
                </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">10-12</td>
                <td>EMPD</td>
                <td>DE</td>
                <td>CDS</td>
                <td>CA</td>
                <td>BEEE</td>
                <td>FWAD</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">12-1</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">1-3</td>
                <td>FCP</td>
                <td>FWAD</td>
                <td>SCOFT MM</td>
                <td>FWAD</td>
                <td>DE</td>
                <td>CHEM</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">3-5</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>CHEM</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>BEEE</td>
            </tr>
        </tbody></table>
        <table border="1" cellspacing="6" cellpadding="2">
            <tbody><tr bgcolor="sky blue">
                <th bgcolor="sky blue">S.NO</th>
                <th>Course code</th>
                <th>Course name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI303</td>
                <td>ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EY708</td>
                <td>CAREER DEVELOPMENT SKILLS</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CS305</td>
                <td>COMPUTER ARCHITECTURE</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
                <tr>
                    <td>8.</td>
                    <td>19EE305</td>
                    <td>BASICS ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING</td>
            </tr>
            <tr>
                <td>9.</td>
                <td>ECA-M-SCOFT</td>
                <td>MENTOR MEET</td>
            </tr>
        </body></table>
    
</body></html>
```


## OUTPUT
![alt text](<Screenshot 2024-11-17 104959.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
