<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>RESCU FOUNDATION</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <link rel="stylesheet" href="css/normalize.css">
    <link href='(https://fonts.googleapis.com/css?family=Open+Sans:400italic,400,300,600' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="css/main.css">

<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    border: 1px solid #e7e7e7;
    background-color: #f3f3f3;
}

li {
    float: left;
}

li a {
    display: block;
    color: #666;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover:not(.active) {
    background-color: #ddd;
}

li a.active {
    color: white;
    background-color: #4CAF50;
}
</style>
</head>
  <body>
    <header>

      <nav>
        <ul>
          <li><a href="index.html" class="selected">Home</a></li>
          <li><a href="whatWeDo.html">WhatWeDo</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="donate.html">Donate</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
              <a href="index.html" id="logo">
        <h1>RESCU FOUNDATION</h1>
        <h2>CHARITY</h2>
      </a>
      </nav>
    </header>
    <div id="wrapper">
      <section>
        
<!____slideshow_____>
<section>
  <img class="mySlides" src="ecocash M.png" style="width:auto">
  <img class="mySlides" src="telecash M.png" style="width:auto">
  <img class="mySlides" src="steward bank.png" style="width:auto">
</section>














<script>
// Automatic Slideshow - change image every 3 seconds
var myIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}
    x[myIndex-1].style.display = "block";
    setTimeout(carousel, 3000);
}
</script>

      </section>
      <footer>
        <a href="http://twitter.com/"><img src="img/twitter-wrap.png" alt="Twitter Logo" class="social-icon"></a>
        <a href="http://facebook.com/"><img src="img/facebook-wrap.png" alt="Facebook Logo" class="social-icon"></a>
        <p>&copy; 2017 RESCU FOUNDATION.</p>
      </footer>
    </div>
  </body>
</html>
