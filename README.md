<!DOCTYPE html>
<html>
    <head>
        <title> Welcome to Washington! </title>     
        <link href="./styles/styles.css" rel="stylesheet" type="text/css">
        <link href="https://fonts.googleapis.com/css?family=Playfair+Display" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet">
    <style>
    * {
    font-family: 'Raleway', sans-serif;
    color: #333333;
}

body {
    height: 100%;
}

header {
    line-height: 4rem;
    padding: 5px;
}

a {
    text-decoration: none;
    color: #669966;
}

a:hover {
    color: #FFCC00;
}

.green {
    color: #669966;
}

#hgreen, #green {
    color: #669966;
    font-weight: bold;
}


a:hover#green, a:hover#hgreen  {
    color: #FFCC00;
}

.yellow {
    color: #FFCC00;
}

a:hover h3 {
color: #669966;
}

#hyellow, #yellow {
    color: #FFCC00;
    font-weight: bold;
}

.brown {
    color: #333333;
}

#home {
    font-weight: bold;
}

.nav {
    width: 100%;
    text-align: center;
    background-color: #333333;
    line-height: 3.5rem; 
    position: sticky;/*This value for position fails validation even though it works fine and is on the w3schools website.*/
    top: 0;
}

.nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}
.nav li {
    display: inline;
}

.nav a {
    text-decoration: none;
    text-align: center;
    padding: 14px 16px;
    color: white;
}
  
.nav a:hover {
    color: #FFCC00;
    background-color: #669966;
 }
 
 #hnav {
     background-color: #FFCC00;
 }

#gnav {
    background-color: #669966;
}

h1.heading {
    display: inline;
}

.mheading {
    font-family: 'Playfair Display', serif;
    font-size: 2.5rem;
    margin-top: 10px;
}

.heading, .mpheading {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
}

.content, .mpcontent {
    font-size: 1.15rem;
}

.mpcontent {
    padding: 5px;
    margin-bottom: 15px;
}

li {
    margin-bottom: 0.5rem;
    width: 75%;
}

.list ul {
    border-left: 1px solid #333333;
}

table {
    width: 100%;
}

.home {
    width: 50%;
    vertical-align: top;
    padding: 5px;
}

td {
    width: 33%;
    margin: 10px;
    padding: 5px;
    vertical-align: top;
}

.list {
    font-size: 1.15rem;
    padding: 5px;
}

.padding{
        margin: 35px 0px;
}

h3 {
    font-family: 'Playfair Display', serif;
}

.width {
    width: 75%;
    margin-left: 0;
    padding: 5px;
}

hr {
    margin-left: 0;
    width: 75%;
    
}

.search {
    float: right;
}

input {
    border: 1px solid #333333;
    padding: 10px;
}

button {
    background-color: #333333;
    color: white;
    padding: 9px;
    border: 2px solid #333333; /*The validator shows a warning for the border color and background color being the same. But it is the way I want it to be styled so that the button looks good.*/
}

img {
    float: right;
    width: 12%;
    margin-right: 100px;
    max-height: 12%;
}

.backgroundimage {
    background-image: url("../images/wascenery.jpeg");
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 400px;
    text-align: right;
    margin-bottom: 10px;
}

#heading {
    font-size: 3rem;
    position: relative;
    top: 250px;
    color: white;
}

#content {
    font-size: 1.5rem;
    position: relative;
    top: 250px;
    color: white;
}

footer {
    background-color: #333333;
    color: white;
    font-size: 0.75rem;
    text-align: center;
    line-height: 1.5rem;
    position: relative;
    bottom: 0;
    width: 100%;
}

.whitespace {
    height: 30px;
}

.footer a {
    color: white;
}

.footer a:hover {
    color: #669966;
}

a:hover.linkcolor {
    color: #FFCC00;
}

    </style>
   </head>
    <body>
        <header>
            <a href="./home.html"><h1 class="heading"> <span class="green">travel</span><span class="yellow">hub</span><span class="brown">.com</span> </h1></a>
            
        <div class="search">
            <input type="search" placeholder="Search..."/> 
            <button type="submit"> Search </button>
        </div>
        
        </header>

        <div class="nav">
        <ul>
            <li> <a href="./home.html" id="home"> Home </a> </li>
            <li class="dropdown"> <a href="./statehistory.html"> State History </a> </li>
            <li> <a href="./stategeography.html"> State Geography </a> </li>
            <li> <a href="./places.html"> Places </a> </li>
            <li> <a href="./travelinfo.html"> Travel info </a> </li>
            <li> <a href="./contactus.html"> Contact us </a> </li>
        </ul>
        </div>

        <div class="backgroundimage">
            <div class="middle"> 
                <div id="heading" class="heading">Welcome to the State of Washington!</div>
                <div id="content">Looking somewhere to travel? You've come to the right place!</div>
            </div>
            
        </div>
        
        <table>
            
            <tr>
            <td colspan="2">
                <div class="mpheading"> Welcome visitors! </div>
            </td>
            </tr>
            
            <tr>
            <td class="home">
                <div class="mpcontent">
                    <p>If you’re looking for a vacation spot, then you’ve come to the right place. If you still haven’t visited Washington, USA you’re clearly missing on a lot. However, it’s not late yet. Travel to Washington during your next holiday with your loved ones; we bet you’ll have the time of your life. And better yet, our website will give you all the details so browse on.</p>
                    
                    <div class="heading"> Why Washington? </div>
                    <p>A scenic place with amazing landscape, Washington is the place to come if you want to connect with nature. It has a wide variety of trees with animals and birds and a lot of lakes to visit. It is home to the famous Space Needle at Seattle! There are amazing suburbs like Issaquah and Sammamish with a great lot of friendly people and a lot more. So, what are you waiting for? Plan your trip today!</p>
        
                </div>
            </td>
            
            <td class="home">
                <div class="list">
                         <p>Here are some places you may have heard of that are exclusive to Washington:</p>
                        <ul>
                            <li>Olympic National Park and the Hoh Rain Forest</li>
                            <li>Seattle Center</li>
                            <li>San Juan Islands</li>
                            <li>Mount Rainier National Park</li>
                            <li>Tacoma Museums</li>
                            <li>Seattle Downtown</li>
                            <li>Washington State Capitol Building</li>
                            <li>Port Angeles <a href="./places.html">More...</a></li>
                        </ul>
                </div>
            </td>
            </tr>
        </table>
        
        <div class="whitespace"></div>
        
        <footer class="footer"> 
            <a href="./home.html">Home</a> | <a href="./statehistory.html" class="linkcolor">State History</a> | <a href="./stategeography.html">State Geography</a> | <a href="./places.html" class="linkcolor">Places</a> | <a href="./travelinfo.html">Travel info</a>  | <a href="./contactus.html" class="linkcolor">Contact us</a>
            <br/>
            
            &copy;2017 travelhub.com by Ananya. All rights reserved.
        </footer>
        
    </body>
</html>
