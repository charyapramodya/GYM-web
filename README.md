# GYM-web
this is a web site for a web application
style.css
body {
    color: aliceblue;
 background-color: black;
 text-align: center;
 font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
 left: 0;
 right: 0;
}

section{
    margin: -10px;
}

h2{
    color: rgb(250, 5, 5);
}
h3{
    color: #000;
}

h1 {
    color: rgb(249, 245, 245);
    font-weight: bolder;
}



#header{
position:sticky;
top:0px;
}

a {
    text-decoration: none;
}

ul li{
    list-style: none;
    text-decoration: none;
}

/* div {
    border: 3px solid rgb(176, 255, 5);
} */

img .backgrounds , div .backgrounds{
    width: 100%;
    height: 400px;
}
.fit-width{
    width: fit-content;
}

.fit-height{
    height: fit-content;
}

.margin-top{
    margin-top: 50px;
}

.slideshow{
    display: none;
}

.sidediv{
    display: -webkit-box;
    display: -moz-box;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
}

/* .cardview{
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
} */

.cardview-w,.cardview{
    box-shadow: 0 4px 8px 0 rgba(221, 221, 221, 0.2), 0 6px 20px 0 rgba(210, 205, 205, 0.19);
}

.img-cards{
    width: 200px;
    height: 200px;
    padding: 10px;
    margin: 5px;
}

.info{
    margin : 50px 50px 0 0;
    padding: 40px 40px;
    justify-content: center;
    text-align: justify;
    width: fit-content;
    height: fit-content;
}

.logo-view{
    width: 30px;
    height: 30px;
    padding: 20px;
}

/*************************header****************************/
.headercontainer {
    background-color: black;
    height: fit-content;
    width: 100%;
    position: sticky;
}

.headercontainer .logo{
    max-height: 100px;
    max-width: 100px;
   border-radius: 30%;
}

.headercontainer  a {
 display: inline-block;
 padding: 10px 20px;
 margin: 0 20px;

 color:rgb(194, 3, 3);
 text-decoration: none;
 font-weight: bold;
 vertical-align: middle;
 background-color: aliceblue;
 border-radius: 30px;
}

.headercontainer  a:hover {
color: black;

}

#first{
    margin-left: 25%;
}

/***************************************footer*********************/


#footerall{
    width: 100%;
    height: fit-content;
    background-color: rgb(255, 255, 255);
    font-weight: bold;
    padding: 20px 10px;
    margin-top: 30px;
    bottom: 0;
}

footer h1{
    font-size: 20px;
    font-weight: bold;
    color: rgb(156, 31, 3);
}

.containerf table{
    width: 100%;
    color :rgb(0, 0, 0);
text-shadow:1px;
font-weight: bold;

}

.main{
    align-self: left;
    text-align: left;
    margin-left: 10%;
}
.col ul li {
    list-style: none;
    align-self: center;
    line-height: 30px;
}
.col ul li a{
    color: #000;
}

.col ul li a:hover{
    color: rgb(254, 5, 5);
}


.containerf th {
    font-size: 18px;
    font-weight: bolder;
    color: rgb(156, 31, 3);
    margin-bottom: 10px;
    margin-top: 10px;
    text-transform: uppercase;
    letter-spacing: 1px;

}

.containerf ul {
    align-content: center;
    align-items: center;
    padding-right: 30px;
}


/********************************************index************************/
section .backgrounds{
    position:relative;;
    z-index: -1;
    height: 500px;
    width: 100%;
    }

div.textsonpics{
     position: absolute;;
     z-index: 0;
     width: fit-content;
     height: fit-content;
     text-overflow: clip;
     margin-top: 10%;
     font-weight: bold;
    }

    .textsonpics>h1{
        font-size: 40px;
    }

    .textsonpics>p{
        font-size: 30px;
    }

.cl2>h1,.cl3>h1,.cl4>h1,.cl6>h1{
        color: #000;
    }

    .cl6>h1{
        background-color: rgba(255, 255, 255, 0.837);
    }
    
.cl1{
    margin-left: 10%;
}

.cl2{
    margin-left: 10%;
}

.cl3{
    margin-left: 70%;
}

.cl4{
    margin-left: 10%;
}

.cl5{
    margin-left: 10%;
}

.cl6{
    margin-left: 40%;
}


    
    #whywe {
        width: 80%;
        height: fit-content;
        margin: 30px 10%;
        padding: 20px 30px;
        background-color: rgba(252, 31, 31, 0.505);
        border-radius: 30px;
        border: 5px solid rgb(255, 255, 255);
    }
    
    #whywe h1 {
        font-size: 1.5em;
        font-weight: bold;
    }
    
    #whywe p{
        font-size: 1em;
        color: aliceblue;
        align-self: center;
    }
    
    .schedule{
        width: 50%;
        height: fit-content;
        margin: 30px 0 30px 25%;
        padding: 30px;
        background-color: rgba(146, 146, 146, 0.275);
        border-radius: 10px;
        align-items: center;
        justify-content: center;
    }

     .sch {
        color: aliceblue;
        width: 100%;
        height: fit-content;
        line-height: 3rem;
    }

    .sch td{
        border: 2px solid #ddd;
    }
    
    tr.red{
        background-color: red;
    }
     tr.black{
        background-color:black;
    }

    .btntyp{
        padding: 10px 20px;
        color: aliceblue;
        background-color: red;
        border-radius: 20px;
    }
    
/******************************about us page********************/

.container {
    background-image: url('./images/aboutus/home.PNG');
    background-repeat: no-repeat;
    background-size: cover;
}

.whowe, #para{
    padding: 5% ;
    width: 50%;
}
.team{
    padding: 100px;
    height: fit-content;
    width: 70%;
    margin : 0 9%;
}

.team-container {
    background-color: rgba(240, 248, 255, 0.471);
    width: 80%;
    height: 300px;
    overflow: hidden;
    margin: 50px 0;
    border-radius: 50px;
    border: 5px solid rgba(255, 255, 255, 0.6);
}

.team-container>.team-pic {
    border-radius: 50%;
    padding: 50px;
}



.branches{
    padding: 10px;
    margin: 20px 14% 100px 14%;
}
.branches-desc{
    margin: 20px 10px;
}






/*******************************services*********************/

.textwe{
    background-image: url('./images/aboutus/home.PNG');
text-align: center;
width: 100%;
background-repeat: no-repeat;
background-size: cover;


}
.services-section {
    width: fit-content;
    height: fit-content;
    background-color: rgba(255, 254, 254, 0.085);
    z-index: -1;
    padding: 20px 20px ;
    margin: 5% 5%;
}

