<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon.Spend less.Smile more</title>
    <style>
        *{
    margin:0;
    padding:0;
    border:border-box;
    font-family: 'Arial';
}
body{
    background-color:rgb(200, 200, 200);

}
.navbar{
    height:60px;
    width:100%;
    display: flex;
    background-color: #0f1111;
    color:white;
    z-index:10;
}
.logo{
    background-image: url("amazon_logo.png");
    background-size: cover;
    width:110px;
    height:50px;
    margin:1px;
    padding: 0px 6px;
}
.border{
    border:1.5px solid transparent;
}
.border:hover{
    border:1.5px solid white;
}
.add-icon{
    display: flex;
}
.nav-add{
    padding:0px 8px 0px 3px;
    margin-top:10px;
    height:40px;
}
#india{
    margin-left: 5px;
    font-weight:bold;
    font-size:14px;;
}
#deliver{
    margin-left:15px;
}
.nav-search{
    display:flex;
    width:630px;
    align-items: center;
    height:40px;
    
    padding:9px 1px;
}
.nav-input:hover{
    border:2px solid orange;
}
select{
    height:37px;
    border-radius: 5px 0px 0px 5px;

}
.nav-dropdown:hover{
    border:2px solid orange;

}
.nav-input input{
    padding:9px 330px 11px 10px;
    border:none; 
}
.search-icon{
    display: flex;
    justify-content: center;
    height:36px;
    width:45px;
    background-color: chocolate;
    border-radius: 0px 5px 5px 0px;
}
.search-icon i{
    font-size:22px;
    margin-top:5px;
    padding-left:0px 5px;
    color: #0f1111;  
}
.country{
    display: flex;
    margin-top:5px;
    align-items: center;
    height:45px;
}
.country-icon{

    background-image: url("R.jpeg");
    background-size: cover;
    height:16px;
    margin-right:5px;
    margin-left:15px;
    width:21px;
}
.country-icon img{
    height:16px;
    width:21px;
}
.country p{
    font-size:14px;
    margin-right:3px;
}
.hello{
    height:40px;
    margin-top:5px;
    padding-top:7px;
    margin-left: 10px;
    padding-right:5px;
    padding-left:5px;
}
#hello{
    font-size:12px; 
}
#accounts{
    font-size:14px;
    font-weight:bold;
}
.cart i{
    font-size:35px;
}
.cart{
    display:flex;
    margin-left:10px;
    margin-top:5px;
    padding-top:8px;
    height:40px;
    width:80px;
}
.cart p{
    font-weight:bold;
    margin-top:15px;
}
.sidebar{
    height:40px;
    width:100%;
    display: flex;
    background-color:#1d2424;
    opacity:0.9;
    color: white;
    align-items: center;
}
a{
    text-decoration:none;
    color: white;
    margin-right:10px;
}
.menu{
    display:flex;
}
.menu a{
    padding:10px 9px 8px 9px;
    font-size: 14px;
}
.menu i{
    padding:6px 0px 6px 9px;
    font-size:20px;
}
.menu-item a{
    padding:8px 5px;
    font-size: 14px;
}
.menu-item{
    display: flex;
    width:950px;
}
.menu-link{
    padding:5px 10px ;
    margin-left:25px;
}
.main{
    background-image:url("background-image.jpg");
    background-size: cover;
    height:600px;
    display:flex;
    flex-wrap: wrap;
}
.amazon.in{
    padding:10px 14px;
    height:30px;
    width:1150px;
    margin-left:40px;
    font-size:14px;
    display: flex;
    justify-content: center;
    align-items:center;
    background-color: white;
}
.amazon.in p a{
    color:#2162A1;
    font-size:14px;
}
.cards{
    display: flex;
    flex-wrap: wrap;
}
.card{
    height:400px;
    width:290px;
    margin:20px 2px 0px 20px ;
    margin-right:3px;
    background-color: white;
    color:black; 
}
.card-img{
    height:300px;
    width: 260px;
    object-fit:cover;

}
.card h2{
    margin:15px 0px 10px 15px;
    font-size:20px;
}
.card a{
    color: #2162A1;
    text-decoration:none;
    margin-left:15px;
    
}
.card-img img{
    height:290px;
    width: 260px;
    margin-left:15px;
}
.four-card-img{
    height:300px;
    width:260px;
    display: flex;
    flex-wrap:wrap;
}
.img1{
    width:100px;
    height:120px;
    margin:10px;
    margin-left:20px;
}
.img1 img{
    width:100px;
    height:100px;
    object-fit:cover;

}
.img1 p{
    margin-top:5px;
    font-size:12px;
}

