# Foody
FooD order

<!DOCTYPE html>
<html lang="en">
 
<head>
      <title>Homepage for Restaurant</title>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
    <title>Fooddddie's Kitchen</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet"
          href=
"https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
          integrity=
"sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
          crossorigin="anonymous">
</head>
 
<body>
 
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">
          Fooddddie's Kitchen
          </a>
        <button class="navbar-toggler" type="button"
                data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false"
                aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#about">
                      About
                      </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#reservation">
                      Reservation
                      </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#menu">
                      Menu
                      </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#shop">
                      Shop
                      </a>
                </li>
            </ul>
        </div>
    </nav>
 
    <!-- Hero Section -->
    <section class="hero-section text-center">
        <div class="container">
            <h1 class="display-4 text-white">
              Welcome To Fooddddie's Kitchen
              </h1>
            <p class="lead text-white">
              Explore a world of flavors and 
              indulge in culinary delights.
              </p>
            <a class="btn btn-primary btn-lg" href="#reservations">
              Book a table
              </a>
        </div>
    </section>
 
    <!-- About Section -->
    <section id="about" class="about-section">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <h2 class="section-heading">
                      Why Choose Us?
                      </h2>
                    <p class="text-muted">
                        Discover the extraordinary at Fooddddie's Kitchen. 
                          Our commitment to quality and
                        exceptional service makes us your top choice. 
                          Lorem ipsum dolor sit amet,
                        consectetur adipisicing elit.
                    </p>
                </div>
                <div class="col-lg-6">
                    <img src="image/1.png"
                        class="img-fluid" alt="About Image">
                </div>
            </div>
        </div>
    </section>
 
    <!-- Carousel Section -->
    <section class="carousel-section">
        <div id="carouselExampleControls"
             class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="src=image/2.png"
                         class="d-block w-100"
                         alt="Food Image 1">
                </div>
                <div class="carousel-item">
                    <img src="src=image/3.png"
                         class="d-block w-100"
                         alt="Food Image 2">
                </div>
                <div class="carousel-item">
                    <img src="src=image/4.png"
                         class="d-block w-100"
                         alt="Food Image 3">
                </div>
            </div>
            <a class="carousel-control-prev"
               href="#carouselExampleControls" role="button"
               data-slide="prev">
                <span class="carousel-control-prev-icon"
                      aria-hidden="true">
                  </span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next"
               href="#carouselExampleControls"
               role="button" data-slide="next">
                <span class="carousel-control-next-icon"
                      aria-hidden="true">
                  </span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </section>
 
    <!-- Reservation and Contact Section -->
    <section id="reservations" class="reservation-section">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <h2 class="section-heading">
                      Make a Booking
                      </h2>
                    <form>
                        <div class="form-group">
                            <label for="name">Your Name</label>
                            <input type="text" class="form-control"
                                   id="name" placeholder="Enter your name">
                        </div>
                        <div class="form-group">
                            <label for="phoneNumber">
                              Phone Number
                              </label>
                            <input type="text"
                                   class="form-control" id="phoneNumber"
                                   placeholder="Enter your phone number">
                        </div>
                        <button type="submit" class="btn btn-primary">
                          Submit
                          </button>
                    </form>
                </div>
                <div class="col-lg-6 opening-time">
                    <h2 class="section-heading">Opening Times</h2>
                    <p class="text-muted">
                        <span>Monday—Thursday: 08:00 — 22:00</span><br>
                        <span>Friday—Saturday: 09:00 — 23:00</span><br>
                        <span>Sunday: 10:00 — 17:00</span>
                    </p>
                    <h2 class="section-heading">Contact</h2>
                    <p class="text-muted">
                        <span>410-602-8008</span><br>
                        <span>15 Florida Ave</span><br>
                        <span>Palo-Alto, 1111 CA</span>
                    </p>
                </div>
            </div>
        </div>
    </section>
 
    <!-- Footer Section -->
    <footer class="footer-section text-center">
        <div class="container">
            <p>© 2023 Fooddddie's Kitchen. All rights reserved.</p>
        </div>
    </footer>
 
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
        integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
        integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
        integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
        crossorigin="anonymous"></script>
</body>
 
</html>
