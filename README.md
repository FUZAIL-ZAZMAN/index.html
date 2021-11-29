# index.html
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INNOVATION 4 FUN</title>
    <link rel="stylesheet" href="index.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fruktur&family=Mochiy+Pop+One&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">   
</head>
<body>
    <section class="header">
      <nav>
        <a href="index.html"><img src="EDIT_MINI_LOGO-removebg-preview.png"></a>
        <div class="nav-links" id="navLinks">
           <i class="fa fa-times" onclick="hidemenu()"></i>
          <ul>
         <li><a href="index.html">HOME</a></li>  
         <li><a href="">PRODUCT</a></li>  
         <li><a href="ABOUT US.html">ABOUT US</a></li>  
         <li><a href="">CONTACT US</a></li>  
          </ul>
        </div>
           <i class="fa fa-bars" onclick="showmenu()"></i>
       </nav>
        
<div class="text-box">
        <h1>WELCOME  TO  OUR  WEBSITE</h1>
        <p>THIS IS MY FIRST WEBSITE WITH HTML AND CSS,<br>THEREFORE MAY BE IT LOOKS INCOMPLETE OR NOT PROFESSIONAL</p>
        <a href="" class="hero-btn"> VISIT OUR WEBSITE TO KNOW MORE</a>
</div>
     
</section>
    
                                    <!----------------projects----------------> 
<section class="projects">
        <h1>MICROCONTROLLERS</h1>
        <p1>THESE ARE SOME POPULAR MICROCONTROLLERS</p1>
        <div class="row">
        <div class="projects-col">
        <h3>ARDUINO</h3>
        <P>The Arduino Nano is a small, complete, and breadboard-friendly board based on the ATmega328 (Arduino Nano 3. ... It has more or less the same functionality of the Arduino Duemilanove, but in a different package. It lacks only a DC power jack, and works with a Mini-B USB cable instead of a standard one.</P>
        </div>
        <div class="projects-col">
        <h3>RESBERRY PI</h3>
        <P>The Raspberry Pi is a low cost, credit-card sized computer that plugs into a computer monitor or TV, and uses a standard keyboard and mouse. It is a capable little device that enables people of all ages to explore computing, and to learn how to program in languages like Scratch and Python.</P>
        </div> 
        <div class="projects-col">
        <h3>NODE MCU</h3>
        <P>NodeMCU is an open source platform based on ESP8266 which can connect objects and let data transfer using the Wi-Fi protocol. In addition, by providing some of the most important features of microcontrollers such as GPIO, PWM, ADC, and etc, it can solve many of the project's needs alone.</P>
        </div>
        </div>
</section>
                                    <!----------------projects---------------->
    
                                    <!----------------Campus---------------->
<section class="campus">
        <h1>ARDUINO</h1>
        <p1>ARDUINO RELATED PROJECTS</p1>
    
    <div class="row">
        
        <div class="campus-col">
        <img src="20210807_212619.jpg">
        <div class="layer">
        <h3><a href="" class="hero-btn">VIEW</a></h3>
        </div>
        </div>
         <div class="campus-col">
        <img src="20210529_124455.jpg">
        <div class="layer">
        <h3><a href="" class="hero-btn">VIEW</a></h3>
        </div>
        </div>
        <div class="campus-col">
        <img src="20210826_115306.png">
        <div class="layer">
        <h3><a href="" class="hero-btn">VIEW</a></h3>
            </div>
        </div>
    </div>
</section> 
                                    <!----------------facilities---------------->
 <section class="facilities">
     
    
    <div class="row">
        
        <div class="campus-col">
        <img src="20210807_212619.jpg">
        <div class="layer">
        <h3><a href="" class="hero-btn">VIEW</a></h3>
        </div>
        </div>
         <div class="campus-col">
        <img src="20210529_124455.jpg">
        <div class="layer">
        <h3><a href="" class="hero-btn">VIEW</a></h3>
        </div>
        </div>
        <div class="campus-col">
        <img src="20210826_115306.png">
        <div class="layer">
        <h3><a href="" class="hero-btn">VIEW</a></h3>
            </div>
        </div>
    </div>
</section>   
       <!----------------Enrollment---------------->
 <section class="cta">
     <h1>Enroll for more</h1>
     <a href="" class="hero-btn">CONTACT US</a>
</section>   
    
        <!----------------Enrollment---------------->
 
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
     <!----------------JavaScript for Toggle menu---------------->  
<script>
       var navLinks = document.getElementById("navLinks");
       function showmenu(){
       navLinks.style.right = "0";
     }
       function hidemenu(){
       navLinks.style.right = "-200px";
     }
</script>  
     <!----------------JavaScript for Toggle menu----------------> 
    
</body>
</html>
