# Ex.07 Restaurant Website
## Date:10.10.2025

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
```
res.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <link rel="stylesheet" href="res.css">
</head>
<body>
    <h1 class="heading">Kuppanna Chinese Corner</h1>
    <div class="container">
        </div>
        <nav class="navbar">
            <ul class="nav-links">
                <li><a href="res.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
            
    </nav>
    <div class="image">
    </div>
    <div class="content">
        <h1 id="i">Welcome to Our Restaurant</h1>
        <p fontcolor="yellowgreen" align="center">Experience the best dining with us. We offer a variety of delicious dishes made from fresh ingredients.</p>
        <center>
        <a href="menu.html" class="btn">Explore Our Menu</a>
        </center>
        <h1 id="i">IJAS J (25007615)</h1>
        
    </div>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="res.css">
</head>
<body>
    <div class="con1">
        <h1>For more information</h1>
    </div>
    <div class="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 5A/125 kilambakkan new CMBT opposite 600021</p>
        <p><strong>Phone:</strong> +91 9655622371</p>
        <p><strong>Email:</strong> kuppanna@gmail.com</p>
      </div>
      <center>
        <a href="home.html" class="btn">Home Page</a>
      </center>
      
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin</title>
    <link rel="stylesheet" href="res.css">
</head>
<body>
    <div class="admin">
        <h1>Admins</h1>
        <br>
        <p class="para">Welcome to the admin page. Here you can manage the website content and settings.</p>
        <br>
        <div class="adm">
        <img src="authorphoto.jpg">
        <h4>Ijas J</h4>
          <p>CEO</p>
        </div>
        <div class="adm">
        <img src="kuppannaog.jpg">
         <h4>Kuppanna</h4>
          <p>Chief Operating Officer</p>
        </div>
        <div class="adm">
        <img src="micheal.jpg">
        <h4>Michael Lee</h4>
          <p>Head of Marketing</p>
        </div>
        <div class="adm">
        <img src="emily.jpg">
        <h4>Emily Davis</h4>
          <p>Lead Developer</p>
        </div>
        <div class="adm">
        <img src="david.jpg">
        <h4>David Wilson</h4>
          <p>Customer Support Manager</p>
        </div>
    </div>


</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="res.css">
</head>
<body bgcolor="#f5f5fa">
    <center><h1 id="d" style="color: #333;" font-weight="bold">Our Menu</h1>
    </center>
    <div class="out">
     <div class="menu-item">
         <img id="h" src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=500&q=80" alt="Margherita Pizza" />
          <h3>Margherita Pizza</h3>
          <p>Classic pizza with fresh tomatoes, mozzarella, and basil.</p>
     </div>
     <div class="menu-item">
          <img id ="h" src="SpaghettiCarbonara.png" alt="Spaghetti Carbonara" />
          <h3>Spaghetti Carbonara</h3>
          <p>Creamy pasta with pancetta and parmesan cheese.</p>
        </div>
        <div class="menu-item">
          <img id ="h" src="caesarsalad.png" alt="Caesar Salad" />
          <h3>Caesar Salad</h3>
          <p>Fresh romaine lettuce, croutons, and Caesar dressing.</p>
        </div>
        <div class="menu-item">
          <img id ="h"src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=500&q=80" alt="Grilled Steak" />
          <h3>Grilled Steak</h3>
          <p>Juicy steak grilled to perfection with herbs.</p>
        </div>
        <div class="menu-item">
          <img id ="h" src="https://images.unsplash.com/photo-1490645935967-10de6ba17061?auto=format&fit=crop&w=500&q=80" alt="Sushi Platter" />
          <h3>Sushi Platter</h3>
          <p>Assorted fresh sushi with wasabi and soy sauce.</p>
        </div>
        <div class="menu-item">
          <img id="h" src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=500&q=80" alt="Tacos" />
          <h3>Tacos</h3>
          <p>Soft corn tortillas filled with seasoned meats and veggies.</p>
        </div>
        <div class="menu-item">
          <img id ="h"src="https://images.unsplash.com/photo-1540189549336-e6e99c3679fe?auto=format&fit=crop&w=500&q=80" alt="Pancakes" />
          <h3>Pancakes</h3>
          <p>Fluffy pancakes topped with syrup and fresh berries.</p>
        </div>
        <div class="menu-item">
          <img id="h" src="vegetablestirfry.png" alt="Vegetable Stir Fry" />
          <h3>Vegetable Stir Fry</h3>
          <p>Fresh vegetables tossed in a savory sauce.</p>
        </div>
        <div class="menu-item">
          <img id="h" src="chesse burger.png" alt="Cheeseburger" />
          <h3>Cheeseburger</h3>
          <p>Grilled beef patty with cheese, lettuce, and tomato.</p>
        </div>
        <div class="menu-item">
          <img id="h" src="https://images.unsplash.com/photo-1551218808-94e220e084d2?auto=format&fit=crop&w=500&q=80" alt="Chocolate Cake" />
          <h3>Chocolate Cake</h3>
          <p>Rich chocolate cake layered with creamy frosting.</p>
        </div>
        <div class="menu-item">
          <img id="h" src="Fish and chips.png" alt="Fish & Chips" />
          <h3>Fish & Chips</h3>
          <p>Crispy fried fish with golden fries.</p>
        </div>
        <div class="menu-item">
          <img id="h" src="greeksalad.png" alt="Greek Salad" />
          <h3>Greek Salad</h3>
          <p>Cucumber, tomato, olives, feta cheese with dressing.</p>
        </div>
    </div>
    <a href="admin.html" class="btn">Admin Page</a>
</body>
</html>

res.css

*{
    margin: 0;
    padding: 0;
}
.nav-links
{
    display: flex;
    gap: 20px;
    font-size: 18px;
    color: white;
    font-family: 'Arial', sans-serif;
    font-weight: bold;
    align-items: center;
    background-color: #333;
    border-radius: 5px; 
    transition: background-color 0.3s;
    width:100%;
    height:80px;
    gap:40px;
    list-style: none;
    justify-content: right;

}
.nav-links li a {
    color: white;
    text-decoration: none;
    padding: 10px 15px 10px 15px;
    border-radius: 5px;
    transition: background-color 0.3s;
    margin-right: 70px;
}
.image
{
width:100%;
height:500px;  
border-radius: 20px;
background-image: url("kuppanna.jpg.png");
background-position: center;
background-repeat: no-repeat;
background-size: cover;
}
.menu-item
{
width:200px;
height:300px;
background-color:  #fff6f2;;
border-radius: 6px;
padding-bottom: 10px;
padding-top: 10px;

}
.menu-item p{
    font-size: small;
    text-align: center;
}
.menu-item img{
    
    height:200px;
    width:200px;
    object-fit: cover;
    border-radius: 6px;
}
.menu-item h3 {
    margin: 15px 0 8px;
   
    text-align: center;
}
.menu-item:hover {
    transform: translateY(-8px) scale(1.045);
    box-shadow: 0 8px 32px rgba(247, 90, 42, 0.14), 0 2px 12px rgba(34, 34, 34, 0.09);
}
.menu-item button:hover {
    background: #f75a2a;
}
.out
{
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    row-gap: 20px;
    column-gap: 10px;
    padding-left: 180px;
    padding-top: 100px;
    padding-right: 180px;
    padding-bottom: 50px;
    margin-top: 50px;
    
}
.contact
{
        max-width: 600px;
      margin: 50px auto;
      background: white;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      font-size: 1.1em;
      line-height: 1.5;
      color: #444;
        font-family: 'Arial', sans-serif;
        margin-top:150px;

}
contact:hover
{
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    background-color:  #2a4d69;
}
.con1
{
    font-style: italic;
    font-weight: bold;
    color: #333;
background-color:  #2a4d69;
    padding: 10px;
    border-radius: 5px;
    text-align: center;
    font-size: 1.2em;
    margin-bottom: 20px;
    opacity: 0.9;
}
.content p{
    font-size: 1.2em;
    margin: 20px 0;
    color: #555;
    line-height: 1.6;
}
#d h1{
    font-size: 2.5em;
    /* margin-bottom: 20px; */
    font-family: 'Arial', sans-serif;
    font-weight: bold;
}
.heading{
    background-color: #666;
    text-align: center;
    margin: 0;
}
#ad
{
    text-align: center;
    margin-top: 50px;
    font-size: 1.2em;
    color: #666;
    font-family: 'Arial', sans-serif;
    width: 200px;
    height: 300px;
    background-color: #fff6f2;
    border-radius: 10px;
}
.admin
{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    row-gap: 20px;
    column-gap: 10px;
    padding-left: 180px;
    width: 100%;
    height: 250vh;
    background-color: #f4f4f4;
    font-family: 'Arial', sans-serif;
}
.admin h1{
    text-align: center;
    margin-left:450px;
    font-family: 'Arial', sans-serif;
    font-weight: bold;
    color: #333;
    /* margin-bottom: 20px; */
    
}
.para{
    margin: 0 0 0 300px;
    /* text-align: center; */
    width: 100%;
}

.adm {
    background-color: #2a4d69;
    color: white;
    padding: 15px 25px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    width:400px;
    text-align: center;
}
.adm img{
    width: 400px;
    height: 400px;
}
#i
{
    background-color: grey;
    text-align: center;
    margin: none;
}
.btn{
    text-decoration: none;
    border: #2a4d69 3px dotted;
    margin: 0 0 20px 0;
}


```

## OUTPUT:

![alt text](<Screenshot 2025-10-10 143119.png>)
![alt text](<ijas/restapp/static/Screenshot 2025-10-08 213522.png>)
![alt text](<ijas/restapp/static/Screenshot 2025-10-08 213550.png>)
![alt text](<ijas/restapp/static/Screenshot 2025-10-08 213615.png>)
![alt text](<ijas/restapp/static/Screenshot 2025-10-08 213632.png>)
![alt text](<ijas/restapp/static/Screenshot 2025-10-08 213650.png>)
![alt text](<ijas/restapp/static/Screenshot 2025-10-08 213737.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
