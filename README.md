# Ex.07 Software Product Company Website
## Date:14-12-23

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home1.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:plum;
            color:purple;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:45%;
        }
        a{
            color:purple;
            text-decoration: none;
        }
        a:hover{
            color:yellow;
            cursor:pointer;
 }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: plum;
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:plum;
        
        }
        .heading1{
            color:purple;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:plum;
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
 p{
            color:purple;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:plum;
            color:purple;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 105px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1>
              DATA ANALYTICS INNOVATIONS  
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
"The role of data analytics in an organization is 
to provide a greater level of specificity "<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                           <p> Username:</p>
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p> Password:</p>
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: purple; color:white;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Santhiya (23013041)</p>
    </div>
</body>
<html>

products.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:purple;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:purple;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
 input{
            width: 18%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:purple;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:white;
            cursor:pointer;
        }
        a{
            color:purple;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 50px;
            padding-bottom: 10px;
            text-align: center;
            color:plum;
        }
      p{
            color:purple;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:purple;
            text-align: center;
        }
        .bottomdiv{
 background-color:plum;
            color:purple;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 180px;

        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DATA ANALYTICS INNOVATIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
               <b><img src="amazon.png" ></b>
               
               
               </div>
              

               <img src="excel.png">
               

               <img src="aws.png">

               <img src="tableau.png">

               <img src="power.png">

               <img src="hadoop.png">

               

            </div>
        </div>
    </div>
    <div class="bottomdiv">
        <b>Designed and Developed by Santhiya (23013041)</b>
    </div>
</body>
</html>

person.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:purple;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:purple;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:purple;
text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 50px;
            padding-bottom: 10px;
            text-align: center;
            color:plum;
        }
        .bottomdiv{
            background-color:plum;
            color:purple;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 130px;

        }
        img{
            border-radius: 50%;
            width: 190px;
            display: inline;
            padding:3px;     
        }
        .person{
            margin:100px;
            text-align: center;
        }
        b,p{
            color:lightpink;
            text-align: center;
        }
        c{
            color:purple;
            text-align: center;
        }
</style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DATA ANALYTICS INNOVATIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="mypic1.jpg" class="MyPic">
                </td>
                <td>
                    <img src="robert.jpeg" class="Robert downey">
                </td>
                <td>
                   <img src="evans.jpeg" class="Chris evans">
                </td>
                <td>
                    <img src="hemsworth.jpeg" class="Chris hemsworth">
                </td>
                <td>
                    <img src="tom.jpeg" class="Tom holland">
                </td>
            </tr>
            <tr>
                <td>
                    <b>Santhiya</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>Robert Downey</b>
                    <p>CEO,Co-Founde</p>
                </td>
                <td>
                    <b>Chris Evans</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Chris hemsworth</b>
                    <p>CEODirector</p>
                </td>
                <td>
                    <b>Tom Holland</b>
                    <p>Asst.Director</p>
                </td>
              
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<c>Designed and Developed by Santhiya (23013041)</c>
    </div>
</body>
</html>

contactus.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Contactus</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:purple;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:black;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:plum;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:lightpink;
        }
        .table1{
            color:white;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color: lightpink;
        }
        .table2{
            color:purple;
            font-size: large;
            background-color:plum;
            border-radius: 5px;
            border-style:dotted;
            border-color: plum;
        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:plum;
            color:purple;
            text-align: center;
            position:relative;
display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="webcover2.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DATA ANALYTICS INNOVATIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="Products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        Asian Garderns,Door No:309,2nd-Floor,253A/108, M.T.H Road, Villivakkam,Chennai-600049. 
</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        near padiflyover, next to sidco bus stop.
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        Data analytics innovation@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9786278993
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: white; color: purple;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p><b>Designed and Developed by Santhiya (23013041)</b></p>
        </div>
    </div>
</body>
</html>
```
## OUTPUT:
![Alt text](<Screenshot (147).png>)
![Alt text](<Screenshot (148).png>)
![Alt text](<Screenshot (149).png>)
![Alt text](<Screenshot (150).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
