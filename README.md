# My Portfolio 
This is my portfolio .
Deployee link==> https://md-arif-java-backend-dev.netlify.app/
# About

My name is Mohammad Arif. I am complete my B.Tech in 2021 from MDU Rohtak ,Haryana.
A Passionate aspiring Java Full Stack Developer skilled in Java 
Backend, moulded and shaped by Masai school’s intensive and 
immersive learning.  Look forward to joining a company where 
I will  be able to contribute towards individual and company growth.



## Features

- Clean, Simple and Modern UI Design.
- Uses No CSS or JavaScript Frameworks or libraries as dependencies.
- Built with only HTML, CSS and a bit of JavaScript 🔨.
- Well Organized Documentation.
- Keyboard support.
- Fully Responsive.
- Loads fast ⚡.



### Header

```html
<header class="header" role="banner" id="top">
    <div class="row">
      <nav class="nav" role="navigation">
        <ul class="nav__items">
          <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
          <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
          <li class="nav__item">
            <a href="#about" class="nav__link">About</a>
          </li>
          <li class="nav__item">
            <a href="#contact" class="nav__link">Contact</a>
          </li>
        </ul>
      </nav>
    </div>
    <div class="header__text-box row">
      <div class="header__text">
        <div id="md1">
        <img src="https://media-exp1.licdn.com/dms/image/C4D03AQFZsATo0VLQAg/profile-displayphoto-shrink_800_800/0/1642845201803?e=1658966400&v=beta&t=etjLIEpyQmwa_Z3DszQ-FdlSnVgfWAL6JhkSh-j7d94" style= "width: 200px " />
      </div>
        <h1 class="heading-primary">
          <!-- Replace the following name with your name -->
          <span>Mohammad Arif</span>
        </h1>
        <!-- Put a small paragraph about yourself -->
        <p>Java Backend Developer at Masai School Banglore</p>
        <a href="#contact" class="btn btn--pink">Get in touch</a>
      </div>
    </div>
```

### Work Section

Each div with class `work__box` represents a project, replace the contents of the all the tags with the information of your projects.

```html
<div class="work__box">
    <div class="work__text">
   <h3>Bella Vita Organic Website Clone</h3>
              <p>
                E-comerce website to buy organic product for  skin and hair.
              </p>
    <ul class="work__list">
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Advance JS</li>
              </ul>

              <div class="work__links">
                <a href="https://darling-malabi-cb1632.netlify.app" target="_blank" class="link__text">
                  Visit Site <span>&rarr;</span>
                </a>
                <a href="https://github.com/Sranjan4321/Bella-Vita-Organic" title="View Source Code" target="_blank">
                  <img src="./images/github.svg" class="work__code" alt="GitHub">
                </a>
              </div>
            </div>
            <div class="work__image-box">
              <img src="https://miro.medium.com/max/875/0*vFyEB_j2zbU1BkEw.jpeg" class="work__image" alt="Project 1" />
            </div>
          </div>
   
</div>
```


### Skills Section


```html
<section class="skill" id="skills">
      <div class="row">
        <h2>Skills</h2>

        <div class="skill__logos">
          <!-- Add logos of the clients or companies you'have worked with. -->
          <img src="https://logos-download.com/wp-content/uploads/2016/10/Java_logo.png" class="skill__logo" alt="Company 2" />
          <img src="https://atomrace.com/blog/wp-content/uploads/2018/05/spring-boot-logo.png" class="skill__logo" alt="Company 3" />
          <img src="https://th.bing.com/th/id/R.0e73e8357fecb4ae0301a1bb471f70f4?rik=JKSFq%2brGiTAyJA&riu=http%3a%2f%2fwww.oscarblancarteblog.com%2fwp-content%2fuploads%2f2014%2f09%2fHibernate-logo1-e1429932456458.png&ehk=4oM5U5v790BrqgW96%2bf1eC%2frDcrMV1LypKa74N3a9%2fY%3d&risl=&pid=ImgRaw&r=0" class="skill__logo" alt="Company 1" />
          <img src="https://logos-download.com/wp-content/uploads/2017/07/HTML5_badge.png" class="skill__logo" alt="Company 3" />
          <img src="https://th.bing.com/th/id/OIP.pXrq6xy_Gxua3qTfGZLXqwHaKc?pid=ImgDet&rs=1" class="skill__logo" alt="Company 1" />
          <img src="https://th.bing.com/th/id/R.b4cc9b6dc76bcc06f3d83656720ebde7?rik=005Zzc3fI4jWEw&riu=http%3a%2f%2fpluspng.com%2fimg-png%2flogo-javascript-png-js-logo-png-512.png&ehk=buIL9ARDqRF2NH%2fhTDw3bko77gSWRCCGP8eY%2fUO4eKc%3d&risl=&pid=ImgRaw&r=0" class="skill__logo" alt="Company 1" />
        </div>
      </div>
    </section>
```

### About Section

<section class="about" id="about">
      <div class="row">
        <h2>About Me</h2>
        <div class="about__content">
          <div class="about__text">
            <!-- Replace the below paragraph with info about yourself -->
            <p>
              A Passionate aspiring Java Full Stack Developer skilled in Java 
              Backend, moulded and shaped by Masai school’s intensive and 
              immersive learning.  Look forward to joining a company where 
              I will  be able to contribute towards individual and company growth.


            </p>
            <!-- Provide a link to your resume -->
            <a href="https://drive.google.com/file/d/1pTSOrLxS4nANY4wolY78rHE41yAcEBtu/view?usp=sharing" class="btn">My Resume</a>
          </div>

          <div class="about__photo-container">
            <!-- Add a nice photo of yourself -->
            <img class="about__photo" src="https://media-exp1.licdn.com/dms/image/C4D03AQFZsATo0VLQAg/profile-displayphoto-shrink_800_800/0/1642845201803?e=1658966400&v=beta&t=etjLIEpyQmwa_Z3DszQ-FdlSnVgfWAL6JhkSh-j7d94" style= "width: 200px " alt="" />
          </div>
        </div>
      </div>
    </section>
```

### Contact Section

<section class="contact" id="contact">
    <div class="row">
      <h2>Get in Touch</h2>
      <div class="contact__info">
        <p>
          Are you looking for a fast-performing and user-friendly website to
          represent your product or business? or looking for any kind of
          consultation? or want to ask questions? or have some advice for me
          or just want to say "Hi 👋" in any case feel free to Let me know. I
          will do my best to respond back. 😊 The quickest way to reach out to
          me is via an email and Phone call.
        </p>
        <!-- Replace the email with yours -->
        <a href="md970824@gmail.com" class="btn">md970824@gmail.com</a><br><br>
        <a href="" class="btn">+91-7988354623</a>
      </div>
    </div>
  </section>
```

### Footer

<footer role="contentinfo" class="footer">
    <div class="row">
      <!-- Update the links to point to your accounts -->
      <ul class="footer__social-links">
        <li class="footer__social-link-item">
          <a href="https://github.com/arif841236" title="Link to Github Profile">
            <img src="./images/github.svg" class="footer__social-image" alt="Github">
          </a>
        </li>
       
        <li class="footer__social-link-item">
          <a href="https://www.linkedin.com/in/arif841236/">
            <img src="./images/linkedin.svg" title="Link to Linkedin Profile" class="footer__social-image" alt="Linkedin">
          </a>
        </li>
      </ul>

        
```
