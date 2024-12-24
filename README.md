# Ex.07 Restaurant Website
## Date:24.12.2024

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
Publish the website in the given URL.

## PROGRAM:
Homepage
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>The Dough Drop</title>
</head>
<body>
    <header>
        <div class="container">
             <h1 class="logo">The Dough Drop</h1>
             <nav>
                <ul class="nav-list">
            <li><a href="menu.html">Menu</a></li>
            <li><a href="admin.html">Admin</a></li>
            <li><a href="contact.html">Contact</a></li>
            
        </ul></nav>
    </div>
                
    
                <img src="restuarent/logo.png" alt="Bakery Logo" class="logo-img">
               
            </div>
        </header>
        <section class="hero">
            <div class="hero-section">
                <h2>Welcome to The Dough Drop bakery</h2>
                <h1>where a slice of heaven is available for all!!</h1>
                <form action="#" class="search-box">
                    <input type="text" placeholder="Search Pastry">
                    <button type="submit">Search</button>
      
                </section>
</body>
</html>
```
Menu
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>The Dough Drop</title>
</head>
<body>
    <header>
        <div class="container">
             <h1 class="logo">The Dough Drop</h1>
             <nav>
                <ul class="nav-list">
                  <li><a href="menu.html">Menu</a></li>
            <li><a href="admin.html">Admin</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="home.html">Home</a></li>

                </ul> </nav>
                
    
                <img src="restuarent/logo.png" alt="Bakery Logo" class="logo-img">
               
            </div>
        </header>
 
</section>
<section class="menu">
<h1>Featured Dough Softies</h1>
<div class="menu-section">
    <div class="menu-card">
        <img src="restuarent/balckcurrent muffin.jpeg" alt="">
        <h2>Lavender Muffin</h2>
        <p>A delightful blend of delicate lavender
         and a hint of vanilla, baked into a moist,
          fluffy muffin.</p>
          <a href="#">ORDER NOW</a>
          </div>
    <div class="menu-card">
            <img src="restuarent/macaron.jpeg" alt="">
            <h2>Macarons</h2>
            <p>A colorful selection of our signature macarons, each
             handcrafted & filled with luscious flavors.</p>
              <a href="#">ORDER NOW</a>
              </div>
              <div class="menu-card">
                
                <img src="restuarent/choco bread.jpeg" alt="">
                <h2>Choco-Pastry</h2>
                <p>A chocolate lover's dream—layers of rich,
                 velvety chocolate ganache nestled in a delicate pastry.</p>
                  <a href="#">ORDER NOW</a>
                  </div>
                  <div class="menu-card">
                    <img src="restuarent/croissant.jpeg" alt="">
                    <h2>Croissant</h2>
                    <p>Golden, flaky & buttery perfection of classic
                     French pastry delicate layers that melt in your mouth.</p>
                      <a href="#">ORDER NOW</a>
                      </div>
                      <div class="menu-card">
                        <img src="restuarent/choco muffin.jpeg" alt="">
                        <h2>Choco-Muffin</h2>
                        <p>A rich, moist muffin bursting with deep chocolate flavor,
                         studded with chunks of premium chocolate.</p>
                          <a href="#">ORDER NOW</a>
                          </div>
                          <div class="menu-card">
                            <img src="restuarent/strawberry cupcake.jpeg" alt="">
                            <h2>Strawberry Muffin</h2>
                            <p>A soft and fluffy muffin loaded with 
                            juicy strawberry pieces, baked to perfection. </p>
                              <a href="#">ORDER NOW</a>

          </div>
        </body>
    </html>
```
Admin
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>The Dough Drop</title>
</head>
<body>
    <header>
        <div class="container">
             <h1 class="logo">The Dough Drop</h1>
             <nav>
                <ul class="nav-list">
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="admin.html">Admin</a></li>
                    <li><a href="contact.html">Contact</a></li>
            <li><a href="home.html">Home</a></li>
        
                </ul> </nav>
                
    
                <img src="restuarent/logo.png" alt="Bakery Logo" class="logo-img">
               
            </div>
        </header>
        <section class="admin">
            <h1>Our Heroes</h1>
            <div class="chef-section">
                <div class="admin-card">
                    <img src="restuarent/gordon ramsay.webp" alt="">
                    <h2>Gordon Ramsay</h2>
                    <p>The CEO of The Dough Drop & Senior chef.</p>
                      </div>
                      <div class="admin-card">
                        <img src="restuarent/curtis.jpeg" alt="">
                        <h2>Curtis Stone</h2>
                        <p>The Manger & master in pastry dishes.</p>
                          </div>
                          <div class="admin-card">
                            <img src="restuarent/dessert king.jpg" alt="">
                            <h2>Reynold</h2>
                            <p>The Dessert king with an experience of 10 years.</p>
                              </div>
                              <div class="admin-card">
                                <img src="restuarent/gary.jpg" alt="">
                                <h2>Gary</h2>
                                <p>The accounts manager and The head baker.</p>
                                  </div>
                                  <div class="admin-card">
                                    <img src="restuarent/bakey.jpg" alt="">
                                    <h2>Phoebe</h2>
                                    <p>The Finance manager and The decorative chef.</p>
                                      </div>
                                      </div></section>
                                      </body>
                                      </html>
