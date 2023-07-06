<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA_Compatible" content="IE-edge">
    <meta name="viewport" content="width-device-width, initial-scale=1.0">
    <title>Naveen Nekkanti- Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/aa83cdd7e7.js" crossorigin="anonymous"></script>
  </head>
  <body>
  <div id="header">
    <div class="container">
        <nav>
           <img src="logo.png" class="logo">
           <ul id="sidemenu">
            <li><a href="#header">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#contact">Contact</a></li>
            <i class="fas fa-times" onclick="closemenu()"></i>
           </ul>
           <i class="fas fa-bars" onclick="closemenu()"></i>
        </nav>
        <div class="header-text">
          <p>Web Developer</p>
          <h1>Hi I'm<span> Naveen</span><br>Nekkanti From India</h1>
        </div>
    </div>
  </div>
  <!------------about------------>
  <div id="about">
     <div class="container">
      <div class="row">
        <div class="about-col-1">
          <img src="pic3.jpg">
        </div>
        <div class="about-col-2">
          <h1 class="sub-title">About Me</h1>
          <p>I am an enthusiastic, self-motivated, reliable, responsible and hard working person. 
            I am a mature team worker and adaptable to all challenging situations. I am able to 
            work well both in a team environment as well as using own initiative. I am able to 
            work well under pressure and adhere to strict deadlines.</p>
            <div class="tab-titles">
              <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
              <p class="tab-links" onclick="opentab('education')">Education</p>
              <p class="tab-links" onclick="opentab('experience')">Experience</p>
            </div>
            <div class="tab-contents active-tab" id="skills">
              <ul>
                <li><span>WEB DESIGN</span><br> Desigining Best Websites</li>
                <li><span>UI/UX</span><br> Desigining Web/App interfaces</li>
                <li><span>Python</span><br> For Developing</li>
              </ul>
            </div>
            <div class="tab-contents" id="education">
              <ul>
                <li><span>2019</span><br> Graduated From Gowtham High School</li>
                <li><span>2019-2021</span><br> Graduated From Srichaitanya Institutes</li>
                <li><span>2021-Current</span><br>Pursing B.Tech Degree in SRM University AP</li>
              </ul>
            </div>
            <div class="tab-contents" id="experience">
              <ul>
                <li><span>2023-APSSDC</span><br>Worked as Web Technoliges-Django</li>
                <li><span>2023-APSSDC</span><br>Worked as Web Technoliges-Django</li>
                <li><span>2023-APSSDC</span><br>Worked as Web Technoliges-Django</li>
              </ul>
            </div>
        </div>
      </div>
     </div>
  </div>
  <!-------------------------Projects----------------->
  <div id="projects">
    <div class="container">
      <h1 class="sub-title">My Projects</h1>
      <div class="projects-list">
           <div>
            <i class="fas fa-code"></i>
            <h2>Web Development</h2>
            <p>The Web Development is used to create a effective Websites
              Web development refers to the creating, building, and maintaining of websites. 
              It includes aspects such as web design, web publishing, web programming, and 
              database management. It is the creation of an application that works over 
              the internet i.e. websites.</p>
              <a href="https://naveennekkanti1.github.io/"><i class="fas fa-external-link-alt"></i></a>
           </div>
           <div>
            <i class="fas fa-crop-alt"></i>
            <h2>UI/UX</h2>
            <p>The Web Development is used to create a effective Websites
              Web development refers to the creating, building, and maintaining of websites. 
              It includes aspects such as web design, web publishing, web programming, and 
              database management. It is the creation of an application that works over 
              the internet i.e. websites.</p>
              <a href=""><i class="fas fa-external-link-alt"></i></a>

           </div>
           <div>
            <i class="fab fa-app-store"></i>
            <h2>Python Development</h2>
            <p>The Web Development is used to create a effective Websites
              Web development refers to the creating, building, and maintaining of websites. 
              It includes aspects such as web design, web publishing, web programming, and 
              database management. It is the creation of an application that works over 
              the internet i.e. websites.</p>
              <a href="#">Learn From Best</a>
           </div>
      </div>
    </div>

  </div>
  <!-------------------------Certifications----------------->
  <div id="certificate">
    <div class="container">
      <h1 class="sub-title">Certifications</h1>
    <div class="certificate-list">
        <div class="certificate">
          <img src="certificate1.jpg">
          <div class="layer">
             <h3>Innvoccaer</h3>
             <p>It was an hacakthon which was conducted by the 
              Innvoccaer in association with Microsoft.</p>
          </div>
        </div>
        <div class="certificate">
          <img src="certificate2.jpg">
          <div class="layer">
            <h3>Innvoccaer</h3>
            <p>It was an hacakthon which was conducted by the 
             Innvoccaer in association with Microsoft.</p>
         </div>
        </div>
        <div class="certificate">
          <img src="certificate3.jpg">
          <div class="layer">
            <h3>Innvoccaer</h3>
            <p>It was an hacakthon which was conducted by the 
             Innvoccaer in association with Microsoft.</p>
         </div>
        </div>
        <div class="certificate">
          <img src="certificate4.jpg">
          <div class="layer">
            <h3>Innvoccaer</h3>
            <p>It was an hacakthon which was conducted by the 
             Innvoccaer in association with Microsoft.</p>
         </div>
        </div>
    </div>
    </div>
  </div>
  <!------------------Contact------------------>
  <div id="contact">
    <div class="container">
      <div class="row">
           <div class="contact-left">
               <h1 class="sub-title">Contact Me</h1>
               <p><i class="fas fa-paper-plane"></i> naveen_nekkanti@srmap.edu.in</p>
               <p><i class="fas fa-phone-square-alt"></i> 9550110355</p>
               <div class="social-icons">
                  <a href=""><i class="fab fa-facebook"></i></a>
                  <a href=""><i class="fab fa-instagram"></i></a>
                  <a href="https://www.linkedin.com/in/durga-naveen-nekkanti-836aaa1a7/"><i class="fab fa-linkedin"></i></a>
               </div>
                <a href="Resume.pdf" class="btn btn2"> Download CV</a>
           </div>
           <div class="contact-right">
              <form name="submit-to-google-sheet">
                <input type="text" name="Name" placeholder="Your Name" required>
                <input type="email" name="Email" placeholder="Your Email" required>
                <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                <button type="submit" class="btn btn2">Submit</button>
              </form>
              <span id="msg">Hello</span>
           </div>
      </div>
    </div>
    <div class="copyright">
      <p>Copyright © Naveen Nekkanti</p>
    </div>
  </div>
  <script>
    var tablinks=document.getElementsByClassName("tab-links");
    var tabcontents=document.getElementsByClassName("tab-contents");
    function opentab(tabname){
      for(tablink of tablinks){
        tablink.classList.remove("active-link")
      }
      for(tabcontent of tabcontents){
        tabcontent.classList.remove("active-tab")
      }
      event.currentTarget.classList.add("active-link");
      document.getElementById(tabname).classList.add("active-tab");
    }
  </script>
  <script>
    var sidemenu=document.getElementById("sidemenu");
    function openmenu(){
      sidemenu.style.right="0";
    }
    function closemenu(){
      sidemenu.style.right="-200px";
    }
  </script>
  <script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbyGLrJmFFRJ3RuoJW2czC5qNg05JtCZUdD6DSL_uddlzTIcaOxEMXdAHgnoBOq-9KArgw/exec'
    const form = document.forms['submit-to-google-sheet']
    const msg=document.getElementById("msg")
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
          msg.innerHTML = "Message sent successfully"
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
