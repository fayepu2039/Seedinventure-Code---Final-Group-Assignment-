<!DOCTYPE html>
<html lang="en">
<title>Faye Yifei Pu Personal Website</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Raleway", sans-serif}
.w3-quarter img{margin-bottom: -6px; cursor: pointer}
.w3-quarter img:hover{opacity: 0.8; transition: 0.3s}
}
</style>
<body class="w3-light-grey">

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-bar-block w3-black w3-animate-right w3-top w3-text-light-grey w3-large" style="z-index:3;width:250px;font-weight:bold;display:none;right:0;" id="mySidebar">
  <a href="javascript:void()" onclick="w3_close()" class="w3-bar-item w3-button w3-center w3-padding-32">CLOSE</a> 
  <a href="#" onclick="w3_close()" class="w3-bar-item w3-button w3-center w3-padding-16">GALLERY</a> 
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button w3-center w3-padding-16">ABOUT ME</a> 
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button w3-center w3-padding-16">CONTACT</a>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-white w3-xlarge w3-padding-16">
  <span class="w3-left w3-padding">Faye Yifei Pu</span>
  <a href="javascript:void(0)" class="w3-right w3-button w3-white" onclick="w3_open()">☰</a>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main w3-content" style="max-width:100%;margin-top:83px">

 <!-- Photo grid -->
 <div class="w3-row w3-grayscale-min">
    <div class="w3-quarter">
      <img src="https://i.ibb.co/f06qm0w/Screen-Shot-2020-08-06-at-2-19-37-PM.png" style="width:100%" onclick="onClick(this)" alt="Organizing the Rotman Commerce Non-profit Network Flagship Conference 2020">
      <img src="https://i.ibb.co/S06j793/deca.jpg" style="width:100%" onclick="onClick(this)" alt="As one of the UTSG delegates at the 2019 DECA U Competition">
      <img src="https://i.ibb.co/4sJcR5n/YIFEIPU-NIGHT-IN-DOWNTOWN-PEOPLE-WILLIAM-J-DOWKES-AWARD.jpg" style="width:100%" onclick="onClick(this)" alt="At Xintiandi, Shanghai">
      
   </div>
    
    <div class="w3-quarter">
      <img src="https://i.ibb.co/bXq8Lv6/IMG-3794.jpg" style="width:100%" onclick="onClick(this)" alt="At the 2020 CSR & U Event hosted by Rotman Commerce Non-profit Network" >
      <img src="https://i.ibb.co/RT70VjS/IMG-6063.jpg" style="width:100%" onclick="onClick(this)" alt="Recharge on the weekend">
    
      

    </div>
    
    <div class="w3-quarter">
      <img src="https://i.ibb.co/ftn2S5d/IMG-2872.jpg" style="width:100%" onclick="onClick(this)" alt="Being part of the International Mentor Team at Victorai College, University of Toronto">
      <img src="https://i.ibb.co/vP76pDb/IMG-3763.jpg" style="width:100%" onclick="onClick(this)" alt="Competing at the Techtrade Competition at Rotman Commerce">
      <img src="https://i.ibb.co/WtbXFFY/4252-BC32-991-D-4-EA9-A250-F25-E1-BA345-A9.jpg" style="width:100%" onclick="onClick(this)" alt="As the mentor for International Student Orientation at Victoria College, University of Toronto">
    </div>

    <div class="w3-quarter">
      <img src="https://i.ibb.co/3ft5Fz3/IMG-6990.jpg" style="width:100%" onclick="onClick(this)" alt=" Co-hosted a theatre camp for students in China ">
      <img src="https://i.ibb.co/XY0NBw8/IMG-7998-2.jpg" style="width:100%" onclick="onClick(this)" alt="First Flute at American Music Abroad Concert Band & Orchestra, toured in US & Europe">
      <img src="https://i.ibb.co/wS2CRBb/IMG-6453.jpg" style="width:100%" onclick="onClick(this)" alt="Visiting a museum in Shangahi, as part of Columbia University's Shanghai Symposium program inspired by the Columbia Core Curriculum ">
      <img src="https://i.ibb.co/YLn09q9/IMG-5205.jpg" style="width:100%" onclick="onClick(this)" alt="Solo Jazz performance with American Music Abroad Concert Band & Orchestra">
    </div>
  </div>

  <!-- Pagination -->
  <div class="w3-center w3-padding-32">
    <div class="w3-bar">
      <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
      <a href="#" class="w3-bar-item w3-black w3-button">1</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">3</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">4</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
    </div>
  </div>
  
  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-black w3-xlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>
  


  <!-- About section -->
  <div class="w3-container w3-dark-grey w3-center w3-text-light-grey w3-padding-32" id="about">
    <h4><b>About Me</b></h4>
    <h5>Student Leader at Rotman Commerce; Aspiring Enterpreneur, Consultant, Accountant</h5>
    <img src="https://i.ibb.co/NZYLpwr/IMG-4725.jpg" alt="Me" class="w3-image w3-padding-32" width="500" height="500">

    <div class="w3-content w3-justify" style="max-width:600px">
      <h4>Faye Yifei Pu</h4>
      <p> I am an International student from Shanghai, China. I moved to Toronto, Canada in Grade 10 where I attended the All Girls Boarding School at Havergal College. As a single child, being a boarder away from my family 
          at such a young age taught me to be resilient, independent, and strong. The all-girls' education empowered me to explore and achieve my full potential, knowing that girls are capable of excelling high. With my interest in business 
          and desire to access liberal arts courses, I decided to attend the University of Toronto. </p>
      <p>Now, I am going into my third year of Accounting Specialist, with a minor in Philosophy. I am involved in various student groups on campus as a student leader, including 
          Director of Events at Rotman Commerce Non-profit Network, President at Victoria International Student Association, just to name a few. In terms of my professional experience, I have been exposed to different fields, including tech-startup, non-profit, etc. 
          I am actively looking for internship for Summer 2021, hopefully related to Accounting, Consulting, or Business Analysis. 

      </p>
      

      <hr class="w3-opacity">
      <h4 class="w3-padding-16">Soft Skills</h4>
      <p class="w3-wide">Teamwork</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:95%">95%</div>
      </div>
      <p class="w3-wide">Problem-solving</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:85%">85%</div>
      </div>
      <p class="w3-wide">Leadership</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:80%">85%</div>
      </div>
      <h4 class="w3-padding-16">Technical Skills</h4>
      <p class="w3-wide">Microsoft (Word, PowerPoint, Excel, VBA)</p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:95%">90%</div>
      </div>
      <p class="w3-wide">Web Design (Html, CSS, Javascript) </p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:85%">70%</div>
      </div>
      <p class="w3-wide">Tableau </p>
      <div class="w3-white">
        <div class="w3-container w3-padding-small w3-center w3-grey" style="width:80%">65%</div>
      </div>

      <a href="https://documentcloud.adobe.com/link/track?uri=urn:aaid:scds:US:9bd97ee0-b331-46c7-9c05-70c03224fa16" class = "w3-button w3-light-grey w3-padding-large w3-margin-top w3-margin-bottom w3-hover-black" >Download resume</a>
      