```
Contact
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>The Dough Drop</title>
</head>
<body>
    <header>
        <div class="container">
             <h1 class="logo">The Dough Drop</h1>
             <nav>
                <ul class="nav-list">
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="admin.html">Admin</a></li>
                    <li><a href="contact.html">Contact</a></li>
                    <li><a href="home.html">Home</a></li>

                </ul> </nav>
                
    
                <img src="restuarent/logo.png" alt="Bakery Logo" class="logo-img">
               
            </div>
        </header>
 
</section>
<section class="contact">
    <h1>Contact Us</h1>
    <div class="contact-section">
        <div class="contact-card">
            <h2>For futher queries,do reach out to us through</h2>
            <h2>Thedoughdrop@gmail.com or 
                through +10 98726 76533</h2>
            <p>Address:145 lake street,the parch road.
                we would be delighted to hear your queries and feedback.
            </p>
              <a href="#">Contact now</a>
              </div>
```
CSS
```

.header{
   margin: 80;
   padding: 80;
   box-sizing: border-box;
   font-family: sans-serif;
}

body{
   width: 90%;
   min-height: 100vh;
   background: #f8f8f8; 
}

header{
   height: 80px;
   width: 1500px;
   background: #5e0326;
   color: #f8f8f8;
   display: flex;
   align-items: center;
   
}
.container{
   width: 80%;
   margin:  auto;
   display: flex;
   align-items: center;
   background-position: center;
   justify-content: space-between;
}
nav ul li{
   list-style: none;
   display: inline;
   margin-right: 20px;
   font-weight: 600;
}
.logo-img {
   height: 75px;
   width: auto;
   margin-right: 8px;
}
.hero {
   width: 1300px;
   height:460px;
   background-image: url(restuarent/Delicious\ sweet\ macaroons\ and\ colorf.jpeg);
   background-repeat: no-repeat;
   background-position: cover;
   background-size: cover;
   background-color: #f8f8f8;
   text-align: center;
   font-family:'Merriweather',serif;
   padding: 100px; 
   margin-bottom: 20px;

}
.hero h2 {
   font-size: 36px;
   margin-bottom: 10px;

}
.hero h1{
   font-size: 20px;
   margin-bottom: 10px;
}
.search-box input{
   width: 35%;
   padding:9px;
   outline: none;
   border:0;
   border-radius: 5px  5px;
}
.search-box button{
   padding: 8px;
   outline: none;
   border:0;
   font-size: 1rem;
   border-radius: 5px 5px 5px 5px;
   cursor:pointer;
   background-color: rgb(242, 215, 180);
}

.menu{
   padding: 50 px 0;
}

.menu h1{ 
text-align: center;
margin-bottom: 35px;
font-size:30px;
}
.menu-section{
   width:85%;
   margin: 0 auto;
   display:grid;
   grid-template-columns: repeat(auto-fit, minmax(300px, 2fr));
   column-gap: 20px;
}
.menu-card{
   background: #f8f8f8;
   margin: 50px 10px;
   border-radius: 15px;
   border: 1px solid #ddc2c2;
   overflow: hidden;
   box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
.menu-card img{
   width:100%;
   height: 300px;
   object-fit: cover;

   
}
.menu-card h2{
   font-size:24px ;
   padding:20px;
   text-align: center;
}
.menu-card a{
   display: block;
   text-align: center;
   text-decoration: none;
   background: #5e0326;
   color:#f8f8f8;
   padding:15px 0;
   cursor: pointer;

}
.menu-card p{
   font-family:Arial, Helvetica, sans-serif;
   font-size: 15px;
   text-align: center;
}
.admin{
   padding: 50 px 0;
}

.admin h1{ 
text-align: center;
margin-bottom: 35px;
font-size:30px;
}
.chef-section{
   width:85%;
   margin: 0 auto;
   display:grid;
   grid-template-columns: repeat(auto-fit, minmax(300px, 2fr));
   column-gap: 20px;
}
.admin-card{
   background: #f8f8f8;
   margin: 50px 10px;
   border-radius: 15px;
   border: 1px solid #ddc2c2;
   overflow: hidden;
   box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
.admin-card img{
   width:100%;
   height: 300px;
   object-fit: cover;

   
}
.admin-card h2{
   font-size:24px ;
   padding:20px;
   text-align: center;
}

.admin-card p{
   font-family:Arial, Helvetica, sans-serif;
   font-size: 15px;
   text-align: center;
}
.contact{
   padding: 50 px 0;
}

.contact h1{ 
text-align: center;
margin-bottom: 35px;
font-size:30px;
}
.contact-section{
   width:85%;
   margin: 0 auto;
   display:grid;
   grid-template-columns: repeat(auto-fit, minmax(300px, 2fr));
   column-gap: 20px;
}
.contact-card{
   background: #f8f8f8;
   margin: 50px 10px;
   border-radius: 15px;
   border: 1px solid #ddc2c2;
   overflow: hidden;
   box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.contact-card h2{
   font-size:24px ;
   padding:20px;
   text-align: center;
}

.contact-card p{
   font-family:Arial, Helvetica, sans-serif;
   font-size: 15px;
   text-align: center;
}
.contact-card a{
   display: block;
   text-align: center;
   text-decoration: none;
   background: #5e0326;
   color:#f8f8f8;
   padding:15px 0;
   cursor: pointer;
}
```

## OUTPUT:
![alt text](<Screenshot 2024-12-24 222809.png>)
![alt text](<Screenshot 2024-12-24 222920.png>)
![alt text](<Screenshot 2024-12-24 222938.png>)
![alt text](<Screenshot 2024-12-24 223122.png>)
![alt text](<Screenshot 2024-12-24 223130.png>)
![alt text](<Screenshot 2024-12-24 223144.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
