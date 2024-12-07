# Ex03 Time Table
# Date:18/11/2024
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
        <center>
       
    </center>
    </head>
    <style>
        .no-border{
            border:none
        }
        .vertical-align{
            writing-mode:vertical-lr
        }
        th{
            background-color:rgb(83, 175, 225);
        }
        tr{
            background-color: ghostwhite;
        }
    </style>
    <center>
    <boder-collopes:collopes></boder-collopes:collopes>
    <table border="9" width="800" high="2000" style="color:darkblue">
    
    <body bgcolor="white" style="color:rgb(9, 10, 10)">
        <img src="/static/download.png" hight="10" width="1000">
        <hr>
        <h1>TIME TABLE</h1>
        <tr>
            <th style="color:forestgreen">TIME</th>
            <th style="color:forestgreen">8-10</th>
            <th style="color:forestgreen">10-12</th>
            <th style="color:forestgreen">12-1</th>
            <th style="color:forestgreen">1-3</th>
            <th style="color:forestgreen">3-5</th>
        </tr>
        <tr>
            <th>MONDAY</th>
            <td></td>
            <td>WEB APPLICATION</td>
            <th class="no-border vertical-align" rowspan="6">L u n c h</th>
            <td>DIGITAL Electronics</td>
            <td></td>
        </tr>
        <tr>
            <th>TUESDAY</th>
            <td>COMPUTER ARTICTECH</td>
            <td></td>
            
            <td>STATISTICS&NUMERICAL METHODS</td>
            <td></td>

        </tr>
        <tr>
            <th>WEDENSDAY </th>
            <td>STATISTICS&NUMBERICAL METHODS</td>
            <td>CPROGRAMMING</td>
           
            <td>SCOFT</td>
            <td></td>
        </tr>
        <tr>
            <th>THRUSDAY</th>
            <td>PHYSICS</td>
            <td>COMPUTER ARTICTECH</td>

            <td>web</td>
            <td></td>
        </tr>
        <tr>
            <th >FRIDAY</th>
            <td></td>
            <td>CAREER DEVELOPEMENT</td>
 
            <td>QUANTAM PHYSIC</td>
            <td></td>
        </tr>
        <tr>
            <th >SATURDAY</th>
            <td></td>
            <td>DIGITAL Electronics</td>
            
            <td>C PROGRAMMING</td>
            <td>WEB Application</td>
        </tr>
    </table>
    
    <table border="3">
            
           
            <tr>
                <th>S.NO</th>
                <th>Code</th>
                <th>Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI304</td>
                <td>C PROGRAMMING</td> 
            </tr>
            

            <tr>
                <td>2</td>
                <td>19AI414</td>
                <td>Fundamental of Web Application Developement</td> 
            </tr>
            <tr>
                <td>3</td>
                <td>19EE305</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td> 
            </tr>
            <tr>
                <td>4</td>
                <td>19CS305</td>
                <td>COMPUTER ARTICTECH</td> 
            </tr>
           
            <tr>
                <td>7</td>
                <td>19EY703</td>
                <td>Career Developement Skills</td> 
            </tr>
            <tr>
                <td>8</td>
                <td>19MA211</td>
                <td>STATISTICS AND NUMERICAL METHODS</td> 
            </tr>
            
        </table>  
        
    </body>
    </center>
</html>
```
# OUTPUT
![alt text](<Screenshot 2024-12-07 091241.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