.long-div{
    height:300px;
    width:1230px;
    background-color:white;
    margin:20px 20px 5px 20px;
  
}
.long-div h2{
    margin-top:20px;
    margin-left:15px;
}
.sellers{
    display: flex;
    height:220px;
    object-fit: cover;
    margin-top:20px;
}
.sellers img{
    height:220px;
    width: 220px;
    margin-left:20px;
}
.history{
    height:760px;
    width:1225px;
    background-color:white;
    margin:10px 20px 0px 20px;
}
.item{
    width:1220px;
    height:320px;
    display: flex;
    margin-bottom:170px;

}
.items{
    width:170px;
    height:320px;
    margin:10px;
    margin-left:15px;
}
.first{
    margin-left:80px;
}

.items img{
    width:170px;
    height:170px;
    margin-bottom:10px;

}
.lines{
    height:50px;
    width:1260px;
}
.line{
    height:0.1px;
    width:1200px;
    margin-left:12px;
    opacity: 0.1;
    border:0.5px solid black;
}
.items a{
    text-decoration:none;
    color: #2162A1;
}
.items a:hover{
    text-decoration:underline;
}
.items p{
    margin-top:10px;
    font-size:23px;
    color:darkorange;
}
.items p a{
    font-size: 13px;
}
#offer{
    font-size:14px;
    color:black;
    margin-top: 10px;
    opacity:0.8;
}
#offer:hover{
    text-decoration: underline;
}
.history h3{
    margin:15px 0px 20px 40px;
    
}
.sign-in{
    margin:20px 10px;
    text-align:center;
    height: 100px;
}
.sign-in h2{
    margin-bottom: 15px;
}
.sign-in #sign{
    padding:10px 50px;
    border-radius:25px;
    background-color:rgb(253, 184, 57);
    color:black;
}
.sign-in #start{
    color:#2162A1;
    text-decoration: underline;
}
.sign-in div{
    font-size:12px;
    margin-top:15px;
}
.greater{
    height:360px;
    width:50px;
    display: flex;
    justify-content:center;
    align-items:center;
}
.great{
    border-radius:10px;
    height:20px;
    width:20px;
    padding:10px;
    display: flex;
    font-weight:bold;
    justify-content:center;
    align-items:center;
    border:0.5px solid black;
    margin-left:50px;
}
.great i{
    color:black;
}
#overing:hover{
    text-decoration:underline;
}
.his-head p{
    margin-top:10px;
    font-size:14px;
}
.his-head{
    color: black;
    display:flex;
    justify-content: space-between;
}
.back{
    height:50px;
    width:1225px;
    background-color:#232f3E;
    opacity: 0.8;
    margin-top:0px;
    margin-left:20px;
}
.back{
    color:white;
    display: flex;
    align-items: center;
    justify-content:center;
}
.horizontal-div{
    height:350px;
    background-color:#232F3E;
    width:1220px;
    display:flex;
    margin-left:20px;
    padding-top:50px;
    padding-left:5px;
}
.pad{
    padding:0px 10px;
}
.get{
    width:133px;
    height:300px;
}
.space{
    width:95px;
    height:300px;
}
.get ul{
    list-style:none;
}
.get p{
    margin:6px 0px 16px 0px;
    color:#fff;
}
.get ul li a{
    font-size:14px;
    color:#DDD;
}
.get ul li a:hover{
    text-decoration:underline;
}
.get ul li{
    margin-bottom:10px;
}
.end-amazon{
    height: 90px;
    width:1225px;
    margin-left:20px;
    background-color:#232F3E;
    display: flex;
    justify-content: center;
    align-items:center;
}
.ama-img{
    background-image:url("amazon_logo.png");
    background-size: cover;
    width: 80px;;
    height:50px;
    margin-right:100px;
}
.end-amazon i{
    color:#DDD;
}
.ama-box{
    font-size:14px;
    border-radius:3px;
    padding:5px;
    border:1px solid #DDD;
    margin-left:10px;
}
.usd{
    background-image: url("USD.jpeg");
    background-size: cover;
    height:14px;
    width:18px;

}
.footer{
    background-color:#131A22;
    height:350px;
    width:1225px;
    margin-left:20px;
    display:flex;
    flex-wrap: wrap;
    padding:30px 0px;
}
.music{
    width:1075px;
    display:grid;
    grid-template-rows:repeat(4,1fr);
    grid-template-columns:repeat(7,1fr);
}
.foot{
    padding:0px 9px;
    margin-right:10px;
}
.foot h5{
    font-size:12px;
    color: #DDD;
    margin-bottom:2px;
    opacity: 0.9;
}
.foot span{
    font-size:12px;
    color:#999;
}
.empty{
    height:380px;
    width:75px;
}
.foot span:hover{
    text-decoration:underline;
}
.foot h5:hover{
    text-decoration:underline;
}
.terms{
    margin-left:20px;
    height:50px;
    width:1225px;
    display: flex;
    color:#DDD;
    font-size:12px;
    text-align: center;
    background-color:#131A22;
    padding:20px 0px 30px;
}
.terms p{
    margin: auto;
}
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" href="amazon-icon.jpg">
</head>
<body>
    <header>
    <div class="navbar">
        <div class="navbar-logo">
            <div class="logo border">
            </div>
        </div>
        <div class="nav-add border">
            <p id="deliver">Deliver to</p>
            <div class="add-icon">
                <i class="fa-solid fa-location-dot"></i>
                <p id="india">India</p>
            </div>
        </div>
        <div class="nav-search">
            <div class="nav-dropdown">
                <select class="dropdown" id="dropdown">
                    <option value="All">All</option>
                    <option value="Books">Books</option>
                    <option value="Electronics">Electronics</option>
                    <option value="Clothing">Clothing</option>
                </select>
            </div>
            <div class="nav-input">
                <input type="text" id="search" placeholder="Search Amazon.in">
            </div>
            <div class="search-icon">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
        </div>
        <div class="country border">
            <div class="country-icon">
            </div>
            <p>EN</p>
            <i class="fa-solid fa-caret-down"></i>
        </div>
        <div class="hello border">
            <p id="hello"><span>Hello ,sign in</span></p>
            <p id="accounts">Accounts & Lists  <i class="fa-solid fa-caret-down"></i></p>
        </div>
        <div class="hello border">
            <p id="hello"><span>Returns</span></p>
            <p id="accounts">& Orders</p>
        </div>
        <div class="cart border">
            <i class="fa-solid fa-cart-shopping"></i>  
            <p>cart</p>    
      </div>   
    </div>
    <div class="sidebar">
        <div class="menu border">
            <i class="fa-solid fa-bars"></i>
            <a href="#">All</a>
        </div>
        <div class="menu-item">
            <a href="https://www.amazon.com/gp/goldbox?ref_=nav_cs_gb" class="border">Today's Deals</a>
            <a href="https://www.amazon.com/registries?ref_=nav_cs_registry&ref_=nav_cs_registry" class="border"> Registry</a>
            <a href="https://www.amazon.com/gp/help/customer/display.html?nodeId=508510&ref_=nav_cs_customerservice" class="border">Customer Service</a>
            <a href="https://www.amazon.com/gift-cards/b/?ie=UTF8&node=2238192011&ref_=nav_cs_gc" class="border">Gift Cards</a>
            <a href="https://www.amazon.com/b/?_encoding=UTF8&ld=AZUSSOA-sell&node=12766669011&ref_=nav_cs_sell" class="border">Sell</a>
        </div>
        <div class="menu-link border">
            <a href="https://www.amazon.in/s?k=electronics">Shop deals in Electronics</a>
        </div>
        </div>
    </header>
    <div class="main">
        <div class="shinde" style="display: flex; justify-content:space-between; width:1220px">
            <div class="greater">
                <div class="great" onclick="changeBackground();" ><i class="fa-solid fa-less-than"></i></div>
             </div>
             <div class="greater">
                <div class="great" onclick="changeBackground();"><i class="fa-solid fa-greater-than"></i></div>
             </div>
        </div>
        <div class="amazon in">
        <p>You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery.  <a href="https://www.amazon.in/">click here to go to amazon.in</a></p></div>
        <div class="cards">
            <div class="card">
                <h2>Get your game on</h2>
                <div class="card-img">
                    <img src="fullone.jpg" alt="one">
                </div>
                <a href="server">Shop gaming</a>
            </div>
            <div class="card">
                <h2>Toys under $25</h2>
                <div class="card-img">
                    <img src="full.two.jpg" alt="second">
                </div>
                <a href="server">show now</a>
            </div>
            <div class="card">
                <h2>New home arrivals under $50</h2>
                <div class="four-card-img">
                    <div class="img1">
                        <img src="kitchen.jpg" alt="kitchen">
                        <p>Kitchen & dining</p>
                    </div>
                    <div class="img1">
                        <img src="home.jpg" alt="help">
                        <p>Home improve</p>
                    </div>
                    <div class="img1">
                        <img src="decor.jpg" alt="deliver">
                        <p>Decor</p>
                    </div>
                    <div class="img1">
                        <img src="bedding.jpg" alt="bath">
                        <p>bedding & bath</p>
                    </div>
                </div>
                <a href="server">See all deals</a>
            </div>

            <div class="card">
                <h2>Fill your basket with joy</h2>
                <div class="card-img">
                    <img src="full.three.jpg" alt="second">
                </div>
                <a href="server">Shop for Easter</a>
            </div>
           
        <div class="long-div">
            <h2>Best Sellers in Computer & Accessories</h2>
            <div class="sellers">
                <img src="seller1.jpg" alt="sellers">
                <img src="seller2.jpg" alt="sellers">
                <img src="seller3.jpg" alt="sellers">
                <img src="seller4.jpg" alt="sellers">
                <img src="seller5.jpg" alt="sellers">
            </div>
        </div>
        <div class="card">
            <h2>Shop deals in Fashion</h2>
            <div class="four-card-img">
                <div class="img1">
                    <img src="ladies-shirt.jpg" alt="kitchen">
                    <p>Jeans under $50</p>
                </div>
                <div class="img1">
                    <img src="ladies-pant.jpg" alt="help">
                    <p>Tops under $25</p>
                </div>
                <div class="img1">
                    <img src="full.four.jpg" alt="deliver">
                    <p>Dresses under $30</p>
                </div>
                <div class="img1">
                    <img src="full.five.jpg" alt="bath">
                    <p>Shoes under $50</p>
                </div>
            </div>
            <a href="server" style="margin-top: 15px;">See all deals</a>
        </div>
        <div class="card">
            <h2>Top Video Games</h2>
            <div class="card-img">
                <img src="minecraft.jpg" alt="second">
            </div>
            <a href="server">See all video games</a>
        </div>
        <div class="card">
            <h2>Gear up to get fit</h2>
            <div class="four-card-img">
                <div class="img1">
                    <img src="clothing.jpg" alt="kitchen">
                    <p>Clothing</p>
                </div>
                <div class="img1">
                    <img src="trackers.jpg" alt="help">
                    <p>Trakers</p>
                </div>
                <div class="img1">
                    <img src="equpment.jpg" alt="deliver">
                    <p>Equipment</p>
                </div>
                <div class="img1">
                    <img src="deals.jpg" alt="bath">
                    <p>Deals</p>
                </div>
            </div>
            <a href="server">Discover more</a>
        </div>
        <div class="card">
            <h2>PCs & Accessories</h2>
            <div class="four-card-img">
                <div class="img1">
                    <img src="desktops.jpg" alt="kitchen">
                    <p>Desktops</p>
                </div>
                <div class="img1">
                    <img src="laptop.jpg" alt="help">
                    <p>Laptops</p>
                </div>
                <div class="img1">
                    <img src="hard drives.jpg" alt="deliver">
                    <p>Hard Drives</p>
                </div>
                <div class="img1">
                    <img src="pc.jpg" alt="bath">
                    <p>PC Accessories</p>
                </div>
            </div>
            <a href="server">See more</a>
        </div> 
    </div>
        <div class="long-div">
            <h2>More items to consider &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="#" style="text-decoration: none; color:#2162A1; font-size:14px;">See more</a></h2>
            <div class="sellers">
                <img src="wine1.jpg" alt="sellers">
                <img src="wine2.jpg" alt="sellers">
                <img src="wine3.jpg" alt="sellers">
                <img src="wine4.jpg" alt="sellers">
                <img src="wine5.jpg" alt="sellers">
            </div>
        </div>
        <div class="long-div">
            <h2>Most Wished for in Video Games</h2>
            <div class="sellers">
                <img src="game1.jpg" alt="sellers">
                <img src="game2.jpg" alt="sellers">
                <img src="game3.jpg" alt="sellers">
                <img src="game4.jpg" alt="sellers">
                <img src="game5.jpg" alt="sellers">
            </div>
        </div>
        <div class="history">
            <div class="lines"></div>
            <div class="line"></div>
            <div class="his-head">
            <h3>Customers who viewed items in your browsing history also viewed</h3>
            <p>Page 2 of 5 &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;<a href="#" style="text-decoration: none; color:#2162A1;" id="overing">Start over</a></p>
        
        </div>
            <div class="item">
                <div class="greater">
                    <div class="great"><i class="fa-solid fa-less-than"></i></div>
                 </div>
             <div class="items first">
                <img src="h1.jpg" alt="sellers">
                <a href="https://www.amazon.com/ZELUS-Weighted-Reflective-Strength-Weightlifting/dp/B07518RBH2/">ZELUS Weighted Vest Weight Vest with Reflective Stripe for Workout, Strength Training, Running, Fitness, Muscle Building, Weight Loss, Weightlifting</a>
                <p>&starf;&starf;&starf;&starf;&starf; <a href="#">420</a></p>
                <p id="offer">1 offer from <b>$ 224.99</b></p>
            </div>
                <div class="items">
                <img src="h2.jpg" alt="sellers">
                <a href="https://www.amazon.com/Fit-Simplify-Resistance-Exercise-Instruction/dp/B01AVDVHTI">Fit Simplify Resistance Loop Exercise Bands with Instruction Guide and Carry Bag, Set of 5 , waterproof seal to prevent children from chlorine and</a>
                <p>&starf;&starf;&starf;&star;&star; <a href="#">119</a></p>
                <p id="offer">1 offer from <b>$ 109.99</b></p>
            </div>
                <div class="items">
                <img src="h3.jpg" alt="sellers">
                <a href="https://www.amazon.com/Swim-Goggles-Anti-Fog-Anti-UV-Swimming/dp/B08XQ35T47">Seago Swim Goggles 2 Pack Anti-Fog Anti-UV Wide View Swimming Goggles for Kids 3-15 swimming goggles use soft silicone cushioned frames </a>
                <p>&starf;&starf;&star;&star;&star; <a href="#">62</a></p>
                <p id="offer" style="font-size:20px;"><b>$ 159.95</b></p>
                <p id="offer">$7.5.05 shipping</p>
                <p id="offer">only 7 left in stock</p>
            </div>
                <div class="items">
                <img src="h4.jpg" alt="sellers">
                <a href="https://www.amazon.com/Resistance-Exercise-Bands-Booty/dp/B08DLXZKF7/">Resistance Bands for Working Out, Elastic Exercice Loop Bands for Physical Therapy, Yoga Starter Set of Stretch Bands for Booty Legs, Pilates Flexbands</a>
                <p>&starf;&starf;&starf;&starf;&starf; <a href="#">36</a></p>
                <p id="offer">2 offer from <b>$ 88.19</b></p>

            </div>
                <div class="items">
                <img src="h5.jpg" alt="sellers">
                <a href="https://www.amazon.com/Flashlight-LHKNL-Ultra-Light-Rechargeable-Waterproof/dp/B08D66HCXW">LHKNL Headlamp Flashlight, 1200 Lumen Ultra-Light Bright LED Rechargeable Headlight with White Red Light,2-Pack Waterproof Motion Sensor Head Lamp</a>
                <p>&starf;&starf;&starf;&star;&star; <a href="#">24</a></p>
                <p id="offer">1 offer from <b>$ 11.99</b></p>
            </div>
            <div class="greater">
                <div class="great"><i class="fa-solid fa-greater-than"></i></div>
             </div>
             </div>
             <div class="line"></div>
             <div class="sign-in">
                <h2>See personalized recommendations</h2>
                <a href="https://www.amazon.com/ap/signin?openid.mode=checkid_setup&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0&openid.return_to=https%3A%2F%2Fwww.amazon.com%2Fref%3Drhf_sign_in&openid.assoc_handle=usflex&openid.pape.max_auth_age=0" id="sign">Sign in</a>
                <div class="start">New customer? <a href="https://www.amazon.com/ap/register?openid.mode=checkid_setup&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0&openid.return_to=https%3A%2F%2Fwww.amazon.com%2Fref%3Drhf_sign_in&openid.assoc_handle=usflex" id="start">Start here</a></div>
             </div>
             <div class="line"></div>
        </div>
        <div class="back">
            <a href="http://127.0.0.1:5500/index.html">Back to Top</a>
        </div>
        <div class="horizontal-div">
            <div class="space" style="width:110px"></div>
            <div class="get">
                <p><b>Get to Know Us</b></p>
                <ul>
                    <li><a href="#">Careers</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">About Amazon</a></li>
                    <li><a href="#">Invester Relations</a></li>
                    <li><a href="#">Amazon Devices</a></li>
                    <li><a href="#">Amazon Science</a></li>

                </ul>
            </div>
            <div class="space"></div>
            <div class="get" style="width:185px">
                <p><b>Make to Know Us</b></p>
                <ul>
                    <li><a href="#">Sell products on Amazon</a></li>
                    <li><a href="#">Sell on Amazon Business</a></li>
                    <li><a href="#">Sell apps on Amazon</a></li>
                    <li><a href="#">Become an Affiliate</a></li>
                    <li><a href="#">Advertise Your Products</a></li>
                    <li><a href="#">Self-Publish with Us</a></li>
                    <li><a href="#">Host an Amazon Hub</a></li>
                    <li><a href="#">›See More Make Money with Us</a></li>
                </ul>
            </div>
            <div class="space"></div>
            <div class="get" style="width:225px">
                <p><b>Amazon Payment Products</b></p>
                <ul>
                    <li><a href="#">Amazon Business Card</a></li>
                    <li><a href="#">Shop with Points</a></li>
                    <li><a href="#">Reload Your Balance</a></li>
                    <li><a href="#">Amazon Currency Converter</a></li>
                </ul>
            </div>
            <div class="space"></div>
            <div class="get" style="width:160px">
                <p><b>Let Us Help You</b></p>
                <ul>
                    <li><a href="#">Amazon and COVID-19</a></li>
                    <li><a href="#">Your Account</a></li>
                    <li><a href="#">Your Orders</a></li>
                    <li><a href="#">Shipping Rates & Policies</a></li>
                    <li><a href="#">Returns & Replacements</a></li>
                    <li><a href="#">Manage Your Content and Devices</a></li>
                    <li><a href="#">Help</a></li>
                </ul>
            </div>
            <div class="space" style="width:110px"></div>
        </div>
        <div class="line"></div>
        <div class="end-amazon">
            <div class="ama-img"></div>
            <div class="ama-box">
                <i class="fa-solid fa-globe"></i>
                <a href="https://www.amazon.com/customer-preferences/edit?ie=UTF8&preferencesReturnUrl=%2F&ref_=footer_lang">English</a>
                <i class="fa-solid fa-angle-down"></i>  
        </div>
        <div class="ama-box">
            <p style="color:#DDD;">$ &nbsp;&nbsp;USD-U.S.Dollar</p>
    </div>
    <div class="ama-box" style="display:flex;">
        <div class="usd"></div>
        <p style="color: #DDD;">&nbsp;&nbsp;United States</p>
