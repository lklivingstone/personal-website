# personal-website
<!--
        <div class="name">
            <h1 class="name">L K Livingstone</h1>
            </div>
            <div class="grid">
            <p class="short-description">Beginner Front-end Developer</p>
        </div>
        -->
    
* {
    box-sizing: border-box;
    display: grid;
    place-items: center;
}




.grid {
    display: grid;
    place-items: center;

}
.name {
    display: grid;
    color: white;
    border: red 1px solid;
    
}
.short-description {
    color: white;
    
    text-align:center;
    border: red 1px solid;
}


<div class="flicker">
                    <p>L </p><p>K</p> 
                </div>



Final:
<header>
            <h1 class="logo"><a href="index.html">LK</a></h1>
            <nav>
                <ul>
                    <li><a href="#">Work</a></li>
                    <li><a href="#">Contact</a></li>
                    <li><a href="#"><img class="dark-night" src="./Logos/Fire.jpg"></a></li>
                </ul>
            </nav>
        </header>
            <div class="text-box">
                <span>L</span><span class="space">.</span><span>K</span><span class="space">.</span><span>L</span><span>i</span><span>v</span><span>i</span><span>n</span><span>g</span><span>s</span><span>t</span><span>o</span><span>n</span><span>e</span>
                <p>Beginner Front-end Developer</p>
                <a href="" class="about-me">About me</a>
            </div>
        
        <footer>
            <ul class="footer-nav">
                <li><a href="#">Twitter</a></li>
                <li><a href="#">Linkedin</a></li>
                <li><a href="#">Github</a></li>
                <li><a href="#">Contact Me</a></li>
            </ul>
        </footer>

:root {
    --primary-clr: black;
}
* {
    color: white;
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

body {
    background-color: var(--primary-clr );
    font-family: 'Press Start 2P', cursive;  
}

.logo {
    padding: 0.5em;
    text-align: center;
}

.logo a {
    text-decoration: none;
}

.home-button {
    padding-top: 23px;
    height: 45px;
    width: auto;
    text-decoration: none;
}

nav ul {
    font-size:0.75rem;
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
    justify-content: space-around;
    align-items: center;
}

nav ul li a{
    text-decoration: none;
}

nav a {
    display: inline-block;
    padding: 0.5em;
}



.nav-links {
    flex: 1;
    text-align: right;
}

.nav-links ul li {
    list-style: none;
    display: inline-block;
    padding-left: 30px;
    position: relative;
}

.nav-links ul li a {
    text-decoration: none;    
}

.nav-links ul li::after {
    content: '';
    width: 0%;
    height: 2px;
    background: white;
    display: block;
    margin: auto; 
    transition: 0.5s;  
}

.nav-links ul li:hover::after {
    width: 100%;    
}

.dark-night {
    height: 25px;
    width: 18px;
}
.header {
    min-height: 100vh;
    width: 100%;
    position: relative;
}



.text-box {
    width: 60%;
    color: white;
    position: absolute;
    top: 40%;
    left: 20%;
}

.text-box p {
    font-size:  1.23rem;
    margin: 20px 0px 20px;
}
.text-box span {
    font-size:  2.3rem;
}
.space {
    color: black;
    font-size:  2.3rem;
}

.text-box span:hover {
    background-color: white;
    color: black;
}


.flicker p {
    display: inline-block;
}
.about-me {
    left: 30%;
    text-decoration: none;
    display: inline-block;
    border: 1px solid white;
    padding: 12px 34px;
    position: relative;
    cursor: pointer;
}

footer {
    background: grey;
    padding: 3em 1em;
}

.footer-nav {
    list-style: none;
    display: flex;
}        

\\\\\\\\\\\\\\\\\\\\\\


:root {
    --primary-clr: black;
}

* {
    background-color: var(--primary-clr);
    color: white;
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

html {
    background-color: var(--primary-clr );
    font-family: 'Press Start 2P', cursive;  
}

.logo {
    margin-top: 2rem;
}

nav ul {
    list-style: none;
}
nav ul li a {
    text-decoration: none;
}

.flex {
    display: flex;
    gap: 1rem;
}

.dark-night {
    height: 25px;
    width: 18px;
}

.about-me {
    text-decoration: none;
    display: block;
}

.container {
    min-height: 100vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 2vh;
}



\\\\\\\\\\\\\\\\\\\\\

<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        
        <title>L K Livingstone</title>
        <link rel="stylesheet" type="text/css" href="styles.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

    </head>
    <body>
        <header class="primary-header flex">
            <div>
                <span class="logo">LK</span>
            </div>
        <nav>
            <ul id="primary-nav" class="primary-nav flex">
                <li><a href="#">Work</a></li>
                <li><a href="#">Contact</a></li>
                <li><a href="#"><img class="dark-light" src="./Logos/Fire.jpg" style="height: 18px; width: 12px;"></a></li>
            </ul>
        </nav>
    </header>
        <!--
        <section id="hero">
            <div class="hero container">
                <div>
                    <h1 class="temp">Hi, I'm L K Livingstone</h1>
                    <p1>Beginner Front-end Developer</p1>
                    <a href="#" type="button" class="about-me">About me</a>
            </div>
            </div>
        </section>
        -->
    </body>
</html>