<DOCTYPE html>
  <html lang="us">
  <head>
  

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