.service-box1{
    width: 300px;
    height: 300px;
    margin: 30px ;
    padding: 20px 25px;
    background-color: rgba(203, 203, 203, 0.362);
    z-index: 0;
    transition: transform 1s;

}

.service-box2{
    padding: 10px;
    height: 270px;
    background-color: rgb(255, 255, 255);
    align-items: center;
    color:black
    /* z-index: 1; */
}

.service-box1:hover{
    transform: scale(1.2);
}

.packages {
    width: fit-content;
    height: fit-content;
    text-align:center;
    margin-left: 5%;
}

.packages-box {
    width: 100%;
    height: fit-content;
    align-content: center;
}

.packages-box-out{
    max-width: 100%;
    height : fit-content; 
    padding: 10px;

}

.packages-box-in{
    width: 350px;
    padding: 5px 10px;
    margin: 10px 100px 10px 5px ;
    border-radius: 50px;
    background-color: aliceblue;
    color: #000;
} 

.packages-box-in h3{
    margin-left: 20px;
}

.packages-box-in h2{
    color: red;
}

.packages-box-in:hover{
    transform: translateX(100px) scale(1.1);
}

.ppara ,.ppara>h3{
    margin-top: 5%;
    padding: 5px 20px;
} 

.workouts{
    width: fit-content; 
    height: fit-content; 
    padding: 10px;
    margin: 10px 8%;
}

.workout-box-1{
    width: 100%;
    height: 100%;
    margin-top:3%;
    margin-left: 5%;
}

.workout-box-2{
    width: 100%;
    height: fit-content;
    padding: 10px;
}

.workpic{
    width: 40%;
    height: 10%;
    border-radius: 50%;
    border: 5px solid aliceblue;
}


.workout-box-3{
    position: relative;
    overflow: hidden;
    margin: 0 10px;
    width: 100%;
    height: 100%;
}

.workout-box-3>.workout-type {
    padding: 30px 20px;
    margin : 5px;
    border-radius: 20px;
    background-color: aliceblue;
    color:rgb(254, 2, 2);
    width: 250px;
    height: 100px;
    display: block;
    object-fit: cover;
    object-position: center;
    font-weight:bold;
}

.workout-box-3>.workout-desc{
    padding: 5px;
    position: absolute;
    inset: 0;
    background-color: rgb(253, 5, 5);
    color:rgb(245, 245, 245);
    justify-content: center;
    display: flex;
    font-weight: bold;
}

.workout-box-3>.workout-desc,
.workout-box-3>.workout-type{
transition: 1s ease-in-out;
}

.workout-box-3>.workout-desc.fade{
    opacity: 0;
}

.workout-box-3:hover>.workout-desc.fade {
    opacity: 1;
}

.workout-box-3:hover>.workout-type.blur{
    filter: blur(50px);
}

.workout-box-3>.workout-desc.sideleft{
transform:translateX(-100%);
}

.workout-box-3:hover>.workout-desc.sideleft{
    transform:translateX(0);
}



/**************************testimonials page**************/

.comment-container {
    text-align: left;
    background-color: rgba(240, 248, 255, 0.471);
    width: 35%;
    padding: 10px;
    height: 500px;
    overflow: hidden;
    margin: 50px 50px;
    border-radius: 50px;
    border: 5px solid rgba(255, 255, 255, 0.6);
    /* display:none; */
}

.comments>h1 {
    margin: 300px 200px;
    padding: 30px;
    background-color: rgba(240, 248, 255, 0.718);
    border-radius: 30px;
}

/**************************Shop*********************/
.shop{
    width: 50%;
}

.ad-cont{
    background-color: white;
    margin: 2% 3%;
    transition: transform 1s;
}

.ad-cont:hover{
 transform: scale(1.1);
}

.symbol{
    width: 50px;
    height: 50px;
    margin: 5px 10px;
}

table{
    text-align: center;
}

.container{
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction:row;
    justify-content: center;
    align-items: center;
    padding: 5px;
}

.container>p{
margin-left: 20px; 
}








/***********************contact us page***********************/

#formhead {
    padding: 5px 5px;
    background-color: rgba(251, 29, 29, 0.679);
    border-radius: 50px;

}

.formmap{
    margin: 50px;
    /* padding: 50px 10px; */
}

.formsec{
    padding: 40px;
    align-content: center;
    width: 30%;
    
}

.form-rows{
    justify-content: left;
    align-items: left;
    margin:  20px 30px;
    padding-left: 20px;
    font-weight: bold;
    padding: 5px 5px;
    background-color: white;
    border-radius: 30px;
    color: black;
}

.form-group label {
    margin-left: 10px;
}

.form-group input {
    margin-left: 10px;
    border:none;
    outline-width: 0;
    width: 60%;
}

 #message{
    width: fit-content;
    height: 100px;
}

.sndbtn,.clrbtn{
    align-self: center;
    color: aliceblue;
    font-weight: bolder;
    border-radius: 30px;
    border-color: aliceblue;
    border-width: 2px;
    margin:20px 0% 0 10%;
    padding: 15px 30px;
    font-size:medium;
}

.sndbtn{
    background-color: rgba(251, 29, 29, 0.679);
}

.clrbtn{
    background-color: rgba(73, 73, 73, 0.679);
}

.sndbtn:hover,.clrbtn:hover{
    background-color: rgb(6, 6, 6);
}

.sndbtn:active,.clrbtn:active{
    background-color: rgb(236, 213, 213);
    color: rgb(226, 12, 12);
}



textarea {
    border: none;
    outline: none;
}

.mapouter{
    margin-left: 10%;
    text-align:right;
    width:600px;
    height:400px;
    }
    
.gmap_canvas{
    overflow:hidden;
    background:none!important;
    width:600px;
    height:400px;
    }
.gmap_iframe 
{
    width:600px!important;
    height:400px!important;
}

