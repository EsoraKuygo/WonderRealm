<!DOCTYPE html>
<html>
<meta charset:"UTF-8">
<head>
  <title>INANA LA BEST</title>
<style>
a{
  color: black;
  font-style: normal;
  text-decoration: none;
}

p{
display: block;
margin : auto;
text-align: center;
}

body{
background-image: url("ishtar.jpeg");
background-size: cover;
background-color: transparent;
}

h1{
text-align: center;
color: white;
}

.hide{
 display: none;

}
.myDIV{
 color: white;
 text-align: center;
}

.myDIV:hover + .hide {
  display: block;
  color: red;
  text-align: center;
}

#myProgress {
  width: 100%;
  background-color: #ddd;

}

#myBar {
  width: 10%;
  height: 30px;
  background-color: #4CAF50;
  text-align: center;
  line-height: 30px;
  color: white;
}
map{
    display: block;
    margin: 0 auto;
    color: white;
}

img {
    display: block;
    margin: 0 auto;
    width: 260px;
    height: 232px;
}

/*footer*/
#footer{
position: absolute ;
left: 0;
right: 0;
background-color: rgb(109, 4, 133) ;
padding: 4px;
opacity: .4;
border: 5px;
border-color: rgb(45, 10, 56);
border-style: dashed;
}

#footer:hover{
  opacity:1.0;
}


#Pdroite{
padding-top: 55px;
margin-left: 60px;
padding-right: 125px;
color: black;
text-align: left;
font-style: italic;
font-family: sans-serif;
font-size: 35px;
float: left;
opacity: 1.0;
}

#Pmid{
padding-top: 2px;
text-align: center;
float: right;
float: left;
}
#Pmid img{
  opacity: 1.0;
  width: auto;
  heigh: auto;
  vertical-align: middle;
  border:5px solid black;
  border-radius: 50%;
}

.huerotate {
  filter: hue-rotate(180deg);
}

#Pleft{
padding-top: 55px;
margin-right: 60px;
color: black;
text-align: left;
text-decoration: underline;
font-family: sans-serif;
font-size: 35px;
float: right;
opacity: 1.0;
}
#Pleft2{
  padding-top: 6px;
  margin-right: 275px ;
  color: black;
  text-align: left;
  font-style: italic;
  font-family: sans-serif;
  font-size: 25px;
  float: right;
  opacity: 1.0;
}

nav{
    width: 100%;
    margin: 0 auto;
    background-color: rgb(107, 55, 250);
    position: sticky;
    top: 0px;
}

nav ul{
    list-style-type: none;
}

nav ul li{
    float: left;
    width: 25%;
    text-align: center;
    position: relative;
}

nav ul::after{
    content: "";
    display: table;
    clear: both;
}

nav a{
    display: block;
    text-decoration: none;
    color: black;
    border-bottom: 2px solid transparent;
    padding: 10px 0px;
}

nav a:hover{
    color: orange;
    border-bottom: 2px solid gold;
}

.sous{
    display: none;
    box-shadow: 0px 1px 2px #CCC;
    background-color: rgb(130, 84, 255);
    position: absolute;
    width: 100%;
    z-index: 1000;
}
nav > ul li:hover .sous{
    display: block;
}
.sous li{
    float: none;
    width: 100%;
    text-align: left;
}
.sous a{
    padding: 10px;
    border-bottom: none;
}
.sous a:hover{
    border-bottom: none;
    background-color: RGBa(200,200,200,0.1);
}
.deroulant > a::after{
    content:"▼";
    font-size: 12px;
}

.conteneur{
  margin: 50px 20px;
  height: 1500px;
}
</style>
</head>


<body>
<!--bande haut de pages-->
  <nav>
  <ul>
    <li class="deroulant"><a href="#">Mythologie Sumerienne &ensp;</a>
      <ul class="sous">
        <li><a href="#">Ishtar</a></li>
        <li><a href="#">Ereshkigal</a></li>
        <li><a href="#">Gilgamesh</a></li>
      </ul>
    </li>
    <li class="deroulant"><a href="#">Syo &ensp;</a>
      <ul class="sous">
        <li><a href="#">Déesse</a></li>
        <li><a href="#">Elfes et aberation</a></li>
        <li><a href="#">Chasseur de primes</a></li>
      </ul>
    </li>
    <li class="deroulant"><a href="#">Nisoma &ensp;</a>
      <ul class="sous">
        <li><a href="humain.html">Humain</a></li>
        <li><a href="#">Robots</a></li>
     </ul>
   <li>
     <li class="deroulant"><a href="#">Ermobs &ensp;</a>
       <ul class="sous">
         <li><a href="#">Uya Simo</a></li>
         <li><a href="#">Hata Simo</a></li>
         <li><a href="#">Fukawa S</a> </li>
      </ul>
    <li>
</nav>


<br>
<h1>INANA devient mieux que sa soeur...</h1>
<!--bar de progress -->
<div id="myProgress">
  <div id="myBar">2%</div>
</div>

<br/>
<p>
<button onclick="move()">Attention</button>

<div class="myDIV">est ce que c'est vrai?</div>
<div class="hide">Evidement t retard ou bien?</div>
</p>

<!--imagemap mid-->
<img alt="inana" src="ina.png" usemap="#inanam"  width="400" height="379">

<map name="inanam">
    <area shape="rect" coords="400,0 ,320, 0"   href="https://google.com" target="_blank" alt="Mozilla" />
    <area shape="circle" coords="100,100,200" alt="Cup of coffee" href="coffee.htm">
