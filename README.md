# index.html


<!DOCTYPE html>
<html lang="en-US">
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<head>
  <title>Artistic Fool - The at Home Art School</title>
  <meta charset="UTF-8">
</head>
    <div class="box">
      <main>
<body style="background-color:floralwhite;">

  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>

  <div class="header">
    <h2>ArtisticFool</h2>
    <p>The at Home Art School</p>
  </div>
  <div id="navbar">
    <a class="active" href="javascript:void(0)">Home</a> <a href="javascript:void(0)">News</a> <a href="javascript:void(0)">Contact</a>
  </div>
  <div style="background-color:indianred;color:white;padding:7px;"></div>
  <div class="content">
    <h3>Placeholder text</h3>
    <p>Placeholder text.</p>
  </div>
  <div style="background-color:indianred;color:white;padding:7px;"></div>
  <script>
               window.onscroll = function() {myFunction()};
               
               var navbar = document.getElementById("navbar");
               var sticky = navbar.offsetTop;
               
               function myFunction() {
                 if (window.pageYOffset >= sticky) {
                   navbar.classList.add("sticky")
                 } else {
                   navbar.classList.remove("sticky");
                 }
               }
  </script>
  <head>
    <style>
               #title {
               background-color: lightgrey;
               color: black;
               padding: 40px;
               text-align: center;
               }
    </style>
  </head>
  <head>
  <div style="background-color:midnightblue;color:white;padding:20px;">
    <h3 style="color:white;">Welcome!</h3>
    <p>Welcome to ArtisticFool, The at Home Art School! This is a blog-type website that will be used to showcase my art and share my artistic experience with the art community.</p>
    <p>Unfortunately, nowadays it is really common to see artists posting only their polished works and not showing the messy process behind the scenes. Here, I want to showcase the good, the bad and the ugly of art and show others that it's okay to experiment and get messy! Care to join me?</p>
  </div>
  <div style="background-color:indianred;color:white;padding:7px;"></div>

  </body>
</html>
 

         <head>
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <link rel="stylesheet" href="styles.css">
         </head>
         <style>

* {box-sizing: border-box}

#Blog {background-color: midnightblue;}
#Portfolio {background-color: midnightblue;}
#Register {background-color: midnightblue;}
#About {background-color: midnightblue;}
</style>
</head>
<body>

<button class="tablink" onclick="openPage('Blog', this, 'midnightblue')" id="defaultOpen"><strong>Blog</strong></button>
<button class="tablink" onclick="openPage('Portfolio', this, 'midnightblue')"><strong>Portfolio</strong></button>
<button class="tablink" onclick="openPage('Register', this, 'midnightblue')"><strong>Register</strong></button>
<button class="tablink" onclick="openPage('About', this, 'midnightblue')"><strong>About</strong></button>

<div id="Blog" class="tabcontent">
  <h3>Blog</h3>
  <hr>
  <p style="font-size: 17pt" font-family= "Arial, Helvetica, sans-serif">Placeholder Text</p>
  <p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif"><strong>March 28, 2023</strong></p>
  <p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">This school year (2022 to now) I have been taking both a Painting and Oil Painting classes that are offered at my school.</p>
  <img src="./FatOverLean1.png" alt="FatOverLeanPractice" width="500" height="725">
  <img src="./Palette.png" alt="CrazyColors" width="500" height="725">
  <img src="./ArtShowCherries1.png" alt="CherryUnderpainting" width="500" height="725">
  <hr>
</div>

<div id="Portfolio" class="tabcontent">
  <h3>Portfolio</h3>
  <hr>
  <p style="font-size: 17pt" font-family= "Arial, Helvetica, sans-serif">Here is some of my work:</p>
  <style>
* {box-sizing: border-box}
.mySlides1, .mySlides2 {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 550px;
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
  color: steelblue;
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

/* On hover, add a grey background color */
.prev:hover, .next:hover {
  background-color: #f1f1f1;
  color: steelblue;
}
</style>
</head>

<p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif"><strong>Painting Classes 2022-2023:</strong></p>
<div class="slideshow-container">
  <div class="mySlides1">
    <img src="./InkSkull.png" style="width:100%">
  </div>

<div class="mySlides1">
    <img src="./AllaPrimaWhitePalette.png" style="width:100%">
  </div>

  <div class="mySlides1">
    <img src="INSERTPICTURE" style="width:100%">
  </div>

  <div class="mySlides1">
    <img src="INSERTPICTURE" style="width:100%">
  </div>
  <a class="prev" onclick="plusSlides(-1, 0)">&#10094;</a>
  <a class="next" onclick="plusSlides(1, 0)">&#10095;</a>
</div>

<hr>

<p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif"><strong>Photography Class 2022:</strong></p>
<div class="slideshow-container">
  <div class="mySlides2">
    <img src="./PhotographyFigman.png" style="width:100%">
  </div>

  <div class="mySlides2">
    <img src="./PhotographyEye.png" style="width:100%">
  </div>

  <div class="mySlides2">
    <img src="./BLACKANDWHITE.jpg" style="width:100%">
  </div>
  <a class="prev" onclick="plusSlides(-1, 1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1, 1)">&#10095;</a>
</div>
<hr>

<script>
let slideIndex = [1,1];
let slideId = ["mySlides1", "mySlides2"]
showSlides(1, 0);
showSlides(1, 1);

function plusSlides(n, no) {
  showSlides(slideIndex[no] += n, no);
}

function showSlides(n, no) {
  let i;
  let x = document.getElementsByClassName(slideId[no]);
  if (n > x.length) {slideIndex[no] = 1}    
  if (n < 1) {slideIndex[no] = x.length}
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";  
  }
  x[slideIndex[no]-1].style.display = "block";  
}
</script>

  <title>Photo Gallery</title>