index page
<html>
    <head>
        <link rel="stylesheet" href="style.css" >   
        <script
        src="https://code.jquery.com/jquery-3.3.1.js"
        integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
        crossorigin="anonymous">
    </script>
    <script> 
    $(function(){
      $("#header").load("header.html"); 
      $("#footer").load("footer.html"); 
    });
    </script> 
    </head>
    <body>
        <section id="header"></section>
            
            <section class =" slideshow " >
                <div class = "textsonpics cl1">
                    <h1> Take the time for <br>
                    Best Fitness</h1>
                    
                </div>
                <img class ="backgrounds" src = "./images/home/home1.jpg"/>
            </section>

            <section class =" slideshow " >
                <div class = "textsonpics cl2">
                    <h1 > Know about us</h1>
                    <p><a class="btntyp" href="aboutUs.html"> About Us</a></p>
                </div>
                <img class ="backgrounds" src = "./images/home/home2.jpg"/>
            </section>


            <section class =" slideshow ">
                <div class = "textsonpics cl3">
                    <h1> Take our services <br> build yourself </h1>
                    <p><a class="btntyp" href="services.html"> Services </a></p>
                </div>
                <img class ="backgrounds" src = "./images/home/home4.jpg"/>
            </section>

            <section class =" slideshow ">
                <div class = "textsonpics cl4">
                    <h1> Get products  <br> build with us </h1>
                    <p><a class="btntyp" href="shop.html"> Select The Product</a> </p>
                </div>
                <img class ="backgrounds" src = "./images/home/home5.jpg"/>
            </section>

            <section class =" slideshow ">
                <div class = "textsonpics cl5">
                    <h1> See customer's opinions <br> about us </h1>
                   <p><a class="btntyp" href="testimonials.html">Testimonials</a> </p>
                </div>
                <img class ="backgrounds" src = "./images/home/home6.jpg"/>
            </section>

            <section class =" slideshow ">
                <div class = "textsonpics cl6">
                    <h1> We are looking for you </h1>
                    <p><a class="btntyp" href="contacttUs.html"> Contact Us</a></p>
                    </div>
                <img class ="backgrounds" src = "./images/home/home3.png"/>
            </section>

<br>

        <div id = "whywe">
            <h1>Why You Should Select Us?</h1>
            <p> Whether your goal is weight loss, strength, injury rehabilitation or to simply get a great workout, our coaches cater to the needs of men and women regardless of age and fitness levels. The Adult Performance Program for Adults focuses on maximizing fat loss and improving flexibility, core strength, total body strength and cardiovascular fitness. 
<br>
<br>
            Rathnayaka GYMS has helped men and women of all ages move better, feel better, reduce fat and increase energy through their programs.
             </p>
        </div>

        <div class="schedule">
            <h1>Our schedule</h1>
                <table class="sch">
                    <tr class="red">
                        <td>Monday</td>
                        <td>6:00AM - 10:00PM</td>
                    </tr>
                    <tr class="black">
                        <td>Tuesday</td>
                        <td>6:00AM - 10:00PM</td>
                    </tr>
                    <tr class="red">
                        <td>Wednesday</td>
                        <td>6:00AM - 10:00PM</td>
                    </tr>
                    <tr class="black">
                        <td>Thursday</td>
                        <td>6:00AM - 10:00PM</td>
                    </tr>
                    <tr class="red">
                        <td>Friday</td>
                        <td>6:00AM - 10:00PM</td>
                    </tr>
                    <tr class="black">
                        <td>Saturday</td>
                        <td>7:00AM - 5:00PM</td>
                    </tr>
                    <tr class="red">
                        <td>Sunday</td>
                        <td>7:00AM - 5:00PM</td>
                    </tr>
                </table>
        </div>
        <section id="footer"></section>
    </body>

    <script>
        var slideIndex = 0;
        showslides();
        
        function showslides() {
          var i;
          var x = document.getElementsByClassName("slideshow");
          for (i = 0; i < x.length; i++) {
            x[i].style.display = "none"; 
          }
          slideIndex++;
          if (slideIndex > x.length) 
          {slideIndex = 1} 

          x[slideIndex-1].style.display = "block"; 
          setTimeout(showslides, 5000); 
        }
        </script>

</html>

<----------------------------------------! header----------------------->
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css" type="text/css">
</head>
<header>
    <div class = "headercontainer">
            <a id = "logo" href="index.html">
                <img class="logo" src="./images/logo.png"/>
            </a>

            <a href="index.html" id ="first">Home</a>
            <a href="aboutUs.html">About Us</a>
            <a href="services.html">Our Services</a>
            <a href="shop.html">Product</a>
            <a href="testimonials.html">Testimonials</a>
            <a href="contactUs.html">Contact Us</a>
        </div>        
    </div>
</header>
</html>

<-----------------------------------! footer----------------->
<!DOCTYPE html>
<html lang="en" >
<head>
    <link rel="stylesheet" href="style.css" type="text/css">
</head>
    <footer id="footerall">
        <div class="containerf">
            <table >
                <thead>
                    <th  ></th>
                    <th  >Services</th>
                    <th  >Branches</th>
                </thead>
               
                    
                <tbody>
                    <tr class="row">
                        <td class="col"> 
                            <div class="sidediv main fit-width">
                                <img src="./images/logo.png" class=" img-cards">
                                <ul>
                                    <li>
                                        <span style='font-size:20px;'>&#128222;</span> +94123456789  </li>  
                                    <li>
                                        <span style='font-size:20px;'>&#128231;
                                        </span>
                                        rathnayakegymofficial@gmail.com
                                    </li>
                                    <br>
                                    <br>
                                    <li>
                                        <a href="#">
                                            <img class="logo-view" src="./images/sm-icons-facebook-logo.webp">
                                        </a>
                                        <a href="#">
                                            <img class="logo-view"  src="./images/insta.png">
                                        </a>
                                        <a href="#">
                                            <img class="logo-view"  src="./images/utube.png">
                                        </a>
                                        <a href="#">
                                            <img class="logo-view"  src="./images/twitter.png">
                                        </a>
                                    </li>
                                </ul>
                        </div>
                            
                            
                        </td>
                        <td class="col"> 
                            <ul>
                                <li><a href="services.html#pkgs">Packages</a></li>  
                                <li><a href="services.html#wrkouts">Workouts</a></li>
                                <li><a href="shop.html#equipsec">Equipments</a></li> 
                                <li><a href="shop.html#supsec">Suppliments</a></li> 
                               
                            </ul>
                        </td>
                        <td class="col">  
                            <ul>
                                <li>Kaduwela</li>  
                                <li>Kottawa</li>
                                <li>Malabe</li>
                                <li>Avissawella</li>
                            </ul>
                        </td>
                    </tr> 
                </tbody>                
            </table>
        </div>
    </footer>
</html>

