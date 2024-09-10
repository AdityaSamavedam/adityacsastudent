---
layout: base
title: About Me Page
description: A Webpage about me (Aditya Samavedam)
hide: true
---

# 🌟 Aditya Samavedam's Blog 🌟
<div class="row">
  <div class="column">
    <img src="./images/Flags/CaliforniaFlag.png" alt="California" style="width:100%">
    <p>California Resident for 8 years</p>
  </div>
  <div class="column">
    <img src="./images/Flags/USAFlag.png" alt="USA" style="width:100%">
    <p>Citizen of USA</p>
  </div>
  <div class="column">
    <img src="./images/Flags/IndiaFlag.png" alt="India" style="width:100%">
    <p>Lived in India from 1st through 8th grade</p>
  </div>
</div>

<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 500px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: white;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
  background-color: rgb(0,0,0);
  box-sizing: border-box;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  background-color: rgb(0,0,0);
  box-sizing: border-box;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
*{
    box-sizing: border-box;
    }

    .column {
    float: left;
    width: 33.33%;
    padding: 5px;
    }

    /* Clearfix (clear floats) */
    .row::after {
    content: "";
    clear: both;
    display: table;
    }
    body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
        color: #333;
        margin: 0;
        padding: 0;
        transition: background-color 0.5s, color 0.5s;
    }

    header {
        background-color: #333;
        color: white;
        padding: 10px 20px;
        text-align: center;
        transition: background-color 0.5s;
    }

    h1 {
        margin: 0;
        font-size: 2.5em;
    }

    .content {
        padding: 20px;
    }

    a {
        color: limegreen;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }

    img {
        max-width: 100%;
        height: auto;
        display: block;
        margin: 20px 0;
        transition: transform 0.3s;
    }

    img:hover {
        transform: scale(1.1);
    }

    .about-me ul {
        list-style-type: none;
        padding: 0;
    }

    .about-me li {
        padding: 5px 0;
    }

    .highlight {
        color: fuchsia;
    }

    .dark-mode {
        background-color: #1a1a1a;
        color: #f0f0f0;
    }

    .dark-mode header {
        background-color: #000;
    }

    .dark-mode a {
        color: lightgreen;
    }

    .dark-mode button {
        background-color: #444;
        color: #f0f0f0;
    }

    .quote {
        font-style: italic;
        color: lime;
        margin-top: 20px;
    }

    button {
        padding: 10px 20px;
        margin: 20px 0;
        cursor: pointer;
        background-color: #333;
        color: white;
        border: none;
        transition: background-color 0.3s, transform 0.3s;
    }

    button:hover {
        background-color: limegreen;
        transform: scale(1.05);
    }
</style>

<button id="toggleDarkMode">Toggle Dark Mode</button>

# Journey of my life:

- #### 🏥 Born in 2008 in Scripps Memorial Hospital, La Jolla
- #### 🏡 Lived in Scripps Ranch for six years
- #### ✈️ Moved to Hyderabad, India in 2014 because my grandparents were ill
- #### 🏫 Did my 1st through 8th grade in India
- #### ↩️ Moved back to San Diego in 2022 because my sister got into UCI
- #### 🏫 Started high school here as a Freshman at Del Norte

### Check out my <a href="https://github.com/AdityaSamavedam" target="_blank">Github page</a>
<br>
<br>
### 🙂A few things About Me🙂
<br>
<p>Click on the arrow buttons to navigate through the slideshow</p>
<br>
<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 6</div>
  <img src="./images/DNHS.jpg" style="width:100%">
  <div class="text">Junior at DNHS</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 6</div>
  <img src="./images/Taekwondo.png" style="width:100%">
  <div class="text">Second Degree Black Belt in Taekwondo</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 6</div>
  <img src="./images/Python.png" style="width:100%">
  <div class="text">Wants to major in CS and likes Python</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 6</div>
  <img src="./images/Badminton.webp" style="width:100%">
  <div class="text">Likes to play badminton</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 6</div>
  <img src="./images/BrawlStars.png" style="width:100%">
  <div class="text">Loves to play Brawl Stars but I'm noob</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 6</div>
  <img src="./images/mario-kart.gif" style="width:100%">
  <div class="text">Also loves to play Mario Kart Wii</div>
</div>

<a class="prev" onclick="plusSlides(-1)">⏪</a>
<a class="next" onclick="plusSlides(1)">⏩</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
  <span class="dot" onclick="currentSlide(6)"></span>
</div>
<br>
<br>
<h3>Best song in the world: <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0" target="_blank" style="color:turquoise">Click this link !!!</a></h3>
<br>
<br>
# My Culture and Family
<br>
<img src="./images/Flags/HinduFlag.png">
- I am a Indian and I am also Hindu.
- My family is pretty small but I also have a sister who is about 21 years old.
- Most of my relatives live in India and when I lived in Hyderabad, I used to visit them every year

<button id="quoteButton">Show Me a Motivational Quote</button>
<div class="quote" id="quote"></div>


<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
    // Dark Mode Toggle
    document.getElementById('toggleDarkMode').addEventListener('click', function() {
        document.body.classList.toggle('dark-mode');
    });

    // Motivational Quote Generator
    const quotes = [
        "Believe you can and you're halfway there.",
        "The only way to do great work is to love what you do.",
        "Success is not final, failure is not fatal: It is the courage to continue that counts.",
        "Don't watch the clock; do what it does. Keep going.",
        "The future belongs to those who believe in the beauty of their dreams."
    ];

    document.getElementById('quoteButton').addEventListener('click', function() {
        const randomQuote = quotes[Math.floor(Math.random() * quotes.length)];
        document.getElementById('quote').textContent = randomQuote;
    });

    // Alert for Best Song Link
    document.querySelector('a[href="https://www.youtube.com/watch?v=xvFZjo5PgG0"]').addEventListener('click', function(event) {
        alert("Get ready for the best song ever!");
    });
</script>

<script src="https://utteranc.es/client.js"
        repo="AdityaSamavedam/adityacsastudent"
        issue-term="pathname"
        theme="github-dark"
        crossorigin="anonymous"
        async>
</script>