<hr>
</map>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas eget aliquam orci. Praesent lorem lacus, aliquet sit amet lorem ut, luctus semper ligula. Donec dapibus odio ex, et bibendum risus euismod eget. Proin vestibulum urna vitae pulvinar fringilla. Curabitur interdum gravida massa, at sagittis odio finibus ac. Nulla semper risus sit amet justo ultrices convallis. Vivamus placerat mi sapien, nec auctor lorem commodo nec. Quisque pulvinar enim et orci tincidunt porttitor. Curabitur dapibus ut augue feugiat iaculis. Morbi erat ante, lobortis at lectus vel, elementum faucibus nulla. Vivamus ultrices dapibus tortor, vitae posuere lorem pulvinar vitae. Praesent maximus pulvinar neque eu egestas. Phasellus ut nisi aliquam, varius justo ac, volutpat erat. Pellentesque fermentum odio mi, vel accumsan quam tempor eget. Integer feugiat, velit gravida varius efficitur, risus felis aliquam ipsum, tempus aliquet ipsum urna nec dolor.
<br>
Sed sit amet diam orci. Curabitur rhoncus lacus vel orci sollicitudin vehicula. Aenean et viverra est. Cras lorem est, dictum et aliquet non, commodo in dolor. Vestibulum congue justo mi, in euismod arcu congue id. Cras sollicitudin dapibus blandit. Aliquam vestibulum lectus quis hendrerit faucibus. Proin a tellus pharetra, iaculis lorem ut, vehicula risus. Nulla convallis nisi accumsan mauris ullamcorper, a blandit nisi faucibus. Mauris at est vel elit sollicitudin egestas et et ex. Sed accumsan tempus risus ut lobortis. In rutrum risus sit amet volutpat porttitor.
<br>
Vivamus placerat sodales orci, sit amet maximus lectus viverra congue. Nullam ullamcorper, lectus quis consectetur bibendum, tellus arcu euismod sapien, ac venenatis metus nisi id felis. Praesent purus leo, suscipit ut vestibulum at, consequat non magna. Nam at erat vel arcu efficitur sollicitudin. Suspendisse efficitur, mi in fermentum condimentum, augue nisl semper felis, non auctor ligula elit in mauris. Sed semper, metus id egestas pretium, nisl erat aliquam nunc, non accumsan magna mi imperdiet dui. Donec pellentesque sapien ac urna faucibus placerat. Proin fringilla lorem libero, non molestie lectus scelerisque ut. Sed scelerisque nisl in quam euismod, at placerat justo posuere. Phasellus ac scelerisque tortor. Maecenas suscipit dolor nec ligula rutrum pharetra. Sed rhoncus velit quis erat ultrices efficitur. Nullam a egestas enim. Integer sit amet lobortis nibh.
<br>
Nunc ullamcorper purus ut dictum condimentum. Maecenas dapibus tincidunt tempus. Fusce commodo dictum arcu. Pellentesque mollis ligula at magna varius, sit amet placerat metus blandit. In dignissim enim nisi, tempor commodo enim tempor non. Morbi eu malesuada nunc, eget cursus lectus. Pellentesque pellentesque dui eget ornare rhoncus. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nulla euismod cursus sapien, a fermentum leo varius nec. Curabitur sit amet est mattis, elementum mi non, vulputate nisl.
<br>
Aliquam iaculis, nisl eu eleifend commodo, purus est malesuada orci, vitae mollis sapien nunc ut nunc. Nulla odio nunc, vehicula vitae placerat sed, blandit vitae odio. Morbi dignissim ante sed eros aliquet, ac facilisis elit aliquet. Duis faucibus tellus non nibh viverra cursus. Suspendisse faucibus tellus ut neque lobortis ullamcorper. Sed fermentum ex sit amet est porttitor lobortis id a quam. Sed vel eros nec metus malesuada commodo. Maecenas scelerisque, mi sit amet aliquet malesuada, dui eros porttitor magna, non feugiat quam mi vitae justo. Nam metus mauris, tempor quis eleifend nec, fermentum non ex. Sed velit ipsum, luctus et ligula at, luctus cursus risus. Proin commodo luctus ultricies. Integer fermentum posuere elit vel gravida.</p>
<hr>
<!--bande pieds de page-->

<div id="footer">
<p id="Pdroite">Besoin d'aide? <br>Nous pouvons vous aidez! <br>Joignez vous a nous ^^  </p>
<p id="Pmid"> <img class="huerotate"src="i-con.gif" alt="ishtar est bg"> </p>
<p id="Pleft">Venez sur nos reseaux sociaux</p>
<p id="Pleft2"><a href="https://www.instagram.com/esora_kyugo/" target="_blank">instagram</a>
        <br> <a href="https://www.facebook.com/esora.kyugo/"  target="_blank">facebook </a>
        <br> <a href="https://twitter.com/esorakyugo?lang=fr"  target="_blank">tweeter </a>
        <br><a href="esora.kyugo.com"  target="_blank">spotify</a> <br> </p>
</div>

<!--skript-->

<script>


var i = 0;
function move() {
  if (i == 0) {
    i = 1;
    var elem = document.getElementById("myBar");
    var width = 10;
    var id = setInterval(frame, 2);
    function frame() {
      if (width >= 100) {
        clearInterval(id);
        i = 0;
      } else {
        width++;
        elem.style.width = width + "%";
        elem.innerHTML = width  + "%";
      }
    }
  }
}
</script>

</body>

</html>
