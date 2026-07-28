# Ex02 Commercial Website
## Date:

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
index.html
```
<html>
<head>
    <title>Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="border">
        <p>Restaurant</p>
    </div>
    <div class="welcome">
        Welcome to our Restaurant
    </div>
    <div class="menu">
        <div class="card">
            <div class="image"><img src="image/65.jpg"></div>
            <h2>Chicken 65</h2>
            <p>Crispy, spicy fried chicken bites tossed with bold South Indian seasonings..</p>
            <h3>₹100</h3>
        </div>
        <div class="card">
            <div class="image"><img src="image/Biriyani.jpg"></div>
            <h2>Chicken Biriyani</h2>
            <p>Fragrant basmati rice layered with tender chicken and aromatic spices for a rich, flavorful meal</p>
            <h3>₹130</h3>
        </div>
        <div class="card">
            <div class="image"><img src="image/Dosa.jpg"></div>
            <h2>Dosa</h2>
            <p>A thin, crispy South Indian rice and lentil crepe served fresh and golden brown.</p>
            <h3>₹40</h3>
        </div>
        <div class="card">
            <div class="image"><img src="image/Fried.jpg"></div>
            <h2>Fried Rice</h2>
            <p>Wok-tossed rice mixed with fresh vegetables and savory seasonings for a satisfying dish.</p>
            <h3>₹120</h3>
        </div>
    </div>
</body>
</html>
```
style.css
```
body{
    margin:0;
    padding:0;
    background:#f5f5f5;
    font-family:Arial, sans-serif;
}

.border{
    width:100%;
    height:70px;
    background:#3498db;
    display:flex;
    align-items:center;
    box-shadow:0 5px 5px rgba(0,0,0,0.2);
}

.border p{
    color:white;
    font-size:28px;
    font-style:italic;
    margin-left:20px;
}

.welcome{
    text-align:center;
    font-size:35px;
    color:chocolate;
    margin:40px 0;
    font-weight:bold;
}

.menu{
    width:90%;
    margin:auto;
    display:flex;
    justify-content:space-evenly;
    align-items:flex-start;
    flex-wrap:wrap;
    gap:30px;
    padding-bottom:40px;
}

.card{
    width:300px;
    background:white;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,0.2);
    text-align:center;
    padding:20px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.image{
    width:100%;
    height:220px;
    border-radius:8px;
    overflow:hidden;
    border:2px solid #ddd;
}

.image img{
    width:100%;
    height:100%;
    object-fit:cover;
}

.card h2{
    margin:15px 0 10px;
}

.card p{
    color:#666;
    line-height:1.5;
}

.card h3{
    color:#3498db;
    margin-top:15px;
}

@media (max-width:700px){
    .menu{
        flex-direction:column;
        align-items:center;
    }

    .card{
        width:90%;
    }
}
```



## OUTPUT
<img width="1919" height="878" alt="image" src="https://github.com/user-attachments/assets/ca54eb15-3506-4f22-9bee-d933083da055" />
<img width="1919" height="648" alt="image" src="https://github.com/user-attachments/assets/d6eae29b-3c8e-44e3-a8f7-a835cb4fccae" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
