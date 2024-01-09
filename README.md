<!DOCTYPE html>
<html lang="en">
<head>
<title>Landing cSS</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Header -->
<header class="w3-display-container w3-center" style="max-width:1500px">
  <img class="1" src="./images.jfif" alt="Me" width="700" height="500">
  <div class="1-display-middle 1-padding-large 1-border 1-wide 1-text-light-grey 1-center"></div>
    <h1 class="1-hide-medium 1-hide-small 1-xxxlarge">JANE DOE</h1>
    <h5 class="1-hide-large" style="white-space:nowrap">JANE DOE</h5>
    <h3 class="1-hide-medium 1-hide-small">PHOTOGRAPHER</h3>
  </div>
  
  <!-- Navbar (placed at the bottom of the header image) -->
  <div class="1-bar 1-light-grey 1-round 1-display-bottommiddle 1-hide-small" style="bottom:-16px">
    <a href="#" class="1 1-button">Home</a>
    <a href="#portfolio" class="1-bar-item 1-button">Portfolio</a>
    <a href="#contact" class="1-bar-item 1-button">Contact</a>
  </div>
</header>


<div class="w3-content w3-padding-large w3-margin-top" id="portfolio">

  <!-- Images (Portfolio) -->
  <img src="./image2.jfif" alt="Ocean" class="w3-image" width="1000" height="500">
  <img src="./image3.jfif" alt="Ocean II" class="w3-image w3-margin-top" width="1000" height="500">
  <img src="./images4.jfif" alt="Falls" class="w3-image w3-margin-top" width="1000" height="500">
  <img src="./images5.jfif" alt="Skies" class="w3-image w3-margin-top" width="1000" height="500">
  <img src="./images6.jfif" alt="Mountains" class="w3-image w3-margin-top" width="1000" height="500">

  
<!--End page content -->



</style>

</head>
<body><br><br>
<center>


<form>
    

<fieldset>
 <legend style="text-align: center;">Personal Data</legend>

 <label for="fn">First Name</label><br>
 <input type="text" id="fn" name="fname" placeholder="first name"><br><br>

 <label for="ln">Last Name</label><br>
 <input type="text" id="ln" name="lname" placeholder="last name"><br>
 <p>CNIC:</p>

 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 -
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
 <input type="text"  style="width: 10px; padding: 3px">
-
 <input type="text"  style="width: 10px; padding: 3px"><br><br>



 <label for="sl">Social Link</label><br>
 <input type="text" id="sl" name="sociallink"  placeholder="Enter Facebook/Linkdin Profile"><br><br>
<div class="row">

 
</fieldset>
</form>
</center>

</div>

</body>
</html>


CSS FILE

a{
    display: block;
    padding: 0 28px;
    color: #fff;
    text-decoration: none;
}

.active a{
    background-color: #10869b;
}

fieldset{
text-align: left;
  width: 40%;
  border: 2px solid rgb(139, 134, 134);
  font-family: Arial, Helvetica, sans-serif;
  background-color: ;
}

input[type]{
width: 50%;
padding: 3px
}

legend{
font-size: large;
border: 2px solid rgb(139, 134, 134);
background-color: rgb(150, 118, 59);
}
.row {
display: flex;
}