<--------------------------------! about us page------------------>
<html>
    <head>
        <link rel="stylesheet" href="style.css" >    
        <script
        src="https://code.jquery.com/jquery-3.3.1.js"
        integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
        crossorigin="anonymous">
    </script>
    <script> 
    $(function(){
      $("#header").load("header.html"); 
      $("#footer").load("footer.html"); 
    });
    </script> 
    </head>
    <body>
        <section id="header"></section>
        <section>
            <div class="container sidediv" >
                <div id="para" class="margin-top">
                        
                    <h1>our vision</h1>
                    <p>To be the most effective Health & Fitness facilitator in the island</p>
                    <br>
                    <br>
                    <h1>Our mission</h1>
                    <p>To have island wide ultra-modern Gymnasiums and Fitness Centers to enhance public health & fitness for their quality lifestyles
                        </p>
                    <br><br>

                    <h1>Our Copporate Goal</h1>
                    <p>To be the most sought after Health & Fitness partner in our region.</p>
            </div>
                <div class="whowe">
                    <h1>Who we are?</h1>
                    <p>Rathnayaka GYMS is the core brand of Blue Mountain Wellness and Sports which is a fully-owned subsidiary of the Blue Mountain Group, the undisputed leader and trail-blazer in the real estate and property development industry in Sri Lanka. The Company is now diversifying its operations with the intention of creating an environment for fitness, health and well-being for all Sri Lankans.
                        <br>
                        <br>

                        Rathnayaka GYMS features an international standard, state-of-the-art gymnasium located in a quiet, spacious and picturesque environment at Pellawatte, Battaramulla offering exclusive privileges and luxury facilities specially catering to those with a penchant for fitness and well-being. The gymnasium features ultra-modern Olympic committee certified Technogym equipment including the revolutionary Wellness Key, introduced in Sri Lanka for the very first time. This high-tech device helps you keep a track of your daily workout while enabling you to obtain a detailed view of your results and performance real-time!
                        <br>
                        <br>

                        Our qualified and experienced personal trainers will provide you with personalized tips and advice to ensure that your workout is effective, safe and of course FUN!
                        <br>
                        <br>
                        Become a member today and be a part of Sri Lanka’s newest and trendiest fitness revolution!
    
                    </p>
                </div>
 
            </div>
            <section class="team margin-top ">
                <h1>Team</h1>
                <p>We have well experienced and trained team. They will guide you to achive your goal in accurate way</p>
    
    
                <div class="containerteam ">
                    <div class="team-container sidediv cardview">
                        <img class="team-pic img-cards" src="./images/aboutus/trainer1.webp"/>
                        <div class="info">
                           <b> Rakitha Fonseka </b> has been in the fitness industry since 2014. Isuru is ACE Certified & the first certified Animal Flow trainer in Sri Lanka. He specializes in a variety of training and believes in a holistic approach to fitness as each person is different and unique.
    
                        </div>
                    </div>
                    <div class="team-container sidediv cardview" style="margin-left: 19%;">
                        <img class="team-pic img-cards" src="./images/aboutus/trainer2.webp"/>
                        <div class="info">
                            <b>Dinuka Perera</b> was born in Sri Lanka and built in Japan. He is a fitness as well as a certified nutrition coach with many credentials: Certified Nutritionist NASM Fitness Nutrition Specialist, NESTA Fitness Nutrition Coach, NESTA Lifestyle and Weight Management Specialist, Certified Corporate Wellness Consultant, American Red Cross CPR/AED, Certified Member of The American College of Sports Medicine.
                        </div>
                    </div>
                    <div class="team-container sidediv cardview">
                        <img class="team-pic img-cards" src="./images/aboutus/trainer3.webp"/>
                        <div class="info">
                            <b>Chethiya Fonseka</b> is the owner of CW Nutrition & Fitness where he provides workout routines geared to your fitness level. He also provides consultation for healthy and easy recipes which will help you to loose fat, gain muscle and achieve overall well being.
    
                        </div>
                    </div>
                    <div class="team-container sidediv cardview" style="margin-left: 19%;">
                        <img class="team-pic img-cards" src="./images/aboutus/trainer4.webp"/>
                        <div class="info">
                            <b>Tanuja Perera</b> is a well known personal trainer, lifestyle and fitness consultant in Sri Lanka. She became a level 3 reps qualified personal trainer in 2010 in UK. She is a strength and conditioning coach specializing in TRX, kettlebells, boxing and Yoga. Her areas of expertise include weight management, postural correction, muscle building, injury rehabilitation and nutrition advice.
    
                        </div>
                    </div>
                    </div>
                </div>
            </section>
            <div class="team branches ">
                    <h1>Branches</h1>
                <div class="sidediv fit-width cardview">
                    <div class="branches-desc cardview" style="margin-left:20px ;">
                        <h2>Kottawa</h2>
                        <img class="img-cards" src="./images/aboutus/gyms1.jpg">
                    </div>
                    <div class="branches-desc cardview">
                        <h2>Kaduwela</h2>
                        <img class="img-cards" src="./images/aboutus/gyms2.jpg"">
                    </div>
                    <div class="branches-desc cardview">
                        <h2>Malabe</h2>
                        <img class="img-cards" src="./images/aboutus/gyms3.jpg"">
                    </div>
                    <div class="branches-desc cardview">
                        <h2>Avissawella</h2>
                        <img class="img-cards" src="./images/aboutus/gyms4.jpg"">
                    </div>
                </div>
            </div>
            </section>
        <section id="footer"></section>
    </body>
</html>

