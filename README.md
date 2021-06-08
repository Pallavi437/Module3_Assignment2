<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>squares and cubes of the number</title>
</head>
<style>
    h3{
        text-align: center;
    }
    table {
     margin: auto;
     border-collapse: collapse;
     margin-top: 50px;
     background-color: rgb(172, 170, 170);
    } 
    table tr th{
        border: solid black;
        padding: 5px;
    }  
    table tr td  {
        border: solid black;
        text-align: center;
        padding: 3px 50px 3px 50px;
       
    }
   </style>
<body>
    <h3>NUMBERS FROM 0 TO 10 WITH THEIR SQUARES AND CUBES</h3>
    <script>
        document.write( "<table><tr><th>Number</th><th>Square</th><th>Cube</th></tr>" );
        for(var n=0; n<=10; n++)
        {
        document.write( "<tr><td>" + n + "</td><td>" + n*n + "</td><td>" + n*n*n + "</td></tr>" ) ;
        }
        document.write( "</table>" ) ;
    </script>
</body>
</html>
