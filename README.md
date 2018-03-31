<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Camel Grill</title>
  <link rel="stylesheet" href="assets/css/main.css">
<link href="https://fonts.googleapis.com/css?family=Annie+Use+Your+Telescope|Caveat|Caveat+Brush|Gochi+Hand|Kaushan+Script" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
</head>
<body>

</header>

<section id="hero-image">

  <header class="header-site">
    <div class="top-nav">
    <ul class = "left-top-nav">
      <li class = "left-top-nav"><a href="homepage.html">Homepage</a></li>
      <li class = "left-top-nav"><a href="about.html">About</a></li>
      <p>Camel</p>
    <img class="header-logo" src="assets/images/Logo.png" alt="camel grill logo">
    <p>Grill</p>
      <li class = "left-top-nav"><a href="contact.html">Contact</a></li>
      <li class = "left-top-nav"><a href="thefood.html">The Food</a></li>
    </ul>
  </nav>
  </div>
  <section class="second-nav">
  <div id="opening-hours">
    <img src="assets/images/orange-clock.jpg" alt="clock logo">
    <p> OPEN NOW </p>
  </div>

  <div id="location">
    <img src="assets/images/orange-location.jpg" alt="location logo">
    <p>37b Dixon Street, Te Aro, Wellington 6011, New Zealand</p>
  </div>

  <div id="phone-orders">
    <img src="assets/images/orange-phone.jpg" alt="phone logo">
    <p>Phone orders: 04-384 6813</p>
  </div>
</section>

</section>

</header>

<div id="second-panel">
  <iframe class="main-map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2997.773513199158!2d174.77501221511457!3d-41.29203344868162!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6d38afd7471559d5%3A0xbb9b6a62c1b06ee4!2sCamel+Grill!5e0!3m2!1sen!2sau!4v1522389189944"></iframe>
<img class="welcome-camel" src="assets/images/camel.jpg" alt="Camel with Welcome written on it">
<div id="welcome-blurb">
<p>Camel Grill brings a combination of mouth watering flavors of the middle east. Quality hand made food with authentic spices and fresh ingredients.</p>
<input id="main-menu-button" type="button" value="View Menu" name="Menu button">

</div>
</div>



<div class = "third-panel">
  <h1>What the people say</h1>
  <div class ="review-one">
  <p><q>Absolutely amazing food! It’s so nice to see someone cooking with passion! It really shows in the taste of the food! Can’t wait to go back! I’d recommend the spicy chips with any of the Shawarma!</q></p> </br> <p><strong>Woody</strong></p>
</div>

<div class ="review-two">
<q>Best vegan kebabs in Wellington. Everything is handmade and the owner is real friendly. Definitely a regular now!</q> </br> </br> <p>Keith</p>
</div>


<div class ="review-three">
<q>Having lived in the Middle East for 7 years this is by far with out a doubt one of, if not the best chicken kebabs I have ever had. They have it down. The meat and the marinade is phenomenal and the bread they use....wow what can I say!</q> </br> </br> <p>Andy</p>
</div>

<div class ="review-four">
<q>Massive fan, definitely worth every penny. This is the only decent falafel I've had in New Zealand - but it's not just decent, this falafel is fantastic! The pizza and meaty kebabs are also good, but the falafel had my heart. Try the desserts, too! </q> </br> </br> <p>Nicole</p>
</div>


<div class ="review-five">
<q>I judge a kebab and shawarma place by their falafel and these are amazing. The wraps are house made and grilled to a lovely warm crisp and their spicy sauce tops it off. The smoked meats are damn good too. </q> </br> </br> <p>Eden</p>
</div>

</div>

<footer class="primary-footer container group">
  <nav>
    <ul>
      <li><a href="homepage.html">Homepage</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="contact.html">Contact</a></li>
      <li><a href="ourstory.html">Our Story</a></li>
      <li><a href="thefood.html">The Food</a></li>
    </ul>
  </nav>
    <small>&copy; Camel Grill</small>
</footer>

<script>$(window).scroll(
    {
        previousTop: 0
    },
    function () {
    var currentTop = $(window).scrollTop();
    if (currentTop < this.previousTop) {
        $(".top-nav").show();
    } else {
        $(".top-nav").hide();
    }
    this.previousTop = currentTop;
});
</script>

</body>
</html>