<------------------------------!services------------------>
<html>
    <head>
        <link rel="stylesheet" href="style.css" > 

        <script
        src="https://code.jquery.com/jquery-3.3.1.js"
        integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
        crossorigin="anonymous">
    </script>
    <script> 
    $(function(){
      $("#header").load("header.html"); 
      $("#footer").load("footer.html"); 
    });
    </script> 
    </head>
    <body>
        <section id="header"></section>
        <div class = "objectives sidediv">
          
            <div class="textwe">
                <h1>We are ready to..</h1>
                <p>
                    <ul>
                        <li>Provide Day to day Premium customer experience where every member matters.</li>
                        <br>
                        <li>Provide guarantied fitness results to every customer with every tailored solution</li>
                        <br>
                        <li>Continuous Improvement in Everything we do and strive towards providing leading service to our customers.</li>
                        <br>
                        <li>To practice what we preach and lead by example at all times</li>
                        <br>
                        <li>Create a community based environment where everyone feels cared for and confident in achieving their goals.</li>
                    </ul>
                </p>
            </div>
        </div>
        <section class = "services-section sidediv">
            <div class = "service-box1">
                <div class = "service-box2">
                    <h2> Packages </h2>
                    <div class = "service-icon">
                        <img style="max-width: 100px ; max-height: 100px;" src="./images/services/ser1.jpg"/>
                    </div>
                    <div class = "service-text">
                        <p>Diet plans especially designed for you considering several factors such as your convenience, affrodability and whether you are vegan or non vegan.</p>
                    </div>
    
                </div>
            </div>
            <div class = "service-box1">
                <div class = "service-box2">
                    <h2>Consulting</h2>
                    <div class = "service-icon">
                        <img style="max-width: 100px ; max-height: 100px;" src="./images/services/ser2.jpg"/>
                    </div>
                    <div class = "service-text">
                        <p>1:1 consulting sessions for you. Talk with the trainer about your goals and identify your plentius and discover various solutions and alternatives just for you.</p>
                    </div>
                    </div>
                </div>
            </div>
            <div class = "service-box1">
                <div class = "service-box2">
                    <h2>Workouts</h2>
                    <div class = "service-icon">
                        <img style="max-width: 100px ; max-height: 100px;" src="./images/services/ser3.jpg"/>
                    </div>
                    <div class = "service-text">
                        <p>Contact you individually and collect required data to deliver the best workout plan for you</p>
                    </div>

                    </div>
                </div>
            </div>
        </section>
        <div class = "packages" id="pkgs">
            <h1> Our Packages </h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                Quae, a voluptatem obcaecati dolores veniam quos, odio 
                vitae possimus reprehende
            </p>
            <div class = "packages-box">
                <div class = "packages-box-out sidediv">
                    <div class = "packages-box-in cardview">
                        <h2>Individual Male</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg1.jpg"/>
                            <div>
                                <p class="ppara">Are you the type of guys that feels insecure of their body whenever you go out partying or with girls? 
                                    <br>
                                    <h3> LKR 23800/=</h3>
                                </p>    
                                </div>
                        </div>
                    </div>
                    <div class = "packages-box-in cardview">
                        <h2>Individual Female</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg2.webp"/>
                            <div>
                            <p class="ppara">Ladies let’s get real here! 
                                You do don’t you?</p>  
                            <br>
                            <h3> LKR 19800/=</h3>
                            </div>
                    </div>
                    </div>
                    <div class = "packages-box-in cardview">
                        <h2>Student</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg3.jpg"/>
                            <div>
                            <p class="ppara">We all have to start somewhere! So why not start at a young age when you have the time and energy for it!</p> 
                            <br>
                            <h3> LKR 16000/=</h3>
                            </div>
                        </div>
                    </div>
                </div>
                <div class = "packages-box-out sidediv">
                    <div class = "packages-box-in cardview" style="margin-left: 20%;">
                        <h2>Familiy</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg4.jpg"/>
                            <div>
                            <p class="ppara">A good deal for you and your family to unite as one and work hard towards a common goal - 
                                <br>
                                TO GET IN SHAPE </p>
                            <br>
                            <h3> LKR 16000/=</h3>
                            </div>
                        </div>
                    </div>
                    <div class = "packages-box-in cardview">
                        <h2>Monthly</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg5.png"/>
                            <div>
                            <p class="ppara">Pay monthly and achieve your goals </p> 
                            <br>
                            <h3> LKR 6000/=</h3>
                            </div>
                        </div>
                    </div>
                </div>
           </div>
        </div>
        <div class = "workouts" id="wrkouts">
            <h1> Our workouts </h1>
            <p> We  consider about your life style and your busy schedule. Hence we think you need a personal trainer who can understand your busy lifestyle and help you to give best results. </p>

            <div class = "sidediv">
            <img class = "workpic" src = "./images/services/wrkout.jpeg"/>
            <div class ="workout-box-1">
                <div class = "workout-box-2 sidediv">
                    <div class = "workout-box-3">
                        <div class="workout-type cardview blur">FREE STYLE GROUP TRAINING</div>
                        <div class="workout-desc fade sideleft">Work together as a team while improving your movement ability.
                        </div>
                    </div>  
                    <div class = "workout-box-3">
                        <div class="workout-type cardview blur">CARDIO TRAINING</div>
                        <div class="workout-desc fade sideleft">It strengthens your heart and lungs, lowers blood pressure and cholesterol levels while helping you enjoy a fit and healthy life.
                        </div>
                    </div>  
                </div>  
                <br>
                <div class = "workout-box-2 sidediv">
                    <div class = "workout-box-3">
                        <div class="workout-type cardview blur">STRENGTH TRAINING
                        </div>
                        <div class="workout-desc fade sideleft">Strength Training helps shape your body while burning fat.
                        </div>
                    </div>  
                    <div class = "workout-box-3">
                        <div class="workout-type cardview blur">PERSONAL TRAINING
                        </div>
                        <div class="workout-desc fade sideleft">Our personal training programmes conducted by our professional personal trainers offer customized sessions especially tailor-made to suit your requirements.
                        </div>
                    </div> 
                </div> 
                <br>
                <div class = "workout-box-2 sidediv">
                        <div class = "workout-box-3">
                            <div class="workout-type cardview blur">HARD ABS
                            </div>
                            <div class="workout-desc fade sideleft">Almost everybody wants a six-pack – rock hard abs that will make you the talk of the town and the gym
                            </div>
                        </div>  
                        <div class = "workout-box-3">
                            <div class="workout-type cardview blur">FUNCTIONAL TRAINING
                            </div>
                            <div class="workout-desc fade sideleft">A typical Functional Training workout comprises functional movements performed at a relatively high intensity
                            </div>
                        </div>      
                    </div>
                    <br>
                    <div class = "workout-box-2 sidediv">
                        <div class = "workout-box-3">
                            <div class="workout-type cardview blur">GROUP EXERCISE CLASSES</div>
                            <div class="workout-desc fade sideleft">Nothing beats working as a team and our Group Exercise Classes will inspire you to discover new training techniques, styles and routines.
                            </div>
                        </div>  
                        <div class = "workout-box-3">
                            <div class="workout-type cardview blur">MUSSLE GAIN</div>
                            <div class="workout-desc fade sideleft">gain mussles in a smart way 
                            </div>
                        </div>  
                    </div> 
                </div>
            </div>
        </div>
        <section id="footer"></section>
    </body>
</html>

