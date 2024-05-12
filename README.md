# Ex.07 Software Product Company Website
## Date:12/05/2024

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
HOME.HTML
```
<!DOCTYPE html>

<html lang="en"> 
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(89, 221, 77);
            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(189, 49, 21);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(83, 87, 209);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgb(222, 33, 134);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:rgba(250, 215, 18, 0.49);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: yellow;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
	    .text h3 {
                color: white;
                font-weight: 800;
                font-size: 22px;
                letter-spacing: 3px;
            }
	
            .text p {
                color: white;
                text-transform: capitalize;
                font-size: 17px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
	
            }
                footer {
                background-color: rgb(16, 189, 91);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>Kalam Technologies</span></h1>
            <ul>
                <li><a href="Home.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2><span> SOFTWARE DEVELOPMENT </span></h2>
                <br>
		<h3></h3>
		<br>
                <p>We blend innovation with expertise to craft bespoke software that drives your success. From streamlined workflows to immersive user experiences, trust us to elevate your digital presence. Let's transform your ideas into reality. Elevate your software, elevate your business with us.</p>
                <br>
                
            </div>
        </div>  
    </div>
    <footer>
        <center> Copyright@2024 Developed by Sanjai S </center>
    </footer>
</body>
</html>
```
PERSON.HTML
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(128, 124, 0);
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(0, 208, 255);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(255, 0, 247);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: rgb(255, 255, 255);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:gold;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: white;
                position: relative;
                left: 200px;
            }
            .image table img {
                height: 250px;
                width: 250px;
                border: 2px solid yellow;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: rgb(255, 0, 0);
            }
            footer {
                background-color: gold;
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>Kalam Technologies</h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div> 
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="c:\Users\admin\Downloads\WhatsApp Image 2024-04-30 at 11.23.52.jpeg"> </td>
                    <td> <img src="c:\Users\admin\Downloads\WhatsApp Image 2024-05-08 at 08.05.33.jpeg"> </td>
                    <td> <img src="c:\Users\admin\Downloads\WhatsApp Image 2024-05-08 at 08.05.34 (1).jpeg"> </td>
                    <td> <img src="c:\Users\admin\Downloads\WhatsApp Image 2024-05-08 at 08.05.34.jpeg"> </td>
                    
                </tr>
                <tr align="center">
                    <th>Ameesha Jeffi J</th>
                    <th>Surya </th>
                    <th>Sanjai Ramasamy</th>
                    <th>Gopinath </th>
                   
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> Co-Founder </td>
                    <td> Managing Director </td>
                    <td> Director </td>
                    
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by Sanjai  </center>
    </footer>
</body>
</html>
```
CONTACT.HTML
```
    <head>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(30, 171, 63);
            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(201, 162, 23);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(104, 104, 25);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgba(255, 217, 0, 0.764);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:rgba(255, 217, 0, 0.523);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid white;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid rgb(183, 162, 47);
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: white;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid white;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: white;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 15px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: white;
                border-radius: 30px;
                background: rgb(169, 150, 48);
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: white;
                position: relative;
                top: 50px;
                
                padding: 10px 80px;
            }
            .box-2 span {
                color: gold;
                font-size: 30px;
            }
            footer {
                background-color: rgb(207, 233, 38);
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span> Kalam Technology </span></h1>
            <ul>
                <li><a href="Home.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> <span>Contact Us </span></h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="30" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information</h2>
                <p><span> Address</span>: Tirunelveli District,TAMILNADU, 627105 </p>
                <p> <span>Email</span> : ameeshajeffi@gmail.com</p>
                <p> <span>Phone</span>: 123 456 7890 </p>
            </div>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by San`jai  </center>
    </footer>
</body>
</html>
```
## OUTPUT:
![328743995-e6ccdf71-fb62-4fc6-9087-8aaa777a5d52](https://github.com/ameeshajeffi/softweb/assets/150773598/648a7daf-4b9c-44ea-9795-a84bd16f8ca6)

![dc355094-857b-4100-9b54-3ab5aa8117ce](https://github.com/ameeshajeffi/softweb/assets/150773598/5db59355-60f1-424f-a9a7-e87e885ad7ef)

![4f8ea89e-cfda-44ba-a869-c4abcdcb9b1b](https://github.com/ameeshajeffi/softweb/assets/150773598/688727e1-cea1-4f99-9afa-e80aa834c0b1)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