</div>
 </div>
 <div class="footer">
 <div class="empty"></div>
 <div class="music">
    <div class="foot">
        <h5>Amazon Music</h5>
        <span>Reach customers <br>
            wherever they <br>
            spend their time</span>
    </div> 
    <div class="foot">
        <h5>6pm</h5>
        <span>Score deals <br>
            on fashion brands</span>
    </div> <div class="foot">
        <h5>AbeBooks</h5>
        <span>Books, art <br>
            & collectibles</span>
    </div> 
    <div class="foot">
        <h5>ACX</h5>
        <span>Audiobook <br> Publishing <br>
            Made Easy</span>
    </div> <div class="foot">
        <h5>Sell on Amazon</h5>
        <span>Start a Selling  <br>Account
        </span>
    </div> <div class="foot">
        <h5>
            Veeqo</h5>
        <span>Shipping Software <br>
            Inventory <br> Management</span>
    </div> <div class="foot">
        <h5>Amazon Business</h5>
        <span>Everything For <br>
            Your Business</span>
    </div> <div class="foot">
        <h5>
            AmazonGlobal</h5>
        <span>Ship Orders
            Internationally</span>
    </div> <div class="foot">
        <h5>
            Amazon Web <br> Services</h5>
        <span>Scalable Cloud <br>
            Computing <br> Services
            </span>
    </div> <div class="foot">
        <h5>Audible</h5>
        <span>Listen to Books & <br> Original <br>
            Audio <br> Performances
            </span>
    </div> 
    <div class="foot">
        <h5>
            Box Office Mojo</h5>
        <span>Find Movie <br>
            Box Office Data
            </span>
    </div> <div class="foot">
        <h5>
            Goodreads</h5>
        <span>Book reviews <br>
            & <br> recommendations
            </span>
    </div> <div class="foot">
        <h5>ImDb</h5>
        <span>Movies, TV <br>
            & Celebrities</span>
    </div> <div class="foot">
        <h5>Amazon Music</h5>
        <span>Get Info <br> Entertainment <br>
            Professionals Need
            </span>
    </div> <div class="foot">
        <h5>IMDbPro</h5>
        <span>Stream millions <br>of song</span>
    </div> <div class="foot">
        <h5>
            Kindle Direct <br> Publishing</h5>
        <span>
            Indie Digital & <br> Print Publishing <br>