<!--projects-->
<!-- Section heading -->
<hr class="w3-opacity">

<h2 class="h1-responsive font-weight-bold my-5 w3-center ">My projects</h2>
<!-- Section description -->
<p class="grey-text w-responsive mx-auto mb-5"> During University, I have been part of different engagements where I have worked on projects related to fields like Consulting, Social Innovation, and Coding. </p>



<!-- Grid row -->

<div class="w3-container w3-dark-grey w3-center w3-text-light-grey w3-padding-32" id= "projects">
    <img src="https://mdbootstrap.com/img/Photos/Others/laptop-sm.jpg" alt="Me" class="w3-image w3-padding-32 img-fluid" width="900" height="600">

    <div class="card-body">
      <a href="https://mdbootstrap.com/img/Photos/Others/laptop-sm.jpg" class="green-text">
        <h5 class="font-weight-bold mt-2 mb-3"><i class="fas fa-chart-line pr-2"></i>Social Innovation & Coding </h5>
      </a>
      <div class="green-text">
        <h5 class="font-weight-bold mt-2 mb-3"><i class="fas fa-chart-line pr-2"></i>Digital Innovation in Emerging Markets, Code for Asia, SeedinVenture  </h5>
      </a>
      <h4 class="font-weight-bold mb-3"> Project 1: An online platform that empowers relocated families in China - Summer 2020  </h4>
      
      <p> Led a team of 5 to analyze issues related to neighbourhood demolition and relocation in China, and designed a digital ecosystem that allows relocated families to connect with those in the new neighbourhood </p>
      
    </div>
  </div>
  <!-- Grid column -->

  <hr class="w3-opacity">

  <div class="w3-container w3-dark-grey w3-center w3-text-light-grey w3-padding-32" id="about"></div>
    <ul class="w3-ul w3-white w3-center ">
      <li class="w3-black w3-xlarge w3-padding-32">Fun Facts About Me </li>
      <li class="w3-padding-16">I have two dogs</li>
      <li class="w3-padding-16"> I am teaching myself guitar by watching Youtube videos</li>
      <li class="w3-padding-16"> I recently went out to a beach at 2:30 AM to see the Perseids Meteor Shower </li>
      </li>
    </ul>
  </div>
