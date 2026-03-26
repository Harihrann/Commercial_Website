# Ex02 Commercial Website
## Date: 25/03/2026

```
NAME : HARIHARAN
REG NO : 212224040101
```

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

# 💻 PROGRAM

## 📄 index.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HARIHARAN's Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header class="header">
    <h1>HARI SHOP</h1>
    <nav class="navbar">
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <a href="#account">Account</a>
    </nav>
</header>

<section id="home" class="home">
    <div class="home-text">
        <h2>Welcome to HARI'S Firearm Shop</h2>
        <p> AN ONLINE STORE FOR YOUR CONVIENCE TO BUY FIREARMS </p>
        <button>FIRE IT UP Now</button>
    </div>
</section>

<section id="products" class="products">
    <h2>Our Products</h2>
    <div class="product-container">
        <div class="card">
            <img src="https://unsplash.com/photos/a-revolver-on-the-wooden-table-copy-space-m8qBima7jvA">
            <h3>GRENADE</h3>
            <p>₹20,999</p>
        </div>

        <div class="card">
            <img src="https://picsum.photos/300?2">
            <h3>Rocket launcher</h3>
            <p>₹10999</p>
        </div>

        <div class="card">
            <img src="https://picsum.photos/300?3">
            <h3>pistol</h3>
            <p>₹20,499</p>
        </div>

        <div class="card">
            <img src="https://picsum.photos/300?4">
            <h3>AK47</h3>
            <p>₹14,999</p>
        </div>
    </div>
</section>
<section id="account" class="account">
    <h2>User Login</h2>
    <input type="text" placeholder="Username">
    <input type="password" placeholder="Password">
    <button>Login</button>
</section>


<section id="about" class="about">
    <h2>About Us</h2>
    <p> Hari Firearms is a dedicated firearm retail store committed to providing high-quality, reliable equipment for responsible owners. We offer a carefully curated selection of firearms, ammunition, and accessories, ensuring every product meets strict standards of safety and performance.</p>
</section>

<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: hariffirearms@gmail.com</p>
    <p>Phone: +91 8925747264</p>
</section>



<footer class="footer">
    <p>Follow Us</p>
    <div class="social">
        <a href="#">Facebook</a>
        <a href="#">Instagram</a>
        <a href="#">Twitter</a>
    </div>
    <p>© 2026 RK Shop. All Rights Reserved.</p>
</footer>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f5f5f5;
}

.header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 60px;
    background:#111;
    color:white;
}

.navbar a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    font-size:18px;
    transition:0.3s;
}

.navbar a:hover{
    color:orange;
}

.home{
    height:90vh;
    background-image: url("grenade.jpeg") ;
    background-position: center;
    background-size: cover;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.home-text{
    background:rgba(0,0,0,0.6);
    padding:40px;
    border-radius:10px;
}

.home button{
    margin-top:15px;
    padding:12px 30px;
    background:orange;
    border:none;
    font-size:18px;
    cursor:pointer;
    border-radius:5px;
}

.home button:hover{
    background:red;
}

.products{
    padding:60px;
    text-align:center;
}

.product-container{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
    margin-top:30px;
}

.card{
    width:250px;
    background:white;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 0 15px rgba(0,0,0,0.2);
    transition:0.3s;
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.card:hover{
    transform:translateY(-10px);
}

.about,.contact,.account{
    padding:60px;
    text-align:center;
}

.account input{
    padding:12px;
    width:250px;
    margin:10px;
    border-radius:5px;
    border:1px solid gray;
}

.account button{
    padding:12px 25px;
    background:green;
    border:none;
    color:white;
    border-radius:5px;
}

.footer{
    background:#111;
    color:white;
    text-align:center;
    padding:30px;
}

.social a{
    color:orange;
    margin:10px;
    text-decoration:none;
}

</style>

</body>
</html>

```



## OUTPUT

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/7251c776-fd34-48fc-af81-f37e1e0cfbc8" />


<img width="1913" height="1199" alt="image" src="https://github.com/user-attachments/assets/6958ca87-e372-4e20-ad0d-82b032a77596" />




## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
