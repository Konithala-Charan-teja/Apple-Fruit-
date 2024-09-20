<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Apple Booking Store</title>
<style>
*{
    margin:0px;
    padding:0px;
}
.contianer{
    display:flex;
    flex-direction: row;
    justify-content: center;
}
/* header section */
.header{
    display:block;
    height:70px;
    position:relative;
    top:0px;
    width:auto;
    position: fixed;
    width:100%;
    z-index: 99;
    background-color: white;
}
.logo{
    position: relative;
    left:10%;
}
.logo,p{
    display:inline;
    margin-left:10px ;
    position: relative;
    bottom:6px;
}
.logo p{
    font-family: cursive;
    font-size: larger;
    text-shadow: 2px 2px 10px;
}
.logo img{
    box-shadow: 2px 2px 2px black;
    margin-top: 20px;
}
.header-service{
    position: relative;
    bottom:30px; 
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin-left: 50%;
    margin-right: 10%;
}
.header-service a{
    text-decoration: none;
    color:black;
    font-weight: bold;
    font-size: larger;
     }
.nav-link{
    transition: all 0.19s;
}
/*header  effects */
.header-service a:hover{
    color:red;
    text-decoration:underline;
    animation: text 1s linear 1;
}
.logo:hover{
    cursor: pointer;
}
@keyframes text{
    100%{
        text-decoration: underline;
        transition:ease-in;
    }
}
/*Main Section*/
.main{
    display: flex;
    background-color: rgb(230,220,230);
    height:700px;
    margin-left: 10px;
}
.main img{
    filter:drop-shadow(5px 8px 8px);
    object-fit: cover;
    margin-left:200px ;
    margin-top:200px;
    margin-right:50px ;
    width:350px;
    animation:apple 2s ease  1;
}
/* animation img */
@keyframes apple{
    0%{
        transform:scale(0.1) ;
    }
    100%{
        transform:scale(1) ;
    }
}
.main-description{
    margin-top: 150px;
    box-shadow: 3px 3px 10px;
    height:300px;
    margin-left: 60px;
    background-color:rgb(220,200,215) ;
    width:600px;
}
.card-1{
    transition:all 0.2s;
}
.main-description:hover{
    transform: scale(1.1);
}
.main-description h1{
    font-size:60px;
    padding:5px;
}
.main-description p{
    font-size: 30px;
    color:rgb(80,80,80);
    position: relative;
    top:30px;
    padding:5px;
    left:20px;
    }
  .main-description button{
    width:100px;
    height:50px;
    position: relative;
    top:80px;
    left:40px;
    background-color: rgb(226, 44, 44);
    color:white;
    font-size: larger;
    border:1px solid rgb(226, 44, 44);
    border-radius: 5px;
    box-shadow: 3px 6px 10px black;
}
/*main  effects */
.main-description button:hover{
    background-color:rgb(234, 80, 80) ;
    color:white;
    cursor: pointer;
}
/* About section */
.container2{
    background-color: rgb(220,200,215);
    margin-left: 10px;
    display: flex;
    flex-direction: column;
}
.container2 h2{
    text-align: center;  
    padding-top:75px;
    padding-bottom: 30px;
    font-size: 35px;
}
#para{
    font-size: larger;
    font-family:cursive;
    margin:30px 70px;
}
.container2 img{
    width:80%;
    height:550px;
    margin-left: 150px;
    margin-bottom: 50px;
    animation: img 1s ease 0.3s;
}
@keyframes img{
    0%{
        transform: translatex(-700px);
    }
}
/*Varities section*/
#varities{
    height:auto;
    background-color: rgb(230,220,230);
    margin-left: 10px;
}
.container3 h2{
    text-align: center;  
    padding-top:80px;
    padding-bottom: 30px;
    font-size: 35px;
}
.varity-items{
    display: grid;
    grid-template-columns: 2.5fr 2.5fr 2.5fr ;
    grid-template-rows: 1fr 1fr;
    width:1000px;
    height:auto;
    justify-content: space-around;
    margin-left:250px;
}
.varity-item{
    background-color: rgba(150,150,150,0.4);
    margin:40px 30px;
    height:450px;
    border-radius: 10px;
}
.varity-item h3{
    margin-left:18px ;
    padding:10px;
    font-size:30px;
    color:rgba(240,30,40,0.9);
}
.para2{
    margin-left:20px ;
    margin-right: 20px;
    font-family: Arial, Helvetica, sans-serif;
    margin-top: 20px;
}
.varity-item img{
    width:250px;
    height:200px;
    margin-top: 20px;
    margin-left: 20px;
    margin-right: 20px;
    box-shadow: 2px 2px 10px;
    border-top-left-radius: 10px;
    border-bottom-right-radius: 10px;
}
.card{
    transition: all 0.35s;
    box-shadow: 2px 2px;
}
.card:hover {
    transform:scale(1.07) ;
    box-shadow: 4px 5px 20px;
}
/* OurService Section */
#service{
    background-color:rgb(220,200,215);
    margin-left:10px;
    height:850px;
}
.container4{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.container4 >h2{
    margin-top:100px;
    font-size: 35px;
}
.fress{
    display: flex;
}
#fress{
    display: flex;
    flex-direction: column;
    margin-top: 70px;
    margin-left: 40px;
}
#fress>h2{
    font-size: 30px;
    margin-bottom: 30px;
}
#fress>p{
    font-size: 20px;
    font-family: cursive;
}
.fast{
    display: flex;
}
.fast img{
    margin-top: 30px;
}
#fast{
    display: flex;
    flex-direction: column;
    margin-top: 70px;
    margin-left: 40px;
}
#fast>h2{
    font-size: 30px;
    margin-bottom: 30px;
}
#fast>p{
    font-size: 20px;
    font-family: cursive;
    width:575px;
}
.satisfy{
    display: flex;
}
.satisfy img{
    margin-right: -50px;
}
#satisfy{
    display: flex;
    flex-direction: column;
    margin-top: 70px;
    margin-left: 40px;
}
#satisfy>h2{
    font-size: 30px;
    margin-bottom: 30px;
}
#satisfy>p{
    font-size: 20px;
    font-family: cursive;
    width:575px;
}
/* Contact section */
#contact{
    height:800px;
    background-color: rgb(230,220,230);
    margin-left: 10px;
}
.container5{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.container5>h1{
    margin-top: 60px;
    margin-bottom: 40px;
}
.container5>h2{
    margin-bottom: 40px;
    font-size: 30px;
    color:rgb(255,0,0);
}
form{
    width:400px;
    display: flex;
    flex-direction: column;
}
form fieldset{
    height: 300px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
    border-radius: 10px;
    border:3px solid;
    background-color: rgba(241, 223, 250, 0.9);
    box-shadow: 4px 5px 30px;
}
legend{
    margin-left: 10px;
    font-size: larger;
    font-weight: bolder;
}
form fieldset label{
    margin-top: 30px;
    position: relative;
    top:10px;
    left:-90px;
    z-index: 1;
    background-color: white;
}
form input{
    display: flex;
    flex-direction: column;
    width:300px;
    padding:15px;
    position:relative;
    border-top: none;
    border-radius: 10px;
    box-shadow: 2px 2px 9px ;
}
button{
    width:100px;
    height:40px;
    margin-top: 20px;
    font-size: 15px;
    font-weight: bold;
    border-radius: 10px;
}
button:hover{
    background-color:rgba(160, 42, 220, 0.5) ;
    color:white;
    border:2px solid rgba(160, 42, 220, 0.5) ;
    box-shadow: 2px 3px 9px black;
    cursor: pointer;
}
</style>
</head>
<body>
        <div class="container">
            <div class="header">
                <div class="logo">
                    <img src="https://freepngimg.com/thumb/apple/16-red-apple-png-image-thumb.png" alt="Logo" width="30px" height="30px"><p>Healthy Apples</p>
                </div>
                <div class="header-service">
                <a href="#about" class="nav-link">About</a>
                <a href="#varities" class="nav-link">Varieties</a>
                <a href="#service" class="nav-link">Our Service</a>
                <a href="#contact" class="nav-link">Contact</a>
                </div>
            </div>
            <div class="main">
                <div class="main-img">
                    <img src="https://www.pngmart.com/files/15/Apple-Slice-PNG-Background-Image.png" alt="Apple">
                </div>
                <div class="main-description card-1">
                    <h1>Fresh , Tasty , Healthy.</h1>
                    <p>100% Organic, Wide varities of apples are grown in Kashmir aka The Heaven of Earth.</p>
                    <button onclick="">Buy Now</button>
               </div>
            </div>
        </div>
        <div  id="about">
            <div class="container2">
                <h2>ABOUT US</h2>
                <P id="para">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We are a group of people with decades of experience in growing and selling apples. We know what a good apple looks like and how they are grown. This essential fruit requires a temperate climate, loamy soil that is rich in organic matter apart from needing proper drainage and aeration facilities. Lucky for us we live in Kashmir which is proudly known as paradise of earth is also home to temperate fruits like apple for which the state is very famous across globe. The main factor which influence temperate fruit bearing trees is soil, climate and environment which are highly favorable and unparalleled in the province of Kashmir. Kashmiri apples a unique look, taste, flavor, size and color.</P>
                <img src="https://i.ytimg.com/vi/syDRoJ1PdYI/maxresdefault.jpg" alt="Apple Harvesting">
            </div>
        </div>
        <div id="varities">
            <div class="container3">
                <h2>VARITIES</h2>
                <div class="varity-items">
                        <div class="varity-item card">
                        <img src="https://th.bing.com/th/id/R.a353380910db7ff72bfba2eb683cf9eb?rik=Sp8qU1riToutug&riu=http%3a%2f%2fclipart-library.com%2fimages_k%2fapples-transparent-background%2fapples-transparent-background-25.png&ehk=n55Pf2soAhv6mXMjCFJ7PcjD0jtg8DJMk5wO%2fYZUYLc%3d&risl=&pid=ImgRaw&r=0" alt="apple">
                        <h3>Amber</h3>
                        <div class="para2"><p>This red, medium-sized fruit becomes fully ripe in mid-October. It is mostly grown in Shopian and Kulgam.</p></div>
                        </div>
                                            <div class="varity-item card">
                        <img src="https://pngimg.com/uploads/apple/apple_PNG12444.png" alt="apple">
                        <h3>American Trel</h3>
                        <div class="para2"><p>A small, rounded, very crispy and sweet fruit variety that ripens in mid-September.</p></div>
                        </div>
                                           <div class="varity-item card">
                        <img src="https://pngimg.com/uploads/apple/apple_PNG12423.png" alt="apple">
                        <h3>Red Delicious</h3>
                        <div class="para2"><p>A very popular and widely cultivated variety of apple that ripens in mid-September. Its flesh is greenish white, grainy and juicy.</p></div>
                        </div>
                        <div class="varity-item card">
                        <img src="https://th.bing.com/th/id/R.28a64b14c5df10dfc2d8c7fc74ff7590?rik=3ineucyeK96Mog&riu=http%3a%2f%2fwww.pngmart.com%2ffiles%2f5%2fGreen-Apple-PNG-Free-Download.png&ehk=%2fhoba1UNkLsH5TbIrRd%2fjD4wfCPCIHApNyveIJIBK1I%3d&risl=1&pid=ImgRaw&r=0" alt="apple">
                        <h3>Maharaej</h3>
                        <div class="para2"><p>A large apple with red and green color. It tastes a bit sour but sweetens with time and is available by late October.</p></div>
                        </div>
                        <div class="varity-item card">
                        <img src="https://th.bing.com/th/id/R.c847e405a684511997d789d1f26c6d36?rik=5tHi5y%2bcEwRcpw&riu=http%3a%2f%2fpngimg.com%2fuploads%2fapple%2fapple_PNG12431.png&ehk=CjOJE0K0mmBTOyzTW71yr8A1ay%2f%2bhle7ZrA3tiUnEKk%3d&risl=&pid=ImgRaw&r=0" alt="apple">
                        <h3>Hazratbael</h3>
                        <div class="para2"><p>A quickly perishable variety that ripens in early July. It is the oldest variety of apples cultivated in the valley and is mostly consumed domestically</p></div>
                        </div>
                       <div class="varity-item card">
                            <img src="https://clipart.info/images/ccovers/15036889476-png-apple-image-clipart-transparent-png-apple.png" alt="apple">
                            <h3>Golden Delicious</h3>
                            <div class="para2"><p>A variety with comparatively longer shelf life, it is crispy, juicy and has thick greenish-white flesh which turns golden upon ripening. It is available till January.</p></div>
                            </div>
                </div>
            </div>
       </div>
       <div id="service">
            <div class="container4">
                <h2>OUR SERVICE</h2>
                <div class="fress">
                    <img src="https://iconsofindianbusiness.com/files/fress_logo-2021-11-10-14:07:47.png" alt="" width="140px">
                    <div id="fress">
                        <h2>Fresh</h2>
                        <p>We deliver fresh apples with a 100% guarantee of freshness.</p>
                    </div>
                </div>
               <div class="fast">
                    <img src="https://www.freeiconspng.com/uploads/faster-icon-png-1.png" alt="" width="140px">
                    <div id="fast">
                        <h2>Fast</h2>
                        <p>We deliver your orders as fast as possible, delivery procedure begins as soon as apple is plucked from tree.</p>
                    </div>
                </div>
               <div class="satisfy">
                    <img src="https://www.graphicspic.com/wp-content/uploads/2020/03/GPGV222-Happiness.png" alt="" width="200px">
                    <div id="satisfy">
                        <h2>Satisfying</h2>
                        <p>We guarantee 100% customer satisfaction. We do our best to make your purchase experience smooth. But if we mess up somehow you will get compensated for every inconvenience.</p>
                    </div>
                </div>
           </div>
          </div>
        <div id="contact">
            <div class="container5">
                <h1>CONTACT</h1>
                <h2>To make an order or just to know more contact us :</h2>
                <div class="orders">
                    <form action="" autocomplete="off">
                        <fieldset>
                            <legend>&nbsp; Know More &nbsp;</legend>
                            <label for="uname">Enter Your Name : </label><input type="text" maxlength="30" id="uname" required autocomplete="off">
                            <label for="email">Enter Your Email : </label><input type="email" id="email" required autocomplete="off">
                            <button type="submit" name="know more">Submit</button>
                        </fieldset>
                    </form>
                </div>
            </div>
        </div>
    </body>
</html>
