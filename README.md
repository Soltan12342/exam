*
{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}
.banner
{
    width: 100%;
    height: 100vh;
  background-size: cover;
  background-position: center; 
  background-image: url(Rectangle.png)
}


.navbar
{
    width: 85%;
    margin: auto;
    padding: 35px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.navbar ul li
{
    list-style: none;
    display: inline-block;
    margin: 0 20px;
}
.navbar ul li a
{
    text-decoration: none;
    color: #000000;
    text-decoration: uppercase;
}
.content
{
    width: 100%;
    position: absolute;
    top: 50%;
    transform:translateY(-50%);
    text-align: center;
}
button
{
    width: 200px;
    padding: 15px 0;
    text-align: center;
    margin: 20px 10px;
    border-radius:25px;
    font-weight: bold;
    border: 2px solid rgb(255, 85, 0); 
    background: transparent;
    color:#fff ;
    cursor: pointer;
    position: relative;
    overflow: hidden;
}
span 
{
    background: rgb(255, 85,0);
    height: 100%;
    width: 100%;
    border-radius: 25px;
    position: absolute;
    left: 0;
    bottom: 0;
    z-index: -1;
    transition: 0.5s;
}
button:hover span{
    width: 100%;
}
button:hover{
    border: none;
}
.foto
{
background-color: #000000;
}
css

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    
    <div class="banner">
<img src="Rectangle-6.png" class="logo">
<img src="Rectangle-3.png"class="foto">
<img src="Rectangle-4.png"class="foto">
<img src="Rectangle-5.png"class="foto">
        <div class="navbar">
   
   <ul>
    <li><a href="#">ELECTRIC SKATEBOARD</a></li>
    <li><a href="#">ELECTRIC SCOOTERS</a></li>
    <li><a href="#">ACCESSORIES</a></li>
    <li><a href="#">GIFT CARD</li>
    <li><a href="#">MORE INFO</a></li>
    
</ul>
        </div>
        <div class="content">
<h1>Welcome TO Boosted USA</h1>
<p>The Holy Grail of Electric Skateboards and One REVolutionary Scooter</p>
<div>
    <button type="button"><span></span> BOOSTED REVS</button>
    <button type="button"><span></span> BOOSTED BOARDS</button>
</div>      
</div>
    </div>
   
</body>
</html>
