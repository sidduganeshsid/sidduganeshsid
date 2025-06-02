<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Siddu Ganesh | Portfolio</title>



  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="https://avatars.githubusercontent.com/u/94279014?v=4" type="image/x-icon">

  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">

  <!--
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

</head>

<body>

  <!--
    - #MAIN
  -->

  <main>

    <!--
      - #SIDEBAR
    -->

    <aside class="sidebar" data-sidebar>

      <div class="sidebar-info">

        <figure class="avatar-box">
          <img style="border-radius: 8%;" src="https://avatars.githubusercontent.com/u/94279014?v=4"
            alt="Siddu Ganesh Musa" width="80">
        </figure>

        <div class="info-content">
          <h1 class="name" title="Siddu Ganesh Musa">Siddu Ganesh<br />Musa</h1>

          <p class="title">Web Development & DevOps</p>
        </div>

        <button class="info_more-btn" data-sidebar-btn>
          <span>Show Contacts</span>

          <!-- <ion-icon name="chevron-down"></ion-icon> -->
          <img name="chevron-down" src="./assets/images/icons/downarrow.png" alt="" width="20px">
        </button>

      </div>

      <div class="sidebar-info_more">

        <div class="separator"></div>

        <ul class="contacts-list">

          <li class="contact-item">

            <div class="icon-box">
              <!-- <ion-icon name="mail-outline"></ion-icon> -->
              <img width="16px" class="icon" src="./assets/images/icons/email.png" alt=""
                style="-webkit-filter: invert(100%);">
            </div>

            <div class="contact-info">
              <p class="contact-title">Email</p>

              <a href="mailto:sidduganeshm@gmail.com" class="contact-link">sidduganeshm@gmail.com</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <!-- <ion-icon name="location-outline"></ion-icon> -->
              <img src="./assets/images/icons/location.png" alt="" width="16px" style="-webkit-filter: invert(100%);">
            </div>

            <div class="contact-info">
              <p class="contact-title">Location</p>

              <address>Hyderabad, Telangana, India.</address>
            </div>

          </li>

        </ul>

        <div class="separator"></div>

        <ul class="social-list">

          <li class="social-item">
            <!-- <a href="#" class="social-link">
              <ion-icon name="logo-facebook"></ion-icon>
            </a> -->
            <a href="https://linkedin.com/in/sidduganesh"><img src="assets/images/social/linkedin.png" alt=""
                width="25px" style="-webkit-filter: invert(100%);"></a>
          </li>

          <li class="social-item">
            <!-- <a href="#" class="social-link">
              <ion-icon name="logo-twitter"></ion-icon>
            </a> -->
            <a href="https://github.com/sidduganeshsid"><img src="assets/images/social/github.png" alt="" width="25px"
                style="-webkit-filter: invert(100%);"></a>
          </li>

          <li class="social-item">
            <!-- <a href="#" class="social-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a> -->
          </li>

        </ul>

      </div>

    </aside>





    <!--
      - #main-content
    -->

    <div class="main-content">

      <!--
        - #NAVBAR
      -->

      <nav class="navbar">
        <ul class="navbar-list">

          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Resume</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Projects</button>
          </li>

          <!-- <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Blog</button>
          </li> -->

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
          </li>

        </ul>
      </nav>

      <!--
        - #ABOUT
      -->
      <article class="about  active" data-page="about">

        <header>
          <h2 class="h2 article-title">About me</h2>
        </header>

        <section class="about-text">
          <p>
            I am a self-driven and passionate tech enthusiast with expertise in web development and DevOps. My skill set
            includes frontend development, Linux, AWS, Git, and containerizing applications. I am proficient in building
            CI/CD pipelines using tools like Jenkins, ensuring smooth and efficient deployment processes. I thrive on
            solving complex problems, learning new technologies, and delivering high-quality solutions.
          </p>

          <p>
            I aspire to obtain a challenging position in your organization in the IT field, where I can contribute to
            its growth and success while fostering my own professional development. I am eager to utilize my technical
            skills and dedication to support the organization’s goals and overall welfare.
          </p>
        </section>


        <!--
          - service
        -->

        <section class="service">

          <h3 class="h3 service-title">What i'm doing</h3>

          <ul class="service-list">



            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-dev.svg" alt="Web development icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Web development</h4>

                <p class="service-item-text">
                  Able to develop, build and maintain frontend and work at backend.
                </p>
              </div>

            </li>
            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/devops.png" alt="devops icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">DevOps</h4>

                <p class="service-item-text">
                  DevOps Engineer focused on optimizing SDLC processes for faster and efficient delivery.
                </p>
              </div>

            </li>



          </ul>

        </section>


        <!--
          - testimonials
        -->



        <!-- </ul>

        </section> -->


        <!--
          - testimonials modal
        -->

        <div class="modal-container" data-modal-container>

          <div class="overlay" data-overlay></div>

          <section class="testimonials-modal">

            <button class="modal-close-btn" data-modal-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>

            <div class="modal-img-wrapper">
              <figure class="modal-avatar-box">
                <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img>
              </figure>

              <img src="./assets/images/icon-quote.svg" alt="quote icon">
            </div>

            <div class="modal-content">

              <h4 class="h3 modal-title" data-modal-title>siddu ganesh</h4>

              <time datetime="2021-06-14">14 June, 2021</time>

              <div data-modal-text>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem id consequatur blanditiis alias.
                  Numquam sit nisi exercitationem voluptas totam necessitatibus sunt, odio nulla deleniti eveniet dolor,
                  accusantium velit enim. Voluptates!
                </p>
              </div>

            </div>

          </section>

        </div>


        <!--
          - clients
        -->

        <!-- <section class="clients">

          <h3 class="h3 clients-title">Clients</h3>

          <ul class="clients-list has-scrollbar">

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-1-color.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-2-color.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-3-color.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-4-color.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-5-color.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-6-color.png" alt="client logo">
              </a>
            </li>

          </ul>

        </section> -->

      </article>

      <!--
        - #RESUME
      -->
      <article class="resume" data-page="resume">

        <header>
          <h2 class="h2 article-title" style="display: flex;">Resume <a href="./assets/SidduGaneshMusa_Resume.pdf"><img
                width="45px" src="./assets/images/—Pngtree—file download icon_4720205.png" alt=""
                style="-webkit-filter: invert(100%);"></a></h2>
        </header>

        <!-- ##skills -->
        <section class="skill">

          <h3 class="h3 skills-title">My skills</h3>

          <ul class="skills-list content-card">

            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">HTML</span>
            </li>
            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">CSS</span>
            </li>
            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">JavaScript</span>
            </li>
            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">Tailwind CSS</span>
            </li>
            <br />

            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">Java</span>
            </li>
            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">Spring Boot</span>
            </li>
            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">MySQL</span>
            </li>
            <br />

            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">Git - GitHub</span>
            </li>
            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">Docker - Docker Hub</span>
            </li>
            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">Ansible (configuration management)</span>
            </li><br />

            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px;  color: white;">Linux ( ubuntu | Amazon | RHEL ... )</span>
            </li>

            <li class="skills-item">
              <!-- <img src="assets/images/devops.png" alt="" width="25px"> -->
              <span style="padding-left: 4px; color: white;">AWS Cloud</span>
            </li>
          </ul>

        </section>
        <br />

        <!-- ##experience -->
        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <!-- <ion-icon name="book-outline"></ion-icon> -->
              <img src="./assets/images/icons/exp.png" alt="" width="16px" style="-webkit-filter: invert(100%);">
            </div>

            <h3 class="h3">Experience</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Java Intern @iNeuron</h4>

              <span>2023</span>

              <p class="timeline-text">
                During my internship, I gained valuable knowledge and hands-on experience in Java and Spring Boot.
              </p>

            </li>
          </ol>

        </section>

        <!-- ##education -->
        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <!-- <ion-icon name="book-outline"></ion-icon> -->
              <img src="./assets/images/icons/edu.png" alt="" width="20px" style="-webkit-filter: invert(100%);">
            </div>

            <h3 class="h3">Education</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Ellenki Institute of Engineering and Technology [JNTUH]</h4>

              <span>2019 — 2023</span>

              <p class="timeline-text">
                B.Tech <b>Computer Science and Engineering</b>,
                Secured Overall 6.96 CGPA and during projects volunteered to other teams in resolving issues and
                execution.
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Royal Junior College [TSBIE]</h4>

              <span>2017 — 2019</span>

              <p class="timeline-text">
                Secured 64 % in XII-MPC (Board of Intermediate Education Telangana) and received Diploma in C/C++
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Vidya Vikas High School</h4>

              <span>2005 — 2017</span>

              <p class="timeline-text">
                Secured 9.3 CGPA in Matriculation (Board of Secondary Education Telangana) and received a Merit student
                award for being Topper in
                my school.
              </p>

            </li>
          </ol>
        </section>
      </article>

      <!--
        - #PROJECTS / PORTFOLIO
      -->
      <article class="portfolio" data-page="projects">

        <header>
          <h2 class="h2 article-title">Projects</h2>
        </header>

        <section class="projects">

          <ul class="filter-list">

            <li class="filter-item">
              <button class="active" data-filter-btn>All</button>
            </li>

            <!-- <li class="filter-item">
              <button data-filter-btn>Web design</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Applications</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Web development</button>
            </li> -->

          </ul>

          <div class="filter-select-box">

            <button class="filter-select" data-select>

              <div class="select-value" data-selecct-value>Select category</div>

              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>

            </button>

            <ul class="select-list">

              <li class="select-item">
                <button data-select-item>All</button>
              </li>

              <!-- <li class="select-item">
                <button data-select-item>Web design</button>
              </li>

              <li class="select-item">
                <button data-select-item>Applications</button>
              </li>

              <li class="select-item">
                <button data-select-item>Web development</button>
              </li> -->

            </ul>

          </div>

          <ul class="project-list">

            <!-- minor project: blockchain based autonomous decentralized online social network  -->
            <li class="project-item  active" data-filter-item data-category="web development">
              <a
                href="https://github.com/sidduganeshsid/A-Blockchain-Based-Autonomous-Decentralized-Online-Social-Network">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/projects/bcdaosn.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Blockchain Based Decentralized Autonomous Online Social Network.</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <!-- major project: reverse engineered android app -->
            <li class="project-item  active" data-filter-item data-category="web development">
              <a
                href="https://github.com/sidduganeshsid/Malware-Detection-A-Framework-for-Reverse-Engineered-Android-Application">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/projects/malware.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Malware Detection: A framework for Reverse Engineered Android Application.
                </h3>

                <p class="project-category">Machine Learning.</p>
              </a>
            </li>

            <!-- ai fitness integration -->
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/projects/AIFitness.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">AI Fitness recommendations based on BMI + Daily Activity</h3>

                <p class="project-category">AI Integration</p>

              </a>
            </li>

            <!-- vr woods -->
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="https://vrworks.vercel.app/">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/projects/vr.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Freelance: Carpenter Shop Landing Page Responsive</h3>

                <p class="project-category">HTML + CSS + TailwindCSS</p>

              </a>
            </li>

            <!-- Clone: one card -->
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="https://onecard9.vercel.app/">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/projects/OneCard.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Clone: One Card</h3>

                <p class="project-category">HTML + TailwindCSS</p>

              </a>
            </li>

            <!-- todo -->
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="https://todo9.vercel.app/">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/projects/todo.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Todo</h3>

                <p class="project-category">HTML CSS JS: Browser API(Local Storage)</p>
              </a>
            </li>

            <!-- hotel booking -->
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="https://sidduganeshsid.github.io/Hotel-Booking/">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/projects/hotelbooking.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Hotel Booking</h3>

                <p class="project-category">HTML CSS BootStrap (desktop based) </p>
              </a>
            </li>

          </ul>
        </section>

      </article>

      <!--
        - #CONTACT
      -->
      <article class="contact" data-page="contact">

        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>

        <section class="contact-details">
          <p style="color: white;">Email: sidduganeshm@gmail.com</p>
          <hr />
          <br />
        </section>

        <section class="contact-form">

          <h3 class="h3 form-title">Contact Form</h3>

          <form method="POST" id="form" class="form" data-form>
            <div class="input-wrapper">

              <input type="hidden" name="access_key" value="3af23340-512c-4b0f-925e-4e45993c278a">

              <input type="text" required name="fullname" class="form-input" placeholder="Full name" required
                data-form-input>
              <input type="email" name="email" required class="form-input" placeholder="Email address" required
                data-form-input>
            </div>
            <textarea name="message" required class="form-input" placeholder="Your Message" required
              data-form-input></textarea>
            <input type="checkbox" name="botcheck" class="hidden" style="display: none;">

            <button class="form-btn" type="submit" data-form-btn>
              <ion-icon name="paper-plane"></ion-icon>
              <span>Send Message</span>
            </button>

            <div id="result" style="color: yellow;"></div>

          </form>

        </section>

        <section class="mapbox" data-mapbox>
          <figure>
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d30455.395451928238!2d78.27139135221533!3d17.41541384247366!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bcb93552671a95b%3A0xbdbce439cbde81f3!2sVattinagulapalle%2C%20Telangana%20500075!5e0!3m2!1sen!2sin!4v1743091293058!5m2!1sen!2sin"
              width="400" height="300" loading="lazy"></iframe>
          </figure>
        </section>

        <section style="align-items: center; justify-items: center;">

          <p style="color: white; text-align: center;">Visitors Count</p>
          <div style="text-align: center;">
            <a href="https://www.hitwebcounter.com" target="_blank">
              <img src="https://hitwebcounter.com/counter/counter.php?page=9447607&style=0006&nbdigits=5&type=page&initCount=0" 
                   title="Counter Widget" 
                   alt="Visit counter"
                   border="0" />
            </a>
          </div>
          <!-- <p>Visitors Count</p> -->
        </section>

      </article>

    </div>

  </main>





  <!--
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

  <!--
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>

</body>

</html>
