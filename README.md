# Ex.07 Software Product Company Website
## Date:10/05/2024

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
home.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>RIZZTECH</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-color:rgb(206, 210, 219);
                background-size: cover;
                background-position: center;
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
                color:rgb(13, 195, 215);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(128, 18, 18);
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
                background:rgb(23, 19, 133);
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
                background-color:rgb(11, 116, 20);
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
                color: rgb(143, 125, 19);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid rgb(141, 156, 143);
                padding: 13px 35px;
                letter-spacing: 1px;
                color:black;
                border-radius: 30px;
                background-color: rgb(39, 231, 10);
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid rgb(35, 224, 227);
                color: rgb(17, 183, 216);
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid rgb(232, 10, 10);
                padding: 13px 35px;
                letter-spacing: 1px;
                color:black;
                border-radius: 30px;
                background-color:  rgb(207, 30, 142);
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid rgb(23, 151, 16);
                color: rgb(24, 177, 182);
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: rgb(13, 161, 190);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">RI<span>ZZ</span>T<span>ech</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="Product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2>INNOVATION AND DESIGN IN CODING</h2>
                <br>
                <p>  Transforming Ideas into Impartful Reality through Precision Coding and Innovation </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by L.MAHESH MUTHU(212222040093)</center>
    </footer>
</body>
</html>

Product.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>RIZZTECH</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-color:rgb(202, 208, 217);
                background-size: cover;
                background-position: center;
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
                color:rgb(45, 201, 233);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
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
                background:rgb(13, 181, 200);
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
                background-color:rgb(24, 147, 200);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid white;
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 70px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color: rgb(24, 186, 211);
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: white;
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color: rgb(12, 151, 193);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">RI<span>ZZ</span>T<span>ech</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="Product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <img src="poster1.jpeg" alt="">
                    <h3>Python</h3>
                    <p>Where simplicity meets power in the world of programming.</p>
                </div>
                <div class="box">
                    <img src="cposter2.jpeg" alt="">
                    <h3>C pgg </h3>
                    <p> Coding resilience in C: Unleashing the raw power of systems programming.</p>
                </div>
                <div class="box">
                    <img src="c++postere3.png" alt="">
                    <h3>C++ pgg</h3>
                    <p>Elevating possibilities with the perfect blend of efficiency and object-oriented elegance.</p>
                </div>
                <div class="box">
                    <img src="javaposter4.png" alt="">
                    <h3>Java</h3>
                    <p>Brewing cross-platform magic with the steaming cup of robust and versatile programming.</p>
                </div>
                <div class="box">
                    <img src="jsposter5.png" alt="">
                    <h3>Java Script</h3>
                    <p>Transforming web landscapes with dynamic interactivity and client-side wizardry.</p>
                </div>
              
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by L.MAHESH MUTHU(212222040093) </center>
    </footer>
</body>
</html>

person.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>RIZZTECH</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-color:rgb(207, 95, 31);
                background-size: cover;
                background-position: center;
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
                color:rgb(19, 219, 246);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
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
                background:rgb(212, 212, 208);
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
                background-color:rgb(21, 153, 201);
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
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid white;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: rgb(30, 177, 196);
            }
            footer {
                background-color: rgb(22, 182, 213);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">RI<span>ZZ</span>T<span>ech</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="Product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>    
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="College Photo Mahesh.jpg"> </td>
                    <td> <img src="obama.jpeg"> </td>
                    <td> <img src="vj.jpeg"> </td>
                    <td> <img src="timo.jpeg"> </td>
                    <td> <img src="willsmith.jpeg"> </td>
                    <td> <img src="ani.jpeg"> </td>
                </tr>
                <tr align="center">
                    <th> TIMO </th>
                    <th> OBAMA </th>
                    <th> VIJAY</th>
                    <th> TIMOO </th>
                    <th> WILLSMITH</th>
                    <th> ANIRUDH </th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                    <td> Dy. Director </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by L.MAHESH MUTHU(212222040093)</center>
    </footer>
</body>
</html>

contact.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>RIZZTECH</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-color:rgb(26, 11, 142);
                background-size: cover;
                background-position: center;
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
                color:rgb(12, 213, 196);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
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
                background:rgb(10, 125, 166);
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
                background-color:rgb(21, 168, 190);
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
                border: 3px solid rgb(13, 166, 180);
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
                left: 30px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: white;
                border-radius: 30px;
                background: rgb(1, 134, 157);
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
                color: rgb(20, 176, 182);
                font-size: 20px;
            }
            footer {
                background-color: rgb(23, 159, 183);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">RI<span>ZZ</span>T<span>ech</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="Product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
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
                        <h1> CONTACT US </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> CONTACT INFO </h2>
                <p> <span>Address</span> : S2,SUNIL GAVASKAR NAGAR NAGAR KILLAMBAKAM</p>
                <p> <span>Email</span> : RIZZTech@gmail.com.com </p>
                <p> <span>Phone</span> : 9940313700 </p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by L.MAHESH MUTHU(212222040093)</center>
    </footer>
</body>
</html>
```


## OUTPUT:
![Screenshot (327)](https://github.com/MaheshMuthuL/softweb/assets/135570619/595521ff-7ccf-45bd-9722-395728afee3c)
![Screenshot (328)](https://github.com/MaheshMuthuL/softweb/assets/135570619/e77aec89-0531-4e94-bac4-1e63f4cdcea2)




![Screenshot (329)](https://github.com/MaheshMuthuL/softweb/assets/135570619/15acbeb2-84f8-45e9-8987-00fb2230d7cd)
![Screenshot (332)](https://github.com/MaheshMuthuL/softweb/assets/135570619/30e3eb5e-faff-4420-9d0e-a0e026065203)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
