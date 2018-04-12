<!DOCTYPE HTML>

<html>
	<head>
		<title>Spatial by TEMPLATED</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<link rel="stylesheet" href="assets/css/main.css" />
		<!-- soc tinklu loginai -->
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
		<link href="https://fonts.googleapis.com/css?family=Dancing+Script" rel="stylesheet">
	</head>
	<body>
<!-- header -->
<div class="hero-image">
  <div class="hero-text">
    <h2><img src="images/VILNIUSlog.png" width="150px" height="120"></h2>
    <h1>Welcome to the <b>BEST</b> city for traveling!!!</h1>
  </div>
</div>
<!-- <<<<<<<<<<<<<<<<<<<<<<<<< header >>>>>>>>>>>>>>>> -->
<div class="header" id="myHeader">
  <a href="#atraction">Activities</a>
  <a href="#food">Food</a>
  <a href="#shops">Shoping</a>
  <div class="header-right">
    <a href="#car">Rent a car</a>
    <a href="#booking">Accommodation</a>
  </div>
</div>

<!-- <<<<<<<<<<< navigation >>>>>>>>>>>>>>>>>>>>>>>>>> -->


<div class="content"> <!-- introduction -->
	<section class="intro">
		<h2>Welcome to Vilnius</h2>
		<p><b>V</b>ilnius (vil-nyus), the baroque beauty of the Baltic, is a city of immense allure. It easily tops the country’s best-attraction bill, drawing tourists like moths to a flame with an easy, confident charm and a warm, golden glow that makes you wish for long midsummer evenings every day of the year.</p>
		<p><b>T</b>he capital may be a long way north and east, but it’s quintessentially continental, with Europe’s largest baroque old town at its heart. Viewed from a hot air balloon, the skyline – pierced by countless Orthodox and Catholic church steeples – looks like a giant bed of nails. Adding to this heady mix is a combination of cobbled alleys, crumbling corners, majestic hilltop views, breakaway states and traditional artists’ workshops – all in a city so small you’d sometimes think it was a village. It has not always been so happy here, though. There are reminders of loss and pain too, from the horror of the KGB’s torture cells to the ghettos where the Jewish community was concentrated before being murdered by the Nazis. Yet the spirit of freedom and resistance has prevailed, and the city is forging a new identity, combining the past with a present and future that involves world cuisine, a burgeoning nightlife and shiny new skyscrapers.</p>
		</p>
	</section>
	<!-- - - - - -  atraction - - - - - - - - - - -->
<div class="slideshow-container">
<h2 id="atraction">Things to see...</h2>
<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="images/pylis is vyrsaus.jpg" style="width:100%">
  <div class="text">Gediminas Tower</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="images/vilnius_up.jpg" style="width:100%">
  <div class="text">Romantic Downtown</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="images/traka.jpg" style="width:100%">
  <div class="text">Trakai Castel</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="images/Vilnius-2.jpg" style="width:100%">
  <div class="text">Business center</div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span>

  <span class="dot" onclick="currentSlide(4)"></span> 
</div>


<div>
<iframe  class="youtube" width="1000" height="600"
src="https://www.youtube.com/embed/plVk4_JgBtQ">
</iframe>
</div>
	</section>
<!-- - - - - - - - - -  food - - - - - - - - - -->
	<section id="food"> 
		<h2 class="atractionh2">What to eat?</h2>
<div class="tab">
  <button class="tablinks active" onclick="openFood(event, 'cepelinas')">Cepelinas</button>
  <button class="tablinks" onclick="openFood(event, 'saltibarsciai')">Šaltibarsciai</button>
  <button class="tablinks" onclick="openFood(event, 'kibinai')">Kibinai</button>
</div>

<div id="cepelinas" class="tabcontent" style="display: block;">s
<img src="images/cepelinai.jpg" width="523px" height="300px">
</div>

<div id="saltibarsciai" class="tabcontent" >
<img src="images/saltibarsciai.jpg" width="523px" height="300px">

</div>

<div id="kibinai" class="tabcontent">
<img src="images/kibinai.jpg" width="523px" height="300px">
</div>
</section>

<!-- - - - - - Where to eat - - - - - - - -->
<h2 class="atractionh2 tarpas">Where to eat?</h2>

<table id="myTable">
  <tr class="header">
    <th style="width:60%;">Name</th>
    <th style="width:40%;">Adress</th>
  </tr>
  <tr>
    <td><a href="http://fortodvaras.lt/">FORTO DVARAS</a></td>
    <td>Pilies st. 16,</td>
  </tr>
  <tr>
    <td><a href="http://www.berneliuuzeiga.eu/berneliai-vilniuje.html">Bernelių Užeiga</a></td>
    <td>A. Vienuolio st. 1</td>
  </tr>
  <tr>
    <td><a href="http://baltidrambliai.lt/">Balti Drambliai</a></td>
    <td>Vilniaus st. 41</td>
  </tr>
  <tr>
    <td><a href="http://www.beatosvirtuve.lt/">Beatos virtuvė</a></td>
    <td>Gedimino pr. 27</td>
  </tr>
  <tr>
    <td><a href="http://www.manoguru.lt/">Mano guru</a></td>
    <td>Vilniaus st. 22</td>
  </tr>
  <tr>
    <td><a href="http://www.klaipedos-senamiestis.lt/lt/klaipedos-senamiestis">Klaipėdos senamiestis</a></td>
    <td>S. Daukanto a. 2</td>
  </tr>
  <tr>
    <td><a href="http://zemaiciu-asotisrestoranas.business.site/">Žemaičių ąsotis</a></td>
    <td>Naugarduko st. 32</td>
  </tr>
  <tr>
    <td><a href="https://m.facebook.com/pages/Prie-Angelo-Kavine/303984593016058">Prie angelo</a></td>
    <td>Užupio st. 9</td>
  </tr>
