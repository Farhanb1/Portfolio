<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="STYLE.CSS">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <script src="https://kit.fontawesome.com/c4254e24a8.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
<div class="container">
    <nav>
        <img src="image/logoo.JPG" class="logo">
        <ul id="sidemenu">
               <li><a href="#header">Home</a></li>
               <li><a href="#about">About</a></li>
               <li><a href="#services">Services</a></li>
               <li><a href="#portfolio">Portfolio</a></li>
               <li><a href="#contact">Contact</a></li>
               <i class="fa-solid fa-circle-xmark" onclick="closemenu()"></i>
        </ul>
        <i class="fa-solid fa-bars" onclick="openmenu()"></i>
    </nav>
    <div class="header-text">
        <p>UI/UX Designer</p>
        <h1> Hi,I'm <span> Bhat Farhan </span> <br>From Kashmir</h1>
        
    </div> 
</div>
</div>
<!-----------------ABOUT---------------->
<div id="about">
    <div class="container">
        <div class="row">
            <div class="aboutcol1">
                <img src="image/inm1.jpeg">
            </div>
            <div class="aboutcol2">
                <h1 class="subtitle" >About Me </h1>
                <P>I am a Computer Engineering Graduate From Govt Degree Collage Anantnag...<br>Technology excites me and I am always in awe of the change it drives in the world.<br> Certain skills that I have worked with include <br><span> Data Structures and Algorithms (C)</span><br> <span> App Development(Kotlin)</span> <br><span>Web Development (Html, Css, JavaScript)</span> <br><span>Graphics Designing (Adobe Premium Pro )</span>  <br><span>Designing (with CorelDraw)..</span> <br>And what I might lack in skills I make up for with my determination to learn...
                    Outside of tech, I am a poet, an avid actor and have spent my college days exploring theatre.</P>
                <div class="taptittle">
                    <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                    <p class="tab-links" onclick="opentab('Expreience')">Expreience</p>
                    <p class="tab-links" onclick="opentab('Education')">Education</p>
                </div>
                <div class="tab-contents active-tab" id="skills">
                    <ul>
                    <li><span>UI/UX</span><br> Desiging Web/App interface</li>
                    <li><span>App Development</span><br> Building Android App</li>
                    <li><span>Video Editor</span><br>Make Youtube Video</li>
                    </ul>
                </div>
                <div class="tab-contents" id="Expreience">
                    <ul>
                    <li><span>2022-2023</span><br>Video Editor at Encreator Company</li>
                    <li><span>2020-2022</span><br>Graphics Designer at Samir Sign</li>
                    </ul>
                </div>
                <div class="tab-contents" id="Education">
                    <ul>
                    <li><span>2023-present</span><br>Bachleor in Computer Application At Govt Degree Collage Anantnag </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<!-----------------services---------------->
<div id="services">
    <div class="conatiner">
        <h1 class="subtitle" >My services </h1>
        <div class="serviceslist">
            <div>
                <i class="fa-brands fa-uikit"></i>
                <h2>UI/UX</h2>
                <p>I provide UI/UX services that prioritize intuitive design, seamless navigation, user-centric interfaces, and enhanced digital experiences for optimal engagement.</p>
                <a href="">Learn More</a>
            </div>
            <div>
                <i class="fa-brands fa-app-store"></i>
                <h2>App Development</h2>
                <p>I offer app development services, creating responsive, feature-rich, and user-friendly applications tailored to meet client-specific needs and goals.</p>
                <a href="">Learn More</a>
            </div>
            <div>
                <i class="fa-solid fa-video"></i>
                <h2>Video Editing</h2>
                <p>I provide video editing services, delivering polished, engaging content with seamless transitions, effects, and storytelling tailored to client vision.</p>
                <a href="">Learn More</a>
            </div>
            
        </div>
    </div>
</div>

<!-----------------potfolio---------------->
<div id="portfolio">
    <div class="container">
        <h1 class="subtitle" >My Work </h1>
        <div class="worklist">
            <div class="work">
                <img src="/image/work 1.png">
                <div class="layer">
                    <h3> Mobile App</h3>
                    <p>I specialize in Android app development, delivering customized, user-friendly solutions with responsive interfaces and robust functionality. My services include designing, coding, and optimizing apps to ensure smooth performance, tailored features, and seamless user experiences for diverse business needs.                    </p>
                    <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="/image/WORK2.png">
                <div class="layer">
                    <h3>UI/UX Desiging</h3>
                    <p>I offer comprehensive UI/UX design services focused on creating intuitive, user-centered digital experiences. My work includes wireframing, prototyping, and user interface design, ensuring seamless navigation, enhanced usability, and visually appealing interfaces that align with client goals and user needs.</p>
                    <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="/image/work3.png">
                <div class="layer">
                    <h3>Video Editing</h3>
                    <p>I offer professional video editing services, specializing in creating dynamic, visually compelling content. From cutting-edge transitions and effects to color correction and sound design, I tailor each project to meet your unique vision, ensuring high-quality, engaging results.</p>
                    <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn"> See More</a>
    </div>
</div>
<!----------------contact---------------->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contactleft">
                <h1 class="subtitle" >Contact Me</h1>
                <p><i class="fa-solid fa-envelope"></i>farhanbashirb786@gmail.com</p>
                <p><i class="fa-solid fa-phone"></i>+91 6006360019</p>
                <div class="socialicon">
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="#"><i class="fa-brands fa-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
                </div>
                <a href="/image/Resume.pdf" download class="btn btn2">Download CV</a>
            </div>
            <div class="contactright">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="Email" placeholder="Your email" required>
                    <textarea name="Meesage" rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    
</div>



<script>
    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");
   
    function opentab(tabname){
        for(tablink of tablinks) {
        tablink.classList.remove("active-link");
    }
        for (tabcontent of tabcontents) {
        tabcontent.classList.remove("active-tab");
    }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab");
    }
</script>

<script>
    var sidemenu =document.getElementById("sidemenu");

    function openmenu(){
        sidemenu.style.right ="0";
    }
    function closemenu(){
        sidemenu.style.right ="-200px";
    }
</script>
<script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbxZ4qIdRX6cXhwXBGLJ5xjJq-snlx1ooshT1kRGfeWbNcbknt0d2nfvTF0gbh12HXY7Kg/exec'
    const form = document.forms['submit-to-google-sheet']
    const msg =document.getElementById("msg")
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerHTML="Message sent successfully"
            setTimeout(function(){
                msg.innerHTML=""
            },5000)
            form.reset()
        })
        .catch(error => console.error('Error!', error.message))
    })
  </script>

</body>
</html>
