# Ex.06 Restaurant Website
## Date: 14/3/2026

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

```
home.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style.css">
    </head>

    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>

        <h1 class="title">JEGAN'S RESTAURANT</h1>

        <div class="container">
            <p>Jegan's premier dining experience awaits you! . Come experience the best cuisine at our restaurant.</p>

            <div class="row">
                <div class="image-box">
                    <img id="front" src="front1.jpg" alt="Restaurant">
                </div>
                <div class="image-box">
                    <img id="front" src="front2.jpg" alt="Restaurant">
                </div>
            </div>
        </div>

        <footer>
            <p>Designed by Jegan S K - 212225231007</p>
        </footer>
    </body>
</html>

menu.html

<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <nav>
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>

    <h1 class="title">MENU</h1>

    <div class="container">

        <div class="row">

            <div class="card">
                <div class="image-box"><img src="food1.jpg" alt="Naan"></div>
                <h3>Naan</h3>
                <p>&#8377; 199</p>
            </div>

            <div class="card">
                <div class="image-box"><img src="food2.jpg" alt="Parotah"></div>
                <h3>Parotah</h3>
                <p>&#8377; 149</p>
            </div>

            <div class="card">
                <div class="image-box"><img src="food3.jpg" alt="Biriyani"></div>
                <h3>Biriyani</h3>
                <p>&#8377; 299</p>
            </div>

            <div class="card">
                <div class="image-box"><img src="food4.jpg" alt="Juices"></div>
                <h3>Juices</h3>
                <p>&#8377; 99</p>
            </div>

        </div>

    </div>

    <footer>
        <p> Jegan S K - 212225231007</p>
    </footer>

</body>
</html>

admin.html

<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="style.css">
    </head>

    <body>

        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>

        <h1 class="title">ADMINISTRATION TEAM</h1>

        <div class="container">

            <div class="row">

                <div class="card">
                    <div class="circle"><img src="1.jpg" alt="Jegan S K"></div>
                    <h3>Jegan S K</h3>
                    <p>Founder & CEO</p>
                </div>

                <div class="card">
                    <div class="circle"><img src="admin1.jpg" alt="Ambani"></div>
                    <h3>Ambani</h3>
                    <p>Manager</p>
                </div>

                <div class="card">
                    <div class="circle"><img src="admin2.jpg" alt="Venkatesh Bhatt"></div>
                    <h3>Venkatesh Bhatt</h3>
                    <p>Chef</p>
                </div>

                <div class="card">
                    <div class="circle"><img src="admin3.jpg" alt="Elon Musk"></div>
                    <h3>Elon Musk</h3>
                    <p>Accountant</p>
                </div>

            </div>

        </div>

        <footer>
            <p> Jegan S K - 212225231007</p>
        </footer>

    </body>
</html>

contact.html

<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <nav>
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>

    <h1 class="title">CONTACT</h1>

    <div class="container">

        <h3>Address</h3>
        <p>No.83/54 , Monkey Street,hyderabad-500001,Italy</p>

        <h3>Phone</h3>
        <p>Book your seats @ 123-456-7890</p>

        <h3>Email</h3>
        <p>Suggestions @ jegan@example.com</p>

    </div>

    <footer>
        <p> Jegan S K - 212225231007</p>
    </footer>

</body>
</html>


style.css

body{
    margin:0;
    font-family:Arial, Helvetica, sans-serif;
    background-image: url('rest-back.jpg');
    background-size: cover;
    display:flex;
    flex-direction:column;
    min-height:100vh;
}

p{
    color:#1e1616;
    line-height:1.6;
}

nav{
    display:flex;
    justify-content:center;
    background:#d9d9d9;
    padding:15px;
}

nav a{
    margin:0 20px;
    text-decoration:none;
    color:purple;
    font-weight:bold;
}

nav a:hover{
    color:rgb(227, 27, 47);
}


.title{
    font-size:70px;
    color:#eb4040;
    margin-left:40px;
}


.container{
    width:90%;
    margin:auto;
}


.row{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
}


.card{
    width:200px;
    height:300px;
    border-radius:10px;
    background:#eb4040;
    margin:20px;
    text-align:center;
    padding:15px;
}


.circle img{
    width:120px;
    height:120px;
    border-radius:50%;
    background:lightgray;
    margin:auto;
}


.image-box img{
    width:100%;
    height:200px;
    justify-content: space-between;
    background:lightgray;
    border-radius:8px;
}

#front{
    height:400px;
    width:100%;
    border-radius:10px;
    justify-content: space-between;
}

footer{
    text-align:center;
    background-color: violet;
}
```

## OUTPUT:

![alt text](<Screenshot (121).png>) 

![alt text](<Screenshot (122).png>)

![alt text](<Screenshot (123).png>)

![alt text](<Screenshot (124).png>) 

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