<!----------------------------services--------------------->
<html>
    <head>
        <link rel="stylesheet" href="style.css" > 

        <script
        src="https://code.jquery.com/jquery-3.3.1.js"
        integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
        crossorigin="anonymous">
    </script>
    <script> 
    $(function(){
      $("#header").load("header.html"); 
      $("#footer").load("footer.html"); 
    });
    </script> 
    </head>
    <body>
        <section id="header"></section>
        <div class = "objectives sidediv">
          
            <div class="textwe">
                <h1>We are ready to..</h1>
                <p>
                    <ul>
                        <li>Provide Day to day Premium customer experience where every member matters.</li>
                        <br>
                        <li>Provide guarantied fitness results to every customer with every tailored solution</li>
                        <br>
                        <li>Continuous Improvement in Everything we do and strive towards providing leading service to our customers.</li>
                        <br>
                        <li>To practice what we preach and lead by example at all times</li>
                        <br>
                        <li>Create a community based environment where everyone feels cared for and confident in achieving their goals.</li>
                    </ul>
                </p>
            </div>
        </div>
        <section class = "services-section sidediv">
            <div class = "service-box1">
                <div class = "service-box2">
                    <h2> Packages </h2>
                    <div class = "service-icon">
                        <img style="max-width: 100px ; max-height: 100px;" src="./images/services/ser1.jpg"/>
                    </div>
                    <div class = "service-text">
                        <p>Diet plans especially designed for you considering several factors such as your convenience, affrodability and whether you are vegan or non vegan.</p>
                    </div>
    
                </div>
            </div>
            <div class = "service-box1">
                <div class = "service-box2">
                    <h2>Consulting</h2>
                    <div class = "service-icon">
                        <img style="max-width: 100px ; max-height: 100px;" src="./images/services/ser2.jpg"/>
                    </div>
                    <div class = "service-text">
                        <p>1:1 consulting sessions for you. Talk with the trainer about your goals and identify your plentius and discover various solutions and alternatives just for you.</p>
                    </div>
                    </div>
                </div>
            </div>
            <div class = "service-box1">
                <div class = "service-box2">
                    <h2>Workouts</h2>
                    <div class = "service-icon">
                        <img style="max-width: 100px ; max-height: 100px;" src="./images/services/ser3.jpg"/>
                    </div>
                    <div class = "service-text">
                        <p>Contact you individually and collect required data to deliver the best workout plan for you</p>
                    </div>

                    </div>
                </div>
            </div>
        </section>
        <div class = "packages" id="pkgs">
            <h1> Our Packages </h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                Quae, a voluptatem obcaecati dolores veniam quos, odio 
                vitae possimus reprehende
            </p>
            <div class = "packages-box">
                <div class = "packages-box-out sidediv">
                    <div class = "packages-box-in cardview">
                        <h2>Individual Male</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg1.jpg"/>
                            <div>
                                <p class="ppara">Are you the type of guys that feels insecure of their body whenever you go out partying or with girls? 
                                    <br>
                                    <h3> LKR 23800/=</h3>
                                </p>    
                                </div>
                        </div>
                    </div>
                    <div class = "packages-box-in cardview">
                        <h2>Individual Female</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg2.webp"/>
                            <div>
                            <p class="ppara">Ladies let’s get real here! 
                                You do don’t you?</p>  
                            <br>
                            <h3> LKR 19800/=</h3>
                            </div>
                    </div>
                    </div>
                    <div class = "packages-box-in cardview">
                        <h2>Student</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg3.jpg"/>
                            <div>
                            <p class="ppara">We all have to start somewhere! So why not start at a young age when you have the time and energy for it!</p> 
                            <br>
                            <h3> LKR 16000/=</h3>
                            </div>
                        </div>
                    </div>
                </div>
                <div class = "packages-box-out sidediv">
                    <div class = "packages-box-in cardview" style="margin-left: 20%;">
                        <h2>Familiy</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg4.jpg"/>
                            <div>
                            <p class="ppara">A good deal for you and your family to unite as one and work hard towards a common goal - 
                                <br>
                                TO GET IN SHAPE </p>
                            <br>
                            <h3> LKR 16000/=</h3>
                            </div>
                        </div>
                    </div>
                    <div class = "packages-box-in cardview">
                        <h2>Monthly</h2>
                        <div class="sidediv">
                            <img style="max-width: 200px ; max-height: 200px;" src="./images/services/pkg5.png"/>
                            <div>
                            <p class="ppara">Pay monthly and achieve your goals </p> 
                            <br>
                            <h3> LKR 6000/=</h3>
                            </div>
                        </div>
                    </div>
                </div>
           </div>
        </div>
        <div class = "workouts" id="wrkouts">
            <h1> Our workouts </h1>
            <p> We  consider about your life style and your busy schedule. Hence we think you need a personal trainer who can understand your busy lifestyle and help you to give best results. </p>

            <div class = "sidediv">
            <img class = "workpic" src = "./images/services/wrkout.jpeg"/>
            <div class ="workout-box-1">
                <div class = "workout-box-2 sidediv">
                    <div class = "workout-box-3">
                        <div class="workout-type cardview blur">FREE STYLE GROUP TRAINING</div>
                        <div class="workout-desc fade sideleft">Work together as a team while improving your movement ability.
                        </div>
                    </div>  
                    <div class = "workout-box-3">
                        <div class="workout-type cardview blur">CARDIO TRAINING</div>
                        <div class="workout-desc fade sideleft">It strengthens your heart and lungs, lowers blood pressure and cholesterol levels while helping you enjoy a fit and healthy life.
                        </div>
                    </div>  
                </div>  
                <br>
                <div class = "workout-box-2 sidediv">
                    <div class = "workout-box-3">
                        <div class="workout-type cardview blur">STRENGTH TRAINING
                        </div>
                        <div class="workout-desc fade sideleft">Strength Training helps shape your body while burning fat.
                        </div>
                    </div>  
                    <div class = "workout-box-3">
                        <div class="workout-type cardview blur">PERSONAL TRAINING
                        </div>
                        <div class="workout-desc fade sideleft">Our personal training programmes conducted by our professional personal trainers offer customized sessions especially tailor-made to suit your requirements.
                        </div>
                    </div> 
                </div> 
                <br>
                <div class = "workout-box-2 sidediv">
                        <div class = "workout-box-3">
                            <div class="workout-type cardview blur">HARD ABS
                            </div>
                            <div class="workout-desc fade sideleft">Almost everybody wants a six-pack – rock hard abs that will make you the talk of the town and the gym
                            </div>
                        </div>  
                        <div class = "workout-box-3">
                            <div class="workout-type cardview blur">FUNCTIONAL TRAINING
                            </div>
                            <div class="workout-desc fade sideleft">A typical Functional Training workout comprises functional movements performed at a relatively high intensity
                            </div>
                        </div>      
                    </div>
                    <br>
                    <div class = "workout-box-2 sidediv">
                        <div class = "workout-box-3">
                            <div class="workout-type cardview blur">GROUP EXERCISE CLASSES</div>
                            <div class="workout-desc fade sideleft">Nothing beats working as a team and our Group Exercise Classes will inspire you to discover new training techniques, styles and routines.
                            </div>
                        </div>  
                        <div class = "workout-box-3">
                            <div class="workout-type cardview blur">MUSSLE GAIN</div>
                            <div class="workout-desc fade sideleft">gain mussles in a smart way 
                            </div>
                        </div>  
                    </div> 
                </div>
            </div>
        </div>
        <section id="footer"></section>
    </body>