</div>

  <div id="Register" class="tabcontent">
  <h3>Register</h3>
  <hr>
    <p style="font-size: 17pt" font-family= "Arial, Helvetica, sans-serif">Please fill out this form with the required information:</p>
    <form method="post" action='https://register-demo.freecodecamp.org'>
      <fieldset style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">
        <label for="first-name">Enter Your First Name: <input id="first-name" name="first-name" type="text" required /></label>
        <label for="last-name">Enter Your Last Name: <input id="last-name" name="last-name" type="text" required /></label>
        <label for="email">Enter Your Email: <input id="email" name="email" type="email" required /></label>
        <label for="new-password">Create a New Password: <input id="new-password" name="new-password" type="password" pattern="[a-z0-5]{8,}" required /></label>
      </fieldset>
      <fieldset style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">
        <label for="personal-account"><input id="personal-account" type="radio" name="account-type" class="inline" /> Personal Account</label>
        <label for="business-account"><input id="business-account" type="radio" name="account-type" class="inline" /> Business Account</label>
        <label for="terms-and-conditions">
          <input id="terms-and-conditions" type="checkbox" required name="terms-and-conditions" class="inline" /> I accept the <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">terms and conditions</a>
        </label>
      </fieldset>
      <fieldset style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">
        <label for="profile-picture">Upload a profile picture: <input id="profile-picture" type="file" name="file" /></label>
        <label for="age">Input your age (years): <input id="age" type="number" name="age" min="13" max="120" /></label>
        <label for="referrer">How did you hear about us?
          <select id="referrer" name="referrer">
            <option value="">(select one)</option>
            <option value="1">School</option>
            <option value="2">Social Media</option>
            <option value="3">Friends/Family</option>
            <option value="4">Other</option>
          </select>
        </label>
        <label for="bio">Provide a bio:
          <textarea id="bio" name="bio" rows="3" cols="30" placeholder="Enter bio here..."></textarea>
        </label>
      </fieldset>
      <input type="submit" value="Submit" />
    </form>
  </body>
  <hr>
    </div>

<div id="About" class="tabcontent">
  <h3>About</h3>
  <hr>
  <p style="font-size: 17pt" font-family= "Arial, Helvetica, sans-serif">Who we are and what we do:</p>
  <p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif"><strong>About Me</strong></p>
  <p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">My name is Hayden, I am 16. I have been making art for as long as I can remember. As a kid, I would sit at my kitchen table and draw for hours on end. I would take inspiration from whatever was happening in my life and transfer it onto paper. It was a way I could express myself and how I was feeling. Of course, these drawings were far from perfect. But they were never meant to be perfect, I would just create for the sake of creating.</p>
  <p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">Throughout my elementary school years I would take after-school art classes and draw whenever I had free time. I couldnt get enough of it. In 5th grade, I remember being in class when a man came in with his roling cart. I had never seen him before. It was then announced that he would be coming in every couple of weeks to give us an art lesson. It was like a pop-in art class. I would look forward to those days like nobody's buisness, hungry for the knowledge that I had yet to recieve. After about about a year or so of this, it was announced that he would be officially joining our school's art department and become a full-time art teacher working beside the current Jr. High art teacher.</p>
  <p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">Throughout Jr. HIgh I took as many art classes as I could (from both teachers). I learned so much from their classes. Throughout 9th grade, I really struggled with art block (to the point where I couldnt even hold a pencil to my sketchbook). I reached out to my teachers and they took me under their wing and tutored me privately, meeting with me every month or so. During that time they encouraged me and helped me become more confident in my art. They are the reason why I continued on my art journey. Without them, I may not still be doing what I do.
  <p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">This year was my first year at an actual highschool, that means new experiences, opportunities, relationships and more. So far this year I have taken both a Painting and I am currently enrolled in a Oil Painting class (both of which I have enjoyed thuroughly). I had used most of the mediums in my Painting class before and had some expirience with them. This class taught me different techniques to use with each individual medium and helped me build my confidence in using them. Prior to taking my Oil Painting class I had never used oil paints before. They have been really fun to learn about and play with. Similar to my Painting class, it helped me become more familiar with different techniques. These classes came with their ups and downs but they have been an amazing learning expirience and I am excited to use them to continue to expand my art knowlege further. You can never stop learning.</p>
  <p style="font-size: 12pt" font-family= "Arial, Helvetica, sans-serif">"When you stop learning you start dying" -Albert Einstein</p>
  <hr>
</div>

<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

document.getElementById("defaultOpen").click();

</script>
</body>
</html>