</table>
<!-- - - - - - - - - shops - - - - - - - -->
	<section>
		<h2 class="atractionh2" id="shops">Shops</h2>
<div class="shops">
  <ul class="shops_ul">
    <li class="shops_li">
      <a href="http://akropolis.lt/lt/vilnius"><img class="shops_img" src="http://www.veidas.lt/wp-content/uploads/akropol_vilnius_25.jpg" /></a>
      <h3 class="shops_h3">Akropolis</h3>
      <p>Ozo st. 25</p></li> 
      
  	     <li class="shops_li">
         <a href="https://www.ozas.lt/"><img class="shops_img" src="images/Ozas-9.jpg" /></a>
   	     <h3 class="shops_h3">OZAS</h3>
  		 <p>Ozo st. 18</p></li>

   		 <li class="shops_li">
   	     <a href="#"><img class="shops_img" src="images/Panorama-7.jpg" /></a>
   	     <h3 class="shops_h3">Panorama</h3>
   	     <p>Saltoniškių st. 9</p>
   		 </li>
 
   		 <li class="shops_li">
    	  <a href="http://www.vcup.lt/"><img class="shops_img" src="images/VCUP.jpg" /></a>
    	  <h3 class="shops_h3">VCUP</h3>
    	  <p>Upės st. 9</p>
    	</li>
  	</ul>
	</div>
	</section>
	<!-- - - - - - CARS - - - - - - - - -  -->
	<h2 class="atractionh2" id="car">Rent a Car</h2>

<div class="car">
  
  <div class="container">
  	<a href="https://autoplius.lt/skelbimai/nuoma/lengvieji-nuoma"><img src="images/cars/rentacar2.jpg" alt="autoplius" style="width:100%"></a>
    <h4><b>AutoPlius</b></h4> 
    <p>Private Car Owners</p> 
  </div>
    <div class="container">
    <a href="https://www.dalinuosi.lt/automobiliu-nuoma"><img src="images/cars/retro_volga.jpg" alt="dalinuosi" style="width:100%"></a>
    <h4><b>Dalintis.lt</b></h4> 
    <p>Private Car Owners</p> 
  </div>
    <div class="container">
    <a href="https://autorent24.lt/"><img src="images/cars/rentacar3.jpg" alt="autorent24" style="width:100%"></a>
    <h4><b>autorent24.lt</b></h4> 
    <p>Renting Company</p> 
  </div>
    <div class="container">
    	<a href="https://autobanga.lt/"><img src="images/cars/drivecar.jpg" alt="autobanga" style="width:100%"></a>
    <h4><b>autobanga.lt</b></h4> 
    <p>Renting Company</p> 
  </div>
</div>
	<!-- - - - - - - - - - - - Map - - - - - - - - - - - - -->
	<section>

	<h2 class="atractionh2">Maps</h2>

<div id="map" style="width:100%;height:400px;"></div>

<script>
function myMap() {
  var mapCanvas = document.getElementById("map");
  var mapOptions = {
    center: new google.maps.LatLng(54.686653, 25.278489), zoom: 12
  };
  var map = new google.maps.Map(mapCanvas, mapOptions);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?callback=myMap"></script>
</section>

<!-- - - - - - - - hotels - - - - - - - - -->

<h2 id="booking">Best Booking systems...</h2>
<br>

<div class="row">
  <div class="column">
    <div class="card2">
      <img class="img_hotel" src="images/booking_com.png" alt="booking_com" width="200px" height="200px">
      <div class="container2">
        <h2>Booking.com</h2>
        <p class="title2">Hotels/Hostels</p>
        <p>Most popular booking system in the world</p>
        <p>info@booking.com</p>
        <p><a href="https://www.booking.com/s/35_6/d84a0b86"><button class="button2">Contact</button></a></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card2">
      <img class="img_hotel" src="images/airbnb.jpg" alt="airbnb" width="200px" height="200px">
      <div class="container2">
        <h2>AirBnB</h2>
        <p class="title2">Private Apartmants</p>
        <p>Worlds leader at booking privet apartments</p>
        <p>info@airbnb.com</p>
        <p><a href="https://www.airbnb.com/"><button class="button2">Contact</button></a></p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card2">
      <img class="img_hotel" src="images/besthoteloffers.png" alt="besthoteloffers" width="200px" height="200px">
      <div class="container2">
        <h2>BestHotelOffers.net</h2>
        <p class="title2">Hotels/Hostels</p>
        <p>Big choice of hotels in Vilnius city</p>
        <p>info@BestHotelOffers.net</p>
        <p><a href="https://www.besthoteloffers.net/"><button class="button2">Contact</button></a></p>
      </div>
    </div>
  </div>
</div>
<!-- - - - -  skrolinimo lapo efektas  - - - - - - - - - - -->


<!-- Footeris -->
   <div class="footer">
    <a href="https://www.facebook.com/vilnius.lt/" class="fa fa-facebook"></a>
<a href="https://twitter.com/vilniustourism" class="fa fa-twitter"></a>
<a href="https://plus.google.com/communities/105415866195184932896" class="fa fa-google"></a>
<a href="https://www.linkedin.com/company/ivinius-lt" class="fa fa-linkedin"></a>
<a href="https://www.youtube.com/channel/UCoomf0ord35L8nQcpP4kBkw" class="fa fa-youtube"></a>
<a href="https://www.instagram.com/vilniusofficial/" class="fa fa-instagram"></a>
   </div>
   		<script type="text/javascript" src="assets/js/costom.js"></script>
 </body>
</html>