</html>


<!--------------------------------testimonials-------------->
<html>
    <head>
        <link rel="stylesheet" href="style.css" >     
        <script
        src="https://code.jquery.com/jquery-3.3.1.js"
        integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
        crossorigin="anonymous">
    </script>
    <script> 
    $(function(){
      $("#header").load("header.html"); 
      $("#footer").load("footer.html"); 
    });
    </script> 
    </head>
    <body>
        <section id="header"></section>        
        
        <section>
            <div class="backgrounds">
                <div class="textsonpics">
                    <h1> Your opinions value us a lot</h1>
                </div>
                <img class="" src="./images/we.jpeg"/>
            </div>  
        </section>

        <div class="comments sidediv margin-top" >
            <h1 class="cardview">Your Comments </h1>
            <div class="comment-container sidediv slideshow" >
                <div style="margin-left: 20px;">
                    <img class="cardview img-cards  " src="./images/test/comme1.jpg"/>
                    <div class="info">
                        I was gaining weight daily and my joints were starting to hurt because all the weight I was carrying. I knew 245 pounds was going to lead to 300 pounds and so forth. I was tired of hurting and being disgusted with how I looked and not able to fit in any clothes. I knew what I needed to help my weight loss goals and Houston Weight Loss Center has definitely given me the extra motivation I needed. A lot has changed now for the better – me and my kids eat better together.
                        <br>

I feel so amazing today it’s an unbelievable feeling. Definitely walk with confidence now!
                    </div>    
                </div>
            </div>
            <div class="comment-container sidediv slideshow">
                <div style="margin-left: 20px;">
                    <img class="cardview img-cards  " src="./images/test/comme2.png"/>
                    <div class="info">
                        I have lost a total of 27 lbs. I saw rapid results with this program. My experience has been great and been a blessing. It was hard for me to lose weight util now. The staff at this center are wonderful, helpful, and thoughtful during this delicate time. My eating habits have changed, I have increased my exercise habits, and feel more confident in myself.
                    </div>    
                </div>
            </div>
            <div class="comment-container sidediv slideshow">
                <div style="margin-left: 20px;">
                    <img class="cardview img-cards  " src="./images/test/comme3.jpg"/>
                    <div class="info">
                        I started this program 3 months ago. When I first started my journey, I wasn’t feeling good in my own body. I used to not like myself and wasn’t comfortable being around family and friends. Everyone would ask what happened to me because I used to be skinny. I started eating healthy and following the Houston Weight Loss Center program. I have lost 41 lbs in 3 months. Try this program and believe in yourself. You can do it.
                    </div>    
                </div>
            </div>
        </div>

        <section class="gallery">
            <img class="gallery" src="./images/test/gall1.jpeg">
            <img class="gallery" src="./images/test/gall4.jpg">
            <img class="gallery" src="./images/test/gall5.jpg">
            <img class="gallery" src="./images/test/gall6.jpg">
            <img class="gallery" src="./images/test/gall7.jpg">
            <img class="gallery" src="./images/test/gall8.jpg">
            <img class="gallery" src="./images/test/gall9.webp">
            <img class="gallery" src="./images/test/gall10.jpg">
        </section>
        <section id="footer"></section>


        <script>
            var slideIndex = 0;
            showslides();
            
            function showslides() {
              var i;
              var x = document.getElementsByClassName("slideshow");
              for (i = 0; i < x.length; i++) {
                x[i].style.display = "none"; 
              }
              slideIndex++;
              if (slideIndex > x.length) 
              {slideIndex = 1} 

              x[slideIndex-1].style.display = "block"; 
              setTimeout(showslides, 2000); 
            }
            </script>
    </body>
</html>

<!-----------------------shop------------------------------------------->
<html>
    <head>
        <link rel="stylesheet" href="style.css" >    
    <script
        src="https://code.jquery.com/jquery-3.3.1.js"
        integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
        crossorigin="anonymous">
    </script>
    <script> 
    $(function(){
      $("#header").load("header.html"); 
      $("#footer").load("footer.html"); 
    });
    </script> 
    </head>
    <body>
        <section id="header"></section>
        <div class="sidediv ">
            
                <div class="shop">
                    <a href="#eqip">
                        <h1 class="textsonpics"> Equipments</h1>
                    </a>
                    <img  class="backgrounds" src="./images/shop/equips.jpeg">
                </div>
                <div class="shop">
                    <a href="#supp">
                        <h1 class="textsonpics"> Suppliments</h1>
                    </a>
                    <img  class="backgrounds" src="./images/shop/supps.jpeg">
                </div>

        </div>
        <section class="equipments margin-top" >
            <h1 id="eqip"> Equipments</h1>
            <div id="equipsec" class="sidediv">
                <div class="ad-cont cardview fit-height fit-width">
                    <h2> treadmill</h2>
                    <img class="img-cards" src="./images/shop/eqip/1tredmill.jpg"/>
                    <br>
                    <h3>LKR 219,000.00</h3>
                </div>
                <div class="ad-cont cardview fit-height fit-width">
                    <h2> Cross trainer</h2>
                    <img class="img-cards" src="./images/shop/eqip/2cross.jpg"/>
                    <br>
                    <h3>LKR 159,000.00</h3>
                </div>
                <div class="ad-cont cardview fit-height fit-width">
                    <h2> Exercise bike</h2>
                    <img class="img-cards" src="./images/shop/eqip/3bike.jpg"/>
                    <br>
                    <h3>LKR 50,000.00</h3>
                </div>
                <div class="ad-cont cardview fit-height fit-width">
                    <h2> Smith machine</h2>
                    <img class="img-cards" src="./images/shop/eqip/4smith.jpg"/>
                    <br>
                    <h3>LKR 279,000.00 </h3>
                </div>
            
                </div>
        </section>

        <section class="suppliments margin-top" >
            <h1 id="supp"> Suppliments</h1>
            <div id="supsec" class="sidediv">
                <div  class="ad-cont cardview fit-height fit-width">
                    <h2> Gold standard whey </h2>
                    <img class="img-cards" src="./images/shop/supp/1gold.jpg"/>
                    <br>
                    <h3>LKR 25,000.00</h3>
                </div>
                <div class="ad-cont cardview fit-height fit-width">
                    <h2> Muscle Meds-Carnivor</h2>
                    <img class="img-cards" src="./images/shop/supp/2meds.jpg"/>
                    <br>
                    <h3>LKR 22,000.00</h3>
                </div>
                <div class="ad-cont cardview fit-height fit-width">
                    <h2> Muscle Tech -Nitro Tech</h2>
                    <img class="img-cards" src="./images/shop/supp/3tech.jpg"/>
                    <br>
                    <h3>LKR 23,000.00</h3>
                </div>
                <div class="ad-cont cardview fit-height fit-width">
                    <h2> Iso fusion </h2>
                    <img class="img-cards" src="./images/shop/supp/4iso.jpg"/>
                    <br>
                    <h3>LKR 19,000.00</h3>
                </div>
            
            </div>
        </section>
        <section id="footer"></section>
    </body>
