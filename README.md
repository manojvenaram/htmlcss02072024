## home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">Titan </h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="product.html">PRODUCT</a></li>
                    <li><a href="people.html">PEOPLE</a></li>
                    <li><a href="contactus.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Type To text">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div> 
        <div class="content">
            <h1>Driving progress through<br><span>precision engineering and</span> <br>boundless creativity.</h1>
            <br>
            <br>
                <button class="cn"><a href="#">LOG IN</a></button>
                <button class="cn"><a href="#">SIGN IN</a></button>

        </div>
    </div>
    <footer class="footer">
        <p>DESIGNED AND DEVELOPED BY MANOJ CHOUDHARY V</p>
    </footer>
</body>
</html>
```
## product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Products - Titan</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* Basic styling - feel free to customize */
        body {
            font-family: sans-serif;
            margin: 0;
        }
        .main {
            text-align: center;
        }
        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .product {
            margin: 20px;
            width: 300px; /* Adjust as needed */
            text-align: center;
            border: 1px solid #ccc;
            padding: 15px;
            border-radius: 5px;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">Titan</h2>
            </div>
            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="product.html">PRODUCT</a></li>
                    <li><a href="people.html">PEOPLE</a></li>
                    <li><a href="contactus.html">CONTACT</a></li>
                </ul>
            </div>
            <div class="search">
                <input class="srch" type="search" name="" placeholder="Type To text">
                <a href="#"><button class="btn">Search</button></a>
            </div>
        </div> 
        <div class="content">
            <h1>Our Products</h1>
            <p>Discover the innovative products we create at Titan.</p>

            <div class="product-container">
                <div class="product">
                    <img src="p1.png" alt="Solar Watch"> 
                    <h3>SolarPulse Watch</h3>
                    <p>Never change a battery again! This stylish watch is powered by the sun.</p>
                    <a href="#" class="btn">Learn More</a> 
                </div>
                <div class="product">
                    <img src="p2.png" alt="Smart Backpack"> 
                    <h3>TitanPack Pro</h3>
                    <p>The ultimate travel companion! Features built-in charging, anti-theft tech, and smart storage.</p>
                    <a href="#" class="btn">Learn More</a>
                </div>
                <div class="product">
                    <img src="p3.png" alt="Augmented Reality Glasses"> 
                    <h3>TitanVision</h3>
                    <p>Experience augmented reality like never before. Lightweight and stylish glasses for work or play.</p>
                    <a href="#" class="btn">Learn More</a>
                </div>
                <div class="product">
                    <img src="p4.png" alt="Home AI Assistant"> 
                    <h3>TitanHome Hub</h3>
                    <p>Control your smart home, make calls, and more with our intuitive AI assistant.</p>
                    <a href="#" class="btn">Learn More</a>
                    <br>
                    
                </div>
            </div>

        </div>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>

    </div>
    <footer class="footer">
        <p>DESIGNED AND DEVELOPED BY MANOJ CHOUDHARY V</p>
    </footer>
</body>
</html>
```
## people.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>People - Titan</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* Basic styling - feel free to customize */
        body {
            font-family: sans-serif;
            margin: 0;
        }
        .main {
            text-align: center;
        }
        .people-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .person {
            margin: 20px;
            text-align: center;
        }
        .person img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">Titan</h2>
            </div>
            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="product.html">PRODUCT</a></li>
                    <li><a href="people.html">PEOPLE</a></li>
                    <li><a href="contactus.html">CONTACT</a></li>
                </ul>
            </div>
            <div class="search">
                <input class="srch" type="search" name="" placeholder="Type To text">
                <a href="#"><button class="btn">Search</button></a>
            </div>
        </div> 
        <div class="content">
            <h1>Our People</h1>
            <p>Meet the talented individuals behind Titan's success.</p>

            <div class="people-container">
                <div class="person">
                    <img src="11.png" alt="Person 1"> 
                    <h3>John Doe</h3>
                    <p>CEO & Founder</p>
                    <p>A visionary leader with a passion for innovation.</p>
                </div>
                <div class="person">
                    <img src="22.png" alt="Person 2"> 
                    <h3>Jane Smith</h3>
                    <p>Lead Designer</p>
                    <p>Creative mind behind Titan's stunning designs.</p>
                </div>
                <div class="person">
                    <img src="33.png" alt="Person 3"> 
                    <h3>David Lee</h3>
                    <p>Head of Engineering</p>
                    <p>Building the technology that powers Titan's products.</p>
                </div>
                <div class="person">
                    <img src="44.png" alt="Person 4"> 
                    <h3>Sarah Jones</h3>
                    <p>Marketing Director</p>
                    <p>Connecting with customers and sharing Titan's story.</p>
                </div>
            </div>

        </div>
    </div>
    <footer class="footer">
        <p>DESIGNED AND DEVELOPED BY MANOJ CHOUDHARY V</p>
    </footer>
</body>
</html>
```
## contactus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Contact Us - Titan</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">Titan</h2>
            </div>
            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="product.html">PRODUCT</a></li>
                    <li><a href="people.html">PEOPLE</a></li>
                    <li><a href="contactus.html">CONTACT</a></li>
                </ul>
            </div>
            <div class="search">
                <input class="srch" type="search" name="" placeholder="Type To text">
                <a href="#"><button class="btn">Search</button></a>
            </div>
        </div> 
        <div class="content">
            <h1>Contact Us</h1>
            <p>We'd love to hear from you! Reach out to us through the following methods:</p>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name"><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message"></textarea><br>
                <button type="submit" class="btn">Submit</button>
            </form>
        </div>
    </div>
    <footer class="footer">
        <p>DESIGNED AND DEVELOPED BY MANOJ CHOUDHARY V</p>
    </footer>
</body>
</html>
```
## Output:

![image](https://github.com/manojvenaram/htmlcss02072024/assets/94165064/2e2b4920-730c-46a3-9d81-f3d3215bb40d)

![image](https://github.com/manojvenaram/htmlcss02072024/assets/94165064/74b3d67c-0f42-4ee9-be40-f36d3d1b1909)

![image](https://github.com/manojvenaram/htmlcss02072024/assets/94165064/b4b6d28a-0e01-4d42-aefd-5f5863c7b9c8)

![image](https://github.com/manojvenaram/htmlcss02072024/assets/94165064/93dabbab-0fb8-44a4-8863-c1595dd15418)