Made Easy
</span>
    </div> <div class="foot">
        <h5>
            Prime Video Direct</h5>
        <span>Video Distribution <br>
            Made Easy
            </span>
    </div> 
    <div class="foot">
        <h5>Shopbop</h5>
        <span>Designer <br>
            Fashion Brands
            </span>
    </div> <div class="foot">
        <h5>Woot!</h5>
        <span>Deals and <br>
            Shenanigans
            </span>
    </div> <div class="foot">
        <h5>
            Zappos</h5>
        <span>Shoes & <br>
            Clothing</span>
    </div> <div class="foot">
        <h5>eero WiFi</h5>
        <span>Stream 4K Video <br>
            in Every Room</span>
    </div> <div class="foot">
        <h5>
            </h5>
        <span>
            </span>
    </div> 
    <div class="foot">
        <h5>
            Blink</h5>
        <span>Smart Security <br>
            for Every Home
            </span>
    </div> <div class="foot">
        <h5>
            Neighbors App</h5>
        <span>Real-Time Crime <br>
            & Safety Alerts
            </span>
    </div> <div class="foot">
        <h5>
            Amazon <br> Subscription Boxes</h5>
        <span>Top subscription <br> boxes - right to  <br>your door
        </span>
    </div> <div class="foot">
        <h5>PillPack</h5>
        <span>Pharmacy <br> Simplified
        </span>
    </div> 
    <div class="foot">
        <h5>
            Amazon Ads</h5>
        <span>Reach customers <br>
            wherever they <br>
            spend their time
            </span>
    </div> 

    <div class="foot">
        <h5></h5>
        <span></span>
    </div> 
    
</div>
<div class="empty" style="width:100px;"></div>
 </div>
 <div class="terms">
    <p>Conditions of Use &nbsp;&nbsp;&nbsp;Privacy Notice &nbsp;&nbsp;&nbsp;Consumer Health Data Privacy Disclosure  &nbsp;&nbsp;&nbsp;Your Ads Privacy Choices <br>
    &copy; 1996-2025, Amazon.com, Inc.or its affiliates</p>
 </div>
<script>
    let change=true;
   function changeBackground(){
    let main=document.querySelector(".main");
    if(change){
        main.style.backgroundImage = "url('back1.jpg')";
        change=false;
    }
    else{
        main.style.backgroundImage = "url('back2.jpg')";
        change=true;

    }
   }
</script>
</body>
</html>