</html>

<!---------------------------------contact us--------------------->
<html>
    <head>
        <link rel="stylesheet" href="style.css" >     
        <script
        src="https://code.jquery.com/jquery-3.3.1.js"
        integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
        crossorigin="anonymous">
    </script>
    <script> 
    $(function(){
      $("#header").load("header.html"); 
      $("#footer").load("footer.html"); 
    });
    </script> 
    </head>
    <body>
        <section id="header"></section>
                <h1>We always with you. Contact us...</h1>
        <section >
            <table border="0" width = 100% >
                <tbody>
                    <tr>
                        <td >
                            <div class="containter sidediv" style="margin-left:30px;" >
                                <span style='font-size:30px;'>&#128222;</span> +94123456789 
                            </div>
                            <div class="containter sidediv" style="margin-left:30px;">
                                <span style='font-size:30px;'>&#128231;
                                </span>
                                 rathnayakegymofficial@gmail.com
                            </div>
                            </td>
                            <td>
                                <div class="containter">
                                <h2>Follow us on</h2>
                                <a href="#">
                                    <img class="logo-view" src="./images/sm-icons-facebook-logo.webp">
                                </a>
                                <a href="#">
                                    <img class="logo-view"  src="./images/insta.png">
                                </a>
                                <a href="#">
                                    <img class="logo-view"  src="./images/utube.png">
                                </a>
                                <a href="#">
                                    <img class="logo-view"  src="./images/twitter.png">
                                </a>               
                            </div>
                </td>
                <td>
                    <div class="container sidediv">
                        <img class="logo-view" src="./images/location.png"/>
                        <h2>Locations</h2>
                    </div>
                    <div class="container sidediv">
                        <p><span style='font-size:30px;'>&#128204;</span> Kaduwela </p>
                        <p><span style='font-size:30px;'>&#128204;</span> Kottawa</p>
                        <p><span style='font-size:30px;'>&#128204;</span> Malabe</p>
                        <p><span style='font-size:30px;'>&#128204;</span> Avissawella</p>
                    </div>
                </td>

            </table> 
        </section>
        <section class="formmap sidediv">
            <div class="formsec fit-height cardview-W">
                <h1 id="formhead"> Have something to ask?</h1>
                <form action="Contactform.php" id="contForm" name="contForm" method="post" onsubmit="form()">
                    <div class="form-group">
                        <div class="form-rows">
                            <label name="cusName" id="cusName"> Name : </label>
                            <input type="text" class="form-control" id="cusName" name="cusName" placeholder="Your Name"required/>
                        </div>
                        <div class="form-rows">
                            <label name="email" id="email"> E-mail :</label>
                            <input type="email" class="form-control" id="email" name="email" placeholder="example@mail.com"required/>
                        </div>
                        <div class="form-rows">
                            <label name="teleNo" id="teleNo">Contact No : </label>
                            <input type="tel" class="form-control" id="teleNo" name="teleNo" pattern="[0-9]{10}" placeholder="0712345678" required/>
                        </div>
                        
                        <div class="form-rows">
                            <label  name="message" id="message"> Message :</label>
                            
                            <textarea rows="4" cols="40" class="form-control" id="cmessage" name="cmessage" placeholder="Message" required/></textarea>
                        </div>
                        <div class="sidediv " >
                            <button style="margin-left: 30%;" class="sndbtn" type="submit" >Send</button>
                            <button class="clrbtn" type="reset" >Clear</button>
                         </div>
                    </div>
                </form>
            </div>

           

 <div class="mapouter">
    <div class="gmap_canvas">
        <iframe class="gmap_iframe" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=600&amp;height=400&amp;hl=en&amp;q=kaduwela&amp;t=h&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"></iframe>
        <a href="https://formatjson.org/">format json</a>
    </div>
</div>

        </section>

        <section id="footer"></section>

    </body>
</html>

<!--------------------------contact form---------------------->
<Doctype html>
<html lang="en">
<?php
/*

$servername = "localhost";
$username = "root";
$password = "";


//========== Create connection========================
$conn = new mysqli($servername, $username, $password);
// Check connection
if ($conn->connect_error) {
  die("Connection failed: " . $conn->connect_error);
}

//=================== Create database==================
$sql = "CREATE DATABASE customerContacts";
if ($conn->query($sql) === FALSE) {
    echo "Error creating database: " . $conn->error;
} 
*/

// after creation of database customerContacts create the connection to the database
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "customerContacts";
$conn = new mysqli($servername, $username, $password, $dbname);
// =============Check connection======
if ($conn->connect_error) {
die("Connection failed: " . $conn->connect_error);
}

/*
//=================== Create table =====================
$sql = "CREATE TABLE IF NOT EXISTS ContForm (
id  INT(3) NOT NULL PRIMARY KEY AUTO_INCREMENT,
cusName  VARCHAR(20) NOT NULL ,
cusemail VARCHAR(100) NOT NULL,
cusPhone VARCHAR(12) NOT NULL ,
cusMessage VARCHAR(500) NOT NULL 
)";

if ($conn -> query($sql)===FALSE){
echo "Error creating table : ". $conn-> error;
}else{
echo " ContForm TABLE CREATED successfully";
}
*/

//===================insert data into the table ======

mysqli_select_db($conn,"customerContacts");
$sql="INSERT INTO ContForm (cusName,cusemail,cusPhone,cusMessage)
VALUES('$_POST[cusName]','$_POST[email]','$_POST[teleNo]','$_POST[cmessage]')";

if(!mysqli_query($conn,$sql))
{
   die("error".mysqli_error($conn));
 }

else
{
	 echo "<div style='margin:20% 30%;'><h4>New record Created successfully! </h4></div>";
   header('Refresh:2; URL=contactUs.html');

  //  $reslt = true;

  }

$conn ->close();

?>
</html>

*******************************images********************************8888
[images.zip](https://github.com/charyapramodya/GYM-web/files/10575151/images.zip)
