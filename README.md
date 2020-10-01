# Portfolio Website By Pranayk Gupta

This is a portfolio website about my journey throughout the 4 wonderful years in college and even beyond as I start on the path of a software developer <br>
This website is hosted at https://pranaykgupta.github.io/Portfolio/

## Technology used : HTML , CSS and Javascript

## Usage

Just Clone this repositry in your PC or Laptop or Download this project in your PC

# Sample Code

```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Pranay Gupta</title>
    <link rel="icon" href="./img/me.jpeg">
    <link href="https://fonts.googleapis.com/css?family=Lato&display=swap" rel="stylesheet">
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
      integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u"
      crossorigin="anonymous"
    />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.7.2/css/all.css"
      integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr"
      crossorigin="anonymous"
    />
    <link
      href="https://fonts.googleapis.com/css?family=Lato:400,700"
      rel="stylesheet"
    />
    <!-- github calendar -->
    <script
      src="https://unpkg.com/github-calendar@latest/dist/github-calendar.min.js">
    </script>

    <!-- Optionally, include the theme (if you don't want to struggle to write the CSS) -->
    <link
      rel="stylesheet"
      href="https://unpkg.com/github-calendar@latest/dist/github-calendar-responsive.css"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="cover">
      <nav class="navbar navbar-default snav navbar-fixed-top">
        <div class="container">
          <div class="navbar-header">
            <button
              type="button"
              class="navbar-toggle collapsed"
              data-toggle="collapse"
              data-target="#bs-nav-demo"
              aria-expanded="false"
              style="border-color: #eee; background-color: #eee"
            >
              <span class="sr-only">Toggle navigation</span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
            </button>
            <a href="#" class="navbar-brand"><img src="./img/logo.png"/></a>
          </div>
          <div class="collapse navbar-collapse" id="bs-nav-demo">
            <ul class="nav navbar-nav">
              <li><a href="#about">About</a></li>
              <li><a href="#project">Projects</a></li>
              <li><a href="#skills">My Skills</a></li>
              <li><a href="#con">Contacts</a></li>
            </ul>
          </div>
        </div>
      </nav>

      <div class="header__text-box">
        <h1 class="heading-primary">
          <span class="heading-primary--main">Pranay</span>
          <div
            class=" typewrite"
            data-type='[ "Hi, I am Pranay Kumar Gupta.", "I am a Full Stack Web Developer.","And a blockchain enthusiast."]'
          >
            <span class="wrap"></span>
          </div>
        </h1>
        <a href="#about" class="btn btn--white btn--animated">Discover More</a>
      </div>
    </div>
    <div class="about" id="about">
      <div class="contain">
        <i class="fas fa-tv about-icon"></i>
        <h3 class="about-head">About Me</h3>
        <hr />
        <p class="about-p">
          <img src="./img/me.jpeg" alt="ME" class="me">
        </p>
        <div class="contact-icon">
          <a href="https://www.facebook.com/pranay.gupta.7311"
            ><i class="fab fa-facebook-f mine"></i
          ></a>
          <a href="https://github.com/pranaykgupta"
            ><i class="fab fa-github mine"></i
          ></a>
          <a href="https://www.linkedin.com/in/pranay-kumar-gupta-57b57116a/"
            ><i class="fab fa-linkedin mine"></i
          ></a>
          <a href="https://www.instagram.com/pranaykgupta/"
            ><i class="fab fa-instagram mine"></i
          ></a>
        </div>
      </div>
    </div>

    <div class="projects" id="project">
      <div class="work">
        <h2>My Projects</h2>
        <p>
          What have I built?
        </p>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-xs-12 col-sm-6 col-lg-3 box-sp">
            <div class="thumbnail">
              <img
                src="./img/payment.jpeg"
              />
              <div class="caption">
                <h3>Fee Payment Portal</h3>
                <p>
                  An online portal to make fee payment easier for the students of IIT Patna.
                </p>
              </div>
            </div>
          </div>
          <div class="col-xs-12 col-sm-6 col-lg-3 box-sp">
            <div class="thumbnail">
              <img
                src="./img/saar.jpeg"
              />

              <div class="caption">
                <h3><a href="https://github.com/SAAR-IITP/SAAR-IITP">SAAR-IITP</a></h3>
                <p>
                  An web app used to connect all the alumnus of IIT Patna.
                </p>
              </div>
            </div>
          </div>
          <div class="col-xs-12 col-sm-6 col-lg-3 box-sp">
            <div class="thumbnail">
              <img
                src="./img/chain.jpg"
              />

              <div class="caption">
                <h3><a href="https://github.com/delhi-chain">Delhi-chain</a></h3>
                <p>
                  A blockchain application.
                </p>
              </div>
            </div>
          </div>
          <div class="col-xs-12 col-sm-6 col-lg-3 box-sp">
            <div class="thumbnail">
              <img
                src="./img/sahaayak.jpg" style="height: 200px;"
              />

              <div class="caption">
                <h3><a href="https://github.com/dsciitpatna/sahaayak">Sahaayak</a></h3>
                <p>
                  Sahaayak is a platform for the talented vendors and people who all are willing to work but not getting a right platform or chance to convert their passion and talent into their scalable profession.
                </p>
              </div>
            </div>
          </div>
          <div class="col-xs-12 col-sm-6 col-lg-3 box-sp">
            <div class="thumbnail">
              <img
                src="./img/saar.jpeg"
              />

              <div class="caption">
                <h3><a href="https://github.com/SAAR-IITP/SAAR-Server">SAAR Server</a></h3>
                <p>
                  Api's base for SAAR-IITP web and app.
                </p>
              </div>
            </div>
          </div>
          <div class="col-xs-12 col-sm-6 col-lg-3 box-sp">
            <div class="thumbnail">
              <a href="https://tedxiitpatna.com/">
              <img
                src="./img/tedx1.png"
                style="width: 100%;"
              />
            </a>
              <div class="caption">
                <h3><a href="https://github.com/VatsalSin/TedxIITPatna">TEDx IIT Patna</a></h3>
                <p>
                  Official website for TEDx IIT Patna.
                </p>
              </div>
            </div>
          </div>
          <div class="col-xs-12 col-sm-6 col-lg-3 box-sp">
            <div class="thumbnail">
              <img
                src="./img/anwesha.jpeg"
              />
              <div class="caption">
                <h3><a href="https://github.com/anweshaiitp/anwesha2k20">Anwesha 2k20</a></h3>
                <p>
                  Website for the Cultural-Techno-Management fest of IIT Patna.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="content" id="skills"></div>
    <div class="calendar projects">
      <!-- Loading stuff -->
      Loading the data just for you.
    </div>
    <div class="footer">
      <div class="contact-details" id="con">
        <p>All right reserved Pranay Kumar Gupta @ 2020</p>
        <a href="mailto:pranaykgupta21@iitp.ac.in" class="mine-2"
          ><i class="fas fa-envelope"></i>pranaykgupta21@gmail.com</a
        >

        <!-- <a href="tel:+919354008441" class="mine-2"
          ><i class="fas fa-phone "></i>+91-9354008441</a
        > -->
        <hr />
      </div>
    </div>
    <script
      src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
      integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
      crossorigin="anonymous"
    ></script>
    <script>
      $(function() {
        $(document).scroll(function() {
          var $nav = $(".navbar-fixed-top");
          $nav.toggleClass("scrolled", $(this).scrollTop() > $nav.height());
        });
      });
    </script>
    <script
      src="https://code.jquery.com/jquery-3.3.1.min.js"
      integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
      crossorigin="anonymous"
    ></script>
    <script
      src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"
      integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa"
      crossorigin="anonymous"
    ></script>
    <script src="./script.js"></script>
    <script src="./skill.js"></script>
    <script>
      GitHubCalendar(".calendar", "pranaykgupta");
      // or enable responsive functionality:
      // GitHubCalendar(".calendar", "pranaykgupta", { responsive: true });
  </script>
  </body>
</html>
```

For detailed explanation, visite [How To](https://code.visualstudio.com/docs/editor/github)

```bash
$ git@github.com:viraldevpb/pranaykgupta.github.io.git
```

## Questions or Suggestions

Feel free to create issues [here](https://github.com/pranaykgupta/pranaykgupta.github.io/issues)

## [Try it](https://github.com/pranaykgupta/pranaykgupta.github.io)

## [Follow me on Instagram for daily coding posts](https://www.instagram.com/pranaykgupta/)
