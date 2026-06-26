# !DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>FastTrack Express</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f4f7fc;
}

header{
background:#0d47a1;
color:white;
padding:20px;
text-align:center;
}

nav{
background:#1565c0;
padding:15px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:20px;
font-size:18px;
}

.hero{
text-align:center;
padding:60px;
}

.hero h1{
font-size:40px;
}

.track-box{
background:white;
width:400px;
margin:auto;
padding:30px;
border-radius:15px;
box-shadow:0 0 15px gray;
}

input{
width:90%;
padding:12px;
font-size:18px;
margin-top:15px;
}

button{
padding:12px 25px;
margin-top:20px;
background:#0d47a1;
color:white;
border:none;
border-radius:8px;
font-size:18px;
cursor:pointer;
}

.status{
margin-top:25px;
font-size:22px;
color:green;
}

footer{
background:#0d47a1;
color:white;
padding:20px;
text-align:center;
margin-top:60px;
}

</style>

</head>

<body>

<header>

<h1>FASTTRACK EXPRESS</h1>

<p>Worldwide Shipping Services</p>

</header>


<nav>

<a href="#">Home</a>

<a href="#">Track</a>

<a href="#">Services</a>

<a href="#">Contact</a>

</nav>



<div class="hero">

<h1>Track Your Shipment</h1>


<div class="track-box">


<input type="text"
id="tracking"
placeholder="Enter Tracking Number">


<br>


<button onclick="trackPackage()">

Track Package

</button>


<div class="status"

id="status">

</div>


</div>

</div>



<footer>

Phone : +1 800 555 1234

<br>

Email : support@fasttrackexpress.com

</footer>



<script>

function trackPackage(){

let num=document.getElementById("tracking").value;

let status=document.getElementById("status");


if(num=="FT123456789"){

status.innerHTML=
"📦 In Transit<br>Expected Delivery: Tomorrow";

}

else if(num=="FT987654321"){

status.innerHTML=
"✅ Delivered";

}

else{

status.innerHTML=
"❌ Tracking number not found";

}

}

</script>

</body>

</html>


<script>

function trackPackage(){

let num=document.getElementById("tracking").value;

let status=document.getElementById("status");


if(num=="FT123456789"){

status.innerHTML=
"📦 In Transit<br>Expected Delivery: arrived";

}

else if(num=="FT987654321"){

status.innerHTML=
"✅ Delivered";

}

else{

status.innerHTML=
"❌ Tracking number not found";


<meta name="google-site-verification" content="YOUR_VERIFICATION_CODE">

}

}

</script>