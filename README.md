# Ex.07 Restaurant Website
## Date: 15/05/205

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Foodie Delight</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #63b1c5;
      background-image: url('d:\bg.jpg');
      background-size: cover;
      background-attachment: fixed;
      background-repeat: no-repeat;
      color: #333;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #34495e;
      overflow: hidden;
    }
    nav a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #e74c3c;
    }
    .banner {
      background: url('d:\bg.jpg') no-repeat center center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 36px;
      font-weight: bold;
    }
    .content {
      padding: 20px;
      background-color: rgba(255, 255, 255, 0.9);
      margin: 10px;
      border-radius: 8px;
    }
    .menu-grid, .admin-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: white;
      padding: 15px;
      border: 1px solid #ccc;
      border-radius: 8px;
      text-align: center;
    }
    .card img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>VENKAT'S CORNER</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#admin">Administration</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <div class="banner" id="home">
    Welcome to VENKAT'S CORNER
  </div>

  <div class="content" id="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
      <div class="card"><img src="pizza.jpg" alt="Food 1" height="200px" width="200px"><p>Margherita Pizza</p></div>
      <div class="card"><img src="burger.jpg" alt="Food 2" height="200px"><p>Veggie Burger</p></div>
      <div class="card"><img src="sandwitch.jpg" alt="Food 3"><p>Grilled Sandwich</p></div>
      <div class="card"><img src="salad.jpg" alt="Food 4"><p>Caesar Salad</p></div>
      <div class="card"><img src="wings.jpg" alt="Food 5"><p>Chicken Wings</p></div>
      <div class="card"><img src="pasta.jpg" alt="Food 6"><p>Pasta Alfredo</p></div>
      <div class="card"><img src="rools.jpg" alt="Food 7"><p>Sushi Rolls</p></div>
      <div class="card"><img src="steak.jpg" alt="Food 8"><p>Steak</p></div>
      <div class="card"><img src="tacos.jpg" alt="Food 9"><p>Tacos</p></div>
      <div class="card"><img src="fish.jpg" alt="Food 10"><p>Fish & Chips</p></div>
      <div class="card"><img src="french.jpg" alt="Food 11"><p>French Fries</p></div>
      <div class="card"><img src="cake.jpg" alt="Food 12"><p>Chocolate Cake</p></div>
    </div>
  </div>

  <div class="content" id="admin">
    <h2>Administration</h2>
    <div class="admin-grid">
      <div class="card"><img src="001.jpg" alt="Admin 1"><p>VENKATESAN<br>CEO</p></div>
      <div class="card"><img src="JONES MACHAN.jpg" alt="Admin 2"><p>JONES<br>MANAGER</p></div>
      <div class="card"><img src="ARUN MAPLLA.jpg" alt="Admin 3"><p>ARUN<br>CHEF Head</p></div>
      <div class="card"><img src="KUNJI MACHAN.jpg" alt="Admin 4"><p>DHANUSH<br>Marketing Lead</p></div>
      <div class="card"><img src="JOHN POOL.jpg" alt="Admin 5"><p>JOHN<br>Finance Officer</p></div>
      <div class="card"><img src="DHARUN.jpg" alt="Admin 6"><p>DHARUN<br>Operations Head</p></div>
    </div>
  </div>

  <div class="content" id="contact">
    <h2>Contact Us</h2>
    <p>Address: 4th Avenue, Anna Nagar-Chennai</p>
    <p>Phone: 9360063682</p>
    <p>Email: venkatesanappu05@gmail.com</p>
  </div>

  <footer>
    <p>Website created by [VENKATESAN-R]</p>
  </footer>
</body>
</html>

```

## OUTPUT:
![Screenshot 2025-05-20 181251](https://github.com/user-attachments/assets/a96d0e6d-94de-4d89-9da2-59be17007a08)

![Screenshot 2025-05-20 181441](https://github.com/user-attachments/assets/3cc78744-af7f-4120-8e72-094f00bebb4d)

![Screenshot 2025-05-20 181453](https://github.com/user-attachments/assets/6d0ef0de-c9e4-44e0-b26b-ee03a7f0020f)

![Screenshot 2025-05-20 181538](https://github.com/user-attachments/assets/64cdedbe-7672-4f29-b887-c1312bfc1cec)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
