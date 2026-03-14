# Ex.06 Restaurant Website
## Date:14.03.2026

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
Publish the website in Localhost.

## PROGRAM:
home.html
```
<html>
    <head>
    <title>Restaurant</title>
    </head>
    <link rel="stylesheet" href="design.css">
    <body>
        <div class="background">
          <nav>
            <div class="pages">
                <a href="home.html">home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="contact.html">Contact Us</a>
            </div>
        </nav>
         <div class="Header">
            <h1>Modern kitchen</h1>
            <i>
                         <h2>"Please your eyes, feed your soul" </h2>
            </i>

         </div>
         <div class="pictures">
            <img src="wa1.jpeg" width="400" height="300">
         </div>
         <div class="picture">
            <img src="p2.jpeg" width="400" height="300">
         </div>
         <div class="footer">
            Created by vahini-25018547
         </div>
         </div>
    </body>
</html>

design.css

.background
{
    background-image:url(wa.jpeg);
    width: 100%;
    height: 100%;
    background-repeat: no-repeat;
    background-size: cover;

}
nav 
{
    background-color:lavender;
    padding: 10px 90px;
    position:fixed;
    left:0;
    top:0;
    width:100%;
}
nav a
{
    color:rgb(71, 13, 206);
    margin:25px;
}
nav a:hover 
{
    color: rgb(66, 213, 83);
}
.Header
{
   text-align: center;
   padding: 10px;
   color:black;
   font-size: large;
}
.pictures
{
   
    border: solid 4px black;
    border-radius: 5px;
    position:absolute;
    left:200px;
    bottom:200px 
}
.picture
{
    border: solid 4px black;
    border-radius: 5px;
    position:absolute;
    right:200px;
    bottom:200px 
}

.footer
{
    left:0;
    bottom:0;
    position:fixed;
    background:rgb(36, 22, 9);
    color:white;
    width:100%;
    text-align:center;
    padding: 10px;
}


menu.html
<html>
    <head>
        <title>menu</title>
        <link href="menu.css" rel="stylesheet">
    </head>

    <body>
        <div class="background">
            <nav>
            <div class="pages">
                <a href="home.html">home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="contact.html">Contact Us</a>
            </div>
        </nav>
        <div class="intro">
            <B>
                Our exclusive Menu
            </B>
            <I>
                “Elevating your taste buds, one bite at a time.”
            </I>
                </div>
                <div class="container1">
                    <div class="container2">
                        <div class="image">
                            <img src="sandwich.jpeg" width="180" height="140">
                        </div>
                        <div class="name">
                            sandwich
                        </div>
                        <div class="details">
                            Air Fryer Chicken Avocado Sandwich, chicken, creamy ...!
                        </div>
                        <div class="price">
                            <h3>Rs.120/-</h3>
                        </div>
                </div>
                <div class="container1">
                    <div class="container2">
                        <div class="image">
                            <img src="burger.jpeg" width="180" height="140">
                        </div>
                        <div class="name">
                            Chicken Burger
                        </div>
                        <div class="details">
                              This burger comes with the entire works - lettuce, tomato and cheese!
                        </div>
                        <div class="price">
                            <h3>Rs.240/-</h3>
                        </div>
                </div>
                <div class="container1">
                    <div class="container2">
                        <div class="image">
                            <img src="pizza.jpeg" width="180" height="140">
                        </div>
                        <div class="name">
                            Cheesy pizza
                        </div>
                        <div class="details">
                             Hot and fresh pizza covered with creamy melted cheese.
                        </div>
                        <div class="price">
                            <h3>Rs.349/-</h3>
                        </div>
                </div>
                <div class="container1">
                    <div class="container2">
                        <div class="image">
                            <img src="shawarma.jpeg" width="180" height="140">
                        </div>
                        <div class="name">
                             shawarma
                        </div>
                        <div class="details">
                              A warm shawarma roll with spiced chicken and fresh salad.
                        </div>
                        <div class="price">
                            <h3>Rs.220/-</h3>
                        </div>
                </div>
                <div class="container1">
                    <div class="container2">
                        <div class="image">
                            <img src="pasta.jpeg" width="180" height="140">
                        </div>
                        <div class="name">
                            creamy pasta
                        </div>
                        <div class="details">
                              Delicious pasta mixed with smooth creamy sauce and herbs.
                        </div>
                        <div class="price">
                            <h3>Rs.199/-</h3>
                        </div>
                </div>
                <div class="footer">
                  Created by vahini-25018547
         </div>
        </div>
    </body>
</html>

menu.css
.background
{
    background-image: url(webapp.jpeg);
    width:100%;
    height:100%;
    background-repeat: no-repeat;
    background-size: cover;

}
nav 
{
    background-color:rgb(222, 239, 177);
    padding: 10px 90px;
    position:fixed;
    left:0;
    top:0;
    width:100%;
}
nav a
{
    color:black;
    margin:20px;
}
nav a:hover 
{
    color: rgb(193, 148, 45);
}

.intro B
{
    position:absolute;
    color:black;
    top:70px;
    left:600px;
    font-weight: bold;
    font-size: 30;
    
}
.intro I
{
    position:relative;
    color:rgb(12, 24, 195);
    top:140px;
    font-size:24px;
    font-weight: bold;
    width:500px;
    left:500px;
    text-align: center;
    
    
}
.container1
{
    display:flex;
    gap:15px;
    
}
.container2
{
    display:flex;
    flex-direction: column;
    border:5px rgb(182, 111, 111) solid;
    background:black;
    margin-top:250px;
    margin-left:150px;
    width:180px;
    height:320px;
}
.name
{
    text-align:center;
    font-weight: bolder;
    font-size:20px;
    padding: 20px;
    color:rgb(216, 209, 18);
}
.details
{
    text-align:center;
    font-style: italic;
    font-size:17px;
    color:white;
     color:aquamarine;
}
.price
{
    text-align:center;
    padding:10x;
    color:white;
    color:rgb(211, 17, 172);
}

.footer
{
    left:0;
    bottom:0;
    position:fixed;
    background:rgb(36, 22, 9);
    color:white;
    width:100%;
    text-align:center;
    padding:10px;
}



admin.html
<html>
    <head>
    <title>admin</title>
    <link href="admin.css" rel="stylesheet">
    </head>
    <body>
         <div class="background">
            <nav>
            <div class="pages">
                <a href="home.html">home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="contact.html">Contact Us</a>
            </div>
        </nav>
        <div class="Team">
            <b> ....Our Administrartion Team...</b>
        </div>
        <div class="container1">
                    <div class="container2">
                        <div class="image">
                            <img src="author.jpeg" width="180" height="160">
                        </div>
                        <div class="name">
                            Vahini
                        </div>
                        <div class="details">
                            CEO
                        </div>    
                        </div> 
                        <div class="container1">
                    <div class="container2">
                        <div class="image">
                            <img src="vijay.jpeg" width="180" height="160">
                        </div>
                        <div class="name">
                               Vijay
                        </div>
                        <div class="details">
                            Chief Administrator
                        </div>    
                        </div> 
                        <div class="container2">
                        <div class="image">
                            <img src="ashwin.jpeg" width="180" height="160">
                        </div>
                        <div class="name">
                            Ashwin
                        </div>
                        <div class="details">
                             stock Manager
                        </div>    
                        </div> 
                        <div class="container2">
                        <div class="image">
                            <img src="dulquer.jpeg" width="180" height="140">
                        </div>
                        <div class="name">
                              Dulquer  
                        </div>
                        <div class="details">
                         Manager          
                        </div>    
                        </div> 
                        <div class="container2">
                        <div class="image">
                            <img src="ajith.jpeg" width="180" height="140">
                        </div>
                        <div class="name">
                            Ajith
                        </div>
                        <div class="details">
                            salary officer
                        </div>    
                        </div>
                        <div class="footer">
                  Created by vahini-25018547
                        </div>
        </div>
    </body>
</html>

admin.css
.background
{
    background-image:url(ap.jpeg);
    width:100%;
    height:100%;
     background-repeat: no-repeat;
    background-size: cover;

}

nav 
{
    background-color:rgb(222, 239, 177);
    padding: 10px 90px;
    position:fixed;
    left:0;
    top:0;
    width:100%;
}
nav a
{
    color:black;
    margin:20px;
}
nav a:hover 
{
    color: rgb(193, 148, 45);
}
.team
{
    font-style: italic;
    text-align: center;
    top:70px;
    left: 550;
    font-size: 40;
    position: absolute;
    color:white;
}
.container1
{
    display:flex;
    gap:15px;
    
}
.container2
{
    display:flex;
    flex-direction: column;
    border-radius:7px 7px;
    background:rgb(118, 159, 171);
    margin-top:250px;
    margin-left:150px;
    width:180px;
    height:250px;
}
.image
{
    border-radius: 12px solid white;

}
.name
{
    text-align:center;
    font-weight: bolder;
    font-size:20px;
    padding: 20px;
    color:rgb(216, 209, 18);
}
.details
{
    text-align:center;
    font-style: italic;
    font-size:17px;
     color:aquamarine;
}
.footer
{
    left:0;
    bottom:0;
    position:fixed;
    background:rgb(36, 22, 9);
    color:white;
    width:100%;
    text-align:center;
    padding:10px;
}

contact.html
<html>
    <head>
        <title>contact us</title>
        <link href="contact.css" rel="stylesheet">
    </head>
     <body>
        <div class="background">
             <nav>
            <div class="pages">
                <a href="home.html">home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="contact.html">Contact Us</a>
            </div>
        </nav>
        <div class="contact">
             visit on:
             </div>
             <div class="add">
              Modern kitchen,<br>
              472,george street,<br>
              Guindy,<br>
              Chennai.
              </div>
        <div class="deleivery">
            for online deleivery:
            </div>
            <div class="app">
             visit ou app <span>Modernkitchen app</span><br>
             Fastest deleivery.<br>
             Free deleivery charges.
        </div>
        <div class="details">
            For further details:
        </div>
        <div class="phone">
            Phone:+91 8888999555.<br>
            Email:fantasticfood@gmail.com.<br>
        </div>
        <div class="quotes">
            <i>
                "!...come and enjoy...!"
            </i>
        </div>
        <div class="footer">
                  Created by vahini-25018547
         </div>
        </div>
     </body>
</html>

contact.css
.background
{
    background-image:url(contact.jpeg);
    width:100%;
    height:100%;
     background-repeat: no-repeat;
    background-size: cover;

}
nav 
{
    background-color:rgb(222, 239, 177);
    padding: 10px 90px;
    position:fixed;
    left:0;
    top:0;
    width:100%;
}
nav a
{
    color:black;
    margin:20px;
}
nav a:hover 
{
    color: rgb(193, 148, 45);
}
.contact
{
    top:100px;
    position: absolute;
    font-weight:bolder;
    left:300px;
    font-size:30;
    color: rgb(215, 133, 70);
    text-decoration: underline 2px;
    
}
.add
{
    font-size: 20;
    text-decoration: none;
    position: absolute;
    left:300px;
    font-weight:bolder;
    top:150px;
    color:rgb(221, 221, 239);
}
span
{
    color:yellow;
}
.deleivery
{
    top:260px;
    position: absolute;
    font-weight:bolder;
    left:300px;
    font-size:30;
    color: rgb(215, 133, 70);
    text-decoration: underline 2px;
    

}
.app
{
     font-size: 20;
    text-decoration: none;
    position: absolute;
    left:300px;
    font-weight:bolder;
    top:310px;
    color:rgb(241, 240, 237);
}
.details
{
    top:390px;
    position: absolute;
    font-weight:bolder;
    left:300px;
    font-size:30;
    color: rgb(215, 133, 70);
    text-decoration: underline 2px;
    

}
.phone
{
     font-size: 20;
    text-decoration: none;
    position: absolute;
    left:300px;
    font-weight:bolder;
    top:430px;
    color:rgb(241, 240, 237);
}
.quotes
{
    position: absolute;
    left:270px;
    top:550px;
    font-weight:bolder;
    font-size: 35;
    color:rgb(175, 11, 101);
}

.footer
{
    left:0;
    bottom:0;
    position:fixed;
    background:rgb(36, 22, 9);
    color:white;
    width:100%;
    text-align:center;
    padding:10px;
}


```

## OUTPUT:
![alt text](<Screenshot (71).png>)
![alt text](<Screenshot (72).png>)
![alt text](<Screenshot (73).png>)
![alt text](<Screenshot (74).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
