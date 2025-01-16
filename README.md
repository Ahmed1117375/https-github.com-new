# https-github.com-new
Ahmed
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
    <style>
      .home {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 50px;
      }

      .home-content {
        max-width: 45%;
      }

      .home-image {
        max-width: 55%;
      }

      .home-image img {
        width: 100%;
        height: auto;
        max-width: 100%;
        border: none;
        box-shadow: none;
      }

      .profile-box:hover .profile-layer {
        transform: translateY(0);
      }

      .profile-layer {
        position: absolute;
        bottom: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: linear-gradient(rgba(0, 0, 0, 0.1), var(--main-color));
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        text-align: center;
        padding: 0 4rem;
        transform: translateY(100%);
        transition: 0.5s ease;
      }

      .profile-box:hover img {
        transform: scale(1.1);
      }

      .profile-box img {
        width: 100%;
        transition: 0.5s ease;
      }

      @media (max-width: 768px) {
        .home {
          flex-direction: column;
          text-align: center;
        }

        .home-content,
        .home-image {
          max-width: 100%;
        }

        .home-image {
          margin-top: 20px;
        }

        .home-image img {
          max-width: 100%;
        }
      }
    </style>
    <title>Document</title>
  </head>
  <body>
    <header class="header">
      <a href="#" class="logo">Ahmed</a>
      <nav class="navabar">
        <a href="#home" class="active">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#profile">Profile</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="home" id="home">
      <div class="home-content">
        <h3>Hello, It's me</h3>
        <h1>Ahmed Hafez</h1>
        <h3>and I'm a <span class="multiple-text"></span></h3>
        <p>
          My name is Ahmed Hafez, a student in the first year of secondary
          school at a religious institute.
        </p>

        <div class="social-media">
          <a href="#"><i class="bx bxl-facebook"></i></a>
          <a href="#"><i class="bx bxl-github"></i></a>
          <a href="#"><i class="bx bxl-instagram"></i></a>
          <a href="#"><i class="bx bxl-linkedin"></i></a>
        </div>
        <a href="#" class="btn">Look at my work</a>
      </div>
      <section class="home" id="home">
        <div class="home-img">
          <img src="image (6) (2).png" alt="Home Image" />
        </div>
      </section>
    </section>

    <section class="about" id="about">
      <div class="about-img">
        <img src="image (2) (1).png" alt="About Image" />
      </div>
      <div class="about-content">
        <h2 class="heading">About <span>Me</span></h2>
        <h3>Frontend Developer</h3>
        <p>
          Hi, I'm Ahmed, a first-year secondary school student. I love learning
          programming, especially web development with HTML, CSS, and
          JavaScript. I enjoy working on small projects and improving my skills
          every day. My goal is to become a professional web developer in the
          future. For me, programming is more than a hobby; it's a way to
          understand and contribute to the digital world.
        </p>
        <a href="#" class="btn">Read More</a>
      </div>
    </section>

    <section class="services" id="services">
      <h2 class="heading">Our <span>Services</span></h2>
      <div class="services-container">
        <div class="services-box">
          <i class="bx bx-code-alt"></i>
          <h3>Web Development</h3>
          <p>
            I specialize in creating modern, responsive, and user-friendly
            websites. My focus is on delivering quality and innovation that
            perfectly meets your business needs.!
          </p>
          <a href="#" class="btn">Read More</a>
        </div>

        <div class="services-box">
          <i class="bx bxs-paint"></i>
          <h3>Graphic Design</h3>
          <p>
            I provide graphic design services that bring your ideas to life with
            creativity and precision. Let me help you stand out with unique and
            exceptional visuals.
          </p>
          <a href="#" class="btn">Read More</a>
        </div>

        <div class="services-box">
          <i class="bx bx-bar-chart-alt"></i>
          <h3>Digital Marketing</h3>
          <p>
            "I help you connect with your audience using digital marketing
            strategies. Whether it's SEO or social media, I work to grow your
            online presence and help your business succeed."
          </p>
          <a href="#" class="btn">Read More</a>
        </div>
      </div>
    </section>

    <section class="profile" id="profile">
      <h2 class="heading">latest <span>Project</span></h2>

      <div class="profile-container">
        <div class="profile-box">
          <img src="portfolio1.jpg" alt="" />
          <div class="profile-layer">
            <h4>Web Design</h4>
            <p>
              A sleek, modern website tailored for a tech startup to showcase
              their innovative products.
            </p>
            <a href="#"><i class="bx bx-link-external"></i></a>
          </div>
        </div>

        <div class="profile-box">
          <img src="portfolio2.jpg" alt="" />
          <div class="profile-layer">
            <h4>Web Design</h4>
            <p>
              A creative portfolio website built for a photographer to highlight
              their stunning work.
            </p>
            <a href="#"><i class="bx bx-link-external"></i></a>
          </div>
        </div>

        <div class="profile-box">
          <img src="portfolio3.jpg" alt="" />
          <div class="profile-layer">
            <h4>Web Design</h4>
            <p>
              A responsive e-commerce platform designed to enhance user
              experience and increase sales.
            </p>
            <a href="#"><i class="bx bx-link-external"></i></a>
          </div>
        </div>

        <div class="profile-box">
          <img src="portfolio4.jpg" alt="" />
          <div class="profile-layer">
            <h4>Photoshop Design</h4>
            <p>The image has been designed and modified professionally</p>
            <a href="#"><i class="bx bx-link-external"></i></a>
          </div>
        </div>

        <div class="profile-box">
          <img src="portfolio5.jpg" alt="" />
          <div class="profile-layer">
            <h4>Photoshop Design</h4>
            <p>The image has been designed and modified professionally</p>
            <a href="#"><i class="bx bx-link-external"></i></a>
          </div>
        </div>

        <div class="profile-box">
          <img src="portfolio6.jpg" alt="" />
          <div class="profile-layer">
            <h4>Photoshop Design</h4>
            <p>The image has been designed and modified professionally</p>
            <a href="#"><i class="bx bx-link-external"></i></a>
          </div>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <h2 class="heading">contact <span>Me!</span></h2>
      <form action="#">
        <div class="input-box">
          <input type="text" placeholder="Full Name" />
          <input type="email" placeholder="Email Address" />
        </div>
        <div class="input-box">
          <input type="number" placeholder="Mobile Number" />
          <input type="text" placeholder="Email subject" />
        </div>
        <textarea
          name=""
          id=""
          cols="30"
          rows="10"
          placeholder="Your Message"
        ></textarea>
        <input type="submit" value="Send Mesaage " class="btn" />
      </form>
    </section>

    <footer class="footer">
      <div class="footer-text">
        <p>copyright &copy; 2025 by Ahmed Hafez All rights reserved</p>
      </div>

      <div class="footer-icontop">
        <a href="#home"><i class="bx bx-up-arrow-alt"></i></a>
      </div>
    </footer>
    <script src="https://unpkg.com/scrollreveal"></script>
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
    <script src="script.js"></script>
  </body>
</html>
