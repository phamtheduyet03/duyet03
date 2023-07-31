<!DOCTYPE html>
<html lang="en" >
<head>

</head>
<body>
<!-- partial:index.partial.html -->
	
<html lang="en">

<head>

</head>

<body>
  <header class="header">
    <nav class="navbar">
      <div class="navbar-container container">
        <div>
          <h1 class="navbar-brand">Portfolio</h1>
        </div>
        <ul class="menu-items">
          <li><a href="#about">About</a></li>
          <li><a href="#my-works">Portfolio</a></li>
          <li><a href="#contact-me">Contact</a></li>
        </ul>
      </div>
    </nav>
	
    <div class="home-content" id="home-page">
      <div class="name">
        <h1>Xin chào, tôi là Phạm Thế Duyệt</h1>
        <p>I'm a Designer</p>
      </div>
      <div class="angle-down-icon">
        <a href="#about"><i class="fas fa-angle-down"></i></a>
      </div>
    </div>
  </header>
  <section class="about-me" id="about">
    <div class="container">
      <div class="about-content">
        <div class="left-content">
          <div>
           <h1 class="about-heading">About Me</h1>
          </div> 
          <img src="z4557236976534_bd8de98b7d95a1d2dbf9143446eb3227-removebg-preview.png" width="433" height="577" alt=""/>
          <p>
            Tôi là một Social Media Designer,tôi đến từ Việt Nam
          </p>
          <div class="work-arrow">
            <p>
              <a href="#my-works">XEM THÊM VỀ TÔI <i class="fas fa-arrow-down"></i></a>
            </p>
          </div>
        </div>
        <div class="skills">
          <div class="right-content">
            <div>
              <h1 class="skills-heading">My Skills</h1>
            </div>
            <div class="skills-bar">
              <div class="bar">
                <div class="info">
                  <span>ADOBE ILLUSTRATOR</span>
                </div>
                <div class="progress-line"><span class="html"></span></div>
                <div class="bar">
                  <div class="info">
                    <span>ADOBE PHOTOSHOP</span>
                  </div>
                  <div class="progress-line"><span class="css"></span></div>
                  <div class="bar">
                    <div class="info">
                      <span>ADOBE INDESIGN</span>
                    </div>
                    <div class="progress-line"><span class="bootstrap"></span></div>
                    <div class="bar">
                      <div class="info">
                        <span>ADOBE PREMIERE</span>
                      </div>
                      <div class="progress-line"><span class="javascript"></span></div>
                      <div class="bar">
                        <div class="info">
                          <span>ADOBE AFFTER EFFECTS</span>
                        </div>
                        <div class="progress-line"><span class="c"></span></div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="work-arrow-2">
              <p>
                <a href="#my-works">Check out my work <i class="fas fa-arrow-down"></i></a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
 </section>
  <section id="my-works">
    <div class="portfolio">
      <div class="proj-heading">
        <h1>Portfolio</h1>
      </div>
      <div class="portfolio-content container">
        <div class="proj-1">
          <img src="nametruoc.png" width="3544" height="2126" alt=""/><img src="Artboard 1.png" width="3544" height="2126" alt=""/>
          <div class="proj1-details">
            <i class="fab fa-html5"></i>
            <i class="fab fa-css3-alt"></i>
            <i class="fab fa-js"></i>
            <h2>Sản Phẩm/ Dự Án</h2>
            <p>Một số sản phẩm của tôi</p>
     
            </button>
            <button><a href="https://www.behance.net/gallery/176432115/Project?">Xem <i
              class="fas fa-external-link-alt"></i></a>
          </button>
          </div>
        </div>
        
        <div class="proj-2">
         <img src="phien.jpg" width="1811" height="2560" alt=""/>
          <div class="proj2-details">
            <i class="fab fa-html5"></i>
            <i class="fab fa-css3-alt"></i>
            <h2>Profile </h2>
            <p>Hồ sơ công việc</p>
        
            </button>
            <button><a href="https://www.behance.net/gallery/176432857/Profile?" target="blank">Xem <i
              class="fas fa-external-link-alt"></i></a>
          </button>
          </div>
          
        </div>
        <div class="more-work">
          <p>
            More
          </p>
          <a href="https://codepen.io/Duyt-Phm-Th" target="blank">CodePen</a>
        </div>
      </div>
    </div>
  </section>
  <div class="contact" id="contact-me">
    <div class="container">
      <div class="contact-content">
        <h2>Contact Me</h2>
        <p class="mail">
          Get in touch with me <i class="fas fa-arrow-right"></i> 2022104030263@student.tdmu.edu.vn
        </p>
        <p class="links">Or find me on:</p>
      
        
        <a href="https://github.com/theduyet03" target="blank"><i class="fab fa-github"></i> Github</a>
        <a href="https://www.behance.net/duyetphamthe" target="blank"><i class="fab fa-dev"></i> Behance</a>
      
        <a href="https://www.instagram.com/_teh.duytpe/" target="blank"><i class="fab fa-instagram"></i> Instagram</a>
      </div>
    </div>
  </div>
  <script type="text/javascript">
    $(document).ready(function () {
      $(window).scroll(function () {
        // checks if window is scrolled more than 500px, adds/removes solid class
        if ($(this).scrollTop() > 550) {
          $('.navbar').addClass('solid');
          $('.back-to-top').addClass('visible');
        } else {
          $('.navbar').removeClass('solid');
          $('.back-to-top').removeClass('visible');
        }

      });
    });
  </script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script>
    $(document).ready(function () {
      // Add smooth scrolling to all links
      $("a").on('click', function (event) {

        // Make sure this.hash has a value before overriding default behavior
        if (this.hash !== "") {
          // Prevent default anchor click behavior
          event.preventDefault();

          // Store hash
          var hash = this.hash;

          // Using jQuery's animate() method to add smooth page scroll
          // The optional number (800) specifies the number of milliseconds it takes to scroll to the specified area
          $('html, body').animate({
            scrollTop: $(hash).offset().top
          }, 800, function () {

            // Add hash (#) to URL when done scrolling (default click behavior)
            window.location.hash = hash;
          });
        } // End if
      });
    });
  </script>
</body>

</html>
<!-- partial -->
  
</body>
</html>