</div>
</div>
</div>

 




  <!-- Contact section -->

  <div class="w3-container w3-light-grey w3-padding-32 w3-padding-large" id="contact">
    <div class="w3-content" style="max-width:600px">
      <h4 class="w3-center"><b>Contact Me</b></h4>
      <p> Feel free to fill out this form and connect with me. I love meeting and chatting with new people!</p>
      <form action="/action_page.php" target="_blank">
        <div class="w3-section">
          <label>Name</label>
          <input class="w3-input w3-border" type="text" name="Name" required>
        </div>
        <div class="w3-section">
          <label>Email</label>
          <input class="w3-input w3-border" type="text" name="Email" required>
        </div>
        <div class="w3-section">
          <label>Message</label>
          <input class="w3-input w3-border" type="text" name="Message" required>
        </div>
        <button type="submit" class="w3-button w3-block w3-black w3-margin-bottom">Send Message</button>
      </form>
    </div>
  </div>

  <!-- Footer -->
  <footer class="w3-container w3-padding-32 w3-grey">  
    <div class="w3-row-padding">
      <div class="w3-third">
        <h3>Contact Info</h3>
        <p> yifei.pu@mail.utoronto.ca; </p>
        <p> fayepu2039@gmail.com</p>
        <p>tel: (+1)647-979-0309</p>      
      </div>


    
      <div class="w3-third">
        <h3>Social Media</h3>
        <ul class="w3-ul">
          <li class="w3-padding-16 w3-hover-black">
            <img src="/w3images/workshop.jpg" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Facebook</span><br>
          </li>
          <li class="w3-padding-16 w3-hover-black">
            <img src="linkedin.com/in/yifeipu" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Linkedin</span><br>
          </li> 
        </ul>
      </div>

     

      <div class="w3-third">
        <h3>POPULAR TAGS</h3>
        <p>
          <span class="w3-tag w3-black w3-margin-bottom">Travel</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Shanghai</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">North America</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Philosphy</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Consulting</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Enterpreneurship</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Accounting </span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Business</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Language</span>
          <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Spanish</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Coding</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Startup</span>
         
         
        </p>
      </div>
    </div>
  </footer>
  


<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}

function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

</script>


</body>
</html>

