<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio BTS SIO</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
  <style>
    body {
      background-color: #2c003e;
      color: #fff;
    }

    h1, h2, h3, h4, h5, h6 {
      color: #d4a5ff;
    }

    .navbar {
      background-color: #190027;
    }

    .navbar-brand {
      color: #d4a5ff;
    }

    .nav-link {
      color: #fff;
    }

    #about {
      background-color: #3d004b;
      padding: 50px 0;
    }

    #portfolio {
      background-color: #460061;
      padding: 50px 0;
    }

    #contact {
      background-color: #52006d;
      padding: 50px 0;
    }

    footer {
      background-color: #190027;
      color: #fff;
      padding: 20px 0;
    }
  </style>
</head>
<body>
  <header>
    <nav class="navbar navbar-expand-lg navbar-dark">
      <a class="navbar-brand" href="#">Portfolio BTS SIO</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
        <script>
  particlesJS("particles-js", {
    particles: {
      number: {
        value: 50,
        density: {
          enable: true,
          value_area: 800
        }
      },
      color: {
        value: "#d4a5ff"
      },
      shape: {
        type: "circle",
        stroke: {
          width: 0,
          color: "#000000"
        },
        polygon: {
          nb_sides: 5
        },
        image: {
          src: "img/github.svg",
          width: 100,
          height: 100
        }
      },
      opacity: {
        value: 0.5,
        random: false,
        anim: {
          enable: false,
          speed: 1,
          opacity_min: 0.1,
          sync: false
        }
      },
      size: {
        value: 3,
        random: true,
        anim: {
          enable: false,
          speed: 40,
          size_min: 0.1,
          sync: false
        }
      },
      line_linked: {
        enable: true,
        distance: 150,
        color: "#d4a5ff",
        opacity: 0.4,
        width: 1
      },
      move: {
        enable: true,
        speed: 6,
        direction: "none",
        random: false,
        straight: false,
        out_mode: "out",
        bounce: false,
        attract: {
          enable: false,
          rotateX: 600,
          rotateY: 1200
        }
      }
    },
    interactivity: {
      detect_on: "canvas",
      events: {
        onhover: {
          enable: true,
          mode: "repulse"
        },
        onclick: {
          enable: true,
          mode: "push"
        },
        resize: true
      },
      modes: {
        grab: {
          distance: 400,
          line_linked: {
            opacity: 1
          }
        },
        bubble: {
          distance: 400,
          size: 40,
          duration: 2,
          opacity: 8,
          speed: 3
        },
        repulse: {
          distance: 200
        },
        push: {
          particles_nb: 4
        },
        remove: {
          particles_nb: 2
        }
      }
    },
    retina_detect: true
  });
</script>

        <div id="particles-js"></div>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#about">À propos</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#portfolio">Portfolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <section id="about">
    <div class="container">
      <h2>À propos de moi</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sed posuere nisi, sed volutpat lorem. Phasellus ac neque feugiat, venenatis lacus et, vehicula metus. Duis rutrum euismod risus, in volutpat ligula elementum ut.</p>
    </div>
  </section>

  <section id="portfolio">
    <div class="container">
      <h2>Portfolio</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card mb-4">
            <img src="project1.jpg" class="card-img-top" alt="Projet 1">
            <div class="card-body">
              <h5 class="card-title">Projet 1</h5>
              <p class="card-text">Deion du projet 1.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card mb-4">
            <img src="project2.jpg" class="card-img-top" alt="Projet 2">
            <div class="card-body">
              <h5 class="card-title">Projet 2</h5>
              <p class="card-text">Description du projet 2.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card mb-4">
            <img src="project3.jpg" class="card-img-top" alt="Projet 3">
            <div class="card-body">
              <h5 class="card-title">Projet 3</h5>
              <p class="card-text">Description du projet 3.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact</h2>
      <form>
        <div class="form-group">
          <label for="name">Nom</label>
          <input type="text" class="form-control" id="name" placeholder="Votre nom">
        </div>
        <div class="form-group">
          <label for="email">Email</label>
          <input type="email" class="form-control" id="email" placeholder="Votre email">
        </div>
        <div class="form-group">
          <label for="message">Message</label>
          <textarea class="form-control" id="message" rows="5" placeholder="Votre message"></textarea>
        </div>
        <button type="submit" class="btn btn-light">Envoyer</button>
      </form>
    </div>
  </section>

  <footer>
    <div class="container text-center">
      <p>Portfolio BTS SIO &copy; 2023</p>
    </div>
  </footer>

  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
</body>
</html>
