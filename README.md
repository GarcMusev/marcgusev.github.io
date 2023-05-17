# marcgusev.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <link rel="stylesheet" href= "css/style.css">
    <title>Marc Gusev Portfolio</title>
</head>
<body>
  <header>
  <nav class="navbar navbar-expand-lg bg-white">
    <div class="container-fluid bg-white">
      <a class="navbar-brand" href="#">
        <img src="img/logo (1).png" width="50" height="50">
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#about">About me</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              My University Projects
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#University">Single Page Application</a></li>
              <li><a class="dropdown-item" href="#University">Bücher Shop</a></li>
              <li><a class="dropdown-item" href="#University">Dating App Softwarearchitektur</a></li>
            </ul>
          </li>

          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#university" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              My Video Projects
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#Movie">1. Hidden Beauty</a></li>
              <li><a class="dropdown-item" href="#Movie">2. The Anthropocene</a></li>
              <li><a class="dropdown-item" href="#Poorbird Skate">3. Poorbird Skate Park</a></li>
              <li><a class="dropdown-item" href="#Lost Place Calisthenics">4. Lost Place Calisthenics</a></li>
              <li><a class="dropdown-item" href="#University Lunch Sport">5. University Lunch Break</a></li>
              <li><a class="dropdown-item" href="#Jewrovision Motion Graphic">6. Motion Graphic</a></li>
            </ul>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-dark" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  </header>
  
  <div class="background-gradient1">


    <div class="offcanvas offcanvas-size-xl offcanvas-start" data-bs-scroll="true" tabindex="-1" id="offcanvasWithBothOptions" aria-labelledby="offcanvasWithBothOptionsLabel">
      <div class="offcanvas-header">
        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
        <img src="img/LebenslaufOhneFoto.jpg" width="100%" height="auto" alt="Bewerbungsfoto Marc Gusev">
        <a href="link/LebenslaufOhneFoto.pdf.zip" class="btn btn-dark">Download</a>
      </div>
    </div>
  
      <div class="card mb-1 mx-auto bg-transparent" id="about" style="max-width: 600px;">
        <div class="row g-0 ">
          <div class="col-md-0">
            <img class="img-fluid rounded mx-auto d-block" src="img/bewerbungsFoto.PNG" id="bewerbungsfoto"width="50%" height="auto" alt="Bewerbungsfoto Marc Gusev">
          </div>
          <div class="col">
            <div class="card-body mx-auto">
              <h5 class="card-title">Über mich</h5>
              <p class="card-text">"Willkommen auf meiner Website! Ich bin Marc Gusev, ein 22-jähriger Medieninformatik-Student aus Berlin. Neben meinem Studium widme ich mich leidenschaftlich dem Filmemachen und habe eine Vielzahl beeindruckender Projekte in meinem Portfolio gesammelt.</p>
              <button class="btn btn-dark" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasWithBothOptions" aria-controls="offcanvasWithBothOptions">Mein Lebenslauf</button>
            </div>
          </div>
        </div>
      </div>
  

    <h2 class="display-2 text-center text-white" id="University" style="margin-top: 200px; margin-bottom: 100px;">My University Projects</h2>
    <div class="row row-cols-1  row-cols-md-3 g-5"> 
      <div class="col">
        <div class="card bg-transparent h-100">
          <img src="img/Sonnensystem.png" class="card-img-top" alt="Sonnensystem Website">
          <div class="card-body">
            <h5 class="card-title">Sonnensystem Website</h5>
            <p class="card-text">Frontend Webdevelopment with Sass and JavaScript </p>
            <a href="link/Planeten.zip"" target="_blank" class="btn btn-dark">Download</a>
            <p class="card-text"><small class="fst-italic">5 Semester 2023, BHT Berlin</small></p>
          </div>
        </div>
      </div> 
  
    <div class="col">
      <div class="card bg-transparent h-100"">
        <img src="img/YLBD1.png" class="card-img-top" alt="Book Shop">
        <div class="card-body">
          <h5 class="card-title">Your Local Book Dealer - Book Shop</h5>
          <p class="card-text">Book Shop programmed with Python and Django Framework</p>
          <a href="link/BücherShop.zip" target="_blank" class="btn btn-dark">Download</a>
          <p class="card-text"><small class="fst-italic">4 Semester 2022, Berlin</small></p>
        </div>
      </div>
    </div>
  
    <div class="col">
      <div class="card bg-transparent h-100"">
        <img src="img/Dafe.png" class="card-img-top" alt="Poorbird Skate Park">
        <div class="card-body">
          <h5 class="card-title">Dafe - Safe Dating App</h5>
          <p class="card-text">Building a Software Architecture with Star-UML</p>
          <a href="link/" target="_blank" class="btn btn-dark">Download</a>
          <p class="card-text"><small class="fst-italic">4, 5 Semester 2022/23, Berlin</small></p>
        </div>
      </div>
    </div>
  </div>
  
  </div>


  <div class="background-gradient2">

    <h2 class="display-2 text-center text-white" id="Movie"style="margin-top: 200px; margin-bottom: 100px;">My Video Projects</h2>
    
    <div class="row row-cols-1 row-cols-md-2 g-5"> 
      <div class="col">
        <div class="card bg-transparent h-100">
          <img src="img/HiddenBeaty.JPG" class="card-img-top" alt="Hidden Beaty Fashion Brand">
          <div class="card-body">
            <h5 class="card-title">Hidden Beauty</h5>
            <p class="card-text"> Ein Fashion Brand Project für das 4 Semester an der HTW im Studiengang Modedesign. Mai 2022, Berlin</p>
            <a href="https://drive.google.com/file/d/1o1GTN6BI3vxjpErp4Xf6Bkbj5cxqtFhl/view?usp=sharing" target="_blank" class="btn btn-dark">Anschauen</a>
            <p class="card-text"><small class="text-body-secondary">Mai 2022, Berlin</small></p>
          </div>
        </div>
      </div>

  
    <div class="col">
      <div class="card bg-transparent h-100"">
        <img src="img/Anthropocene.png" class="card-img-top" alt="The Anthropocene Fashion Brand">
        <div class="card-body">
          <h5 class="card-title">The Anthropocene</h5>
          <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
          <a href="https://drive.google.com/file/d/1knJ9QgRDYW4yStHX-ZOju0Pd2_zHF1H3/view?usp=sharing" target="_blank" class="btn btn-dark">Anschauen</a>
          <p class="card-text"><small class="text-body-secondary">April 2023, Berlin</small></p>
        </div>
      </div>
    </div>

    <div class="col" id="Poorbird">
      <div class="card bg-transparent h-100"">
        <img src="img/Poorbird.png" class="card-img-top" alt="Poorbird Skate Park">
        <div class="card-body">
          <h5 class="card-title">Poordbird Skate Park</h5>
          <p class="card-text">Skate Video for introducing the new local CLub in Köpenick November 2022, Berlin.</p>
          <a href="https://drive.google.com/file/d/1NecLDjJHBWSPRosicH4X3F4meP4SoGMV/view?usp=share_link" target="_blank" class="btn btn-dark">Anschauen</a>
          <p class="card-text"><small class="text-body-secondary">November 2021, Berlin</small></p>
        </div>
      </div>
    </div>
    
    <div class="col" id="Lost Place Calisthenics">
      <div class="card bg-transparent h-100"">
        <img src="img/LostPlace.png" class="card-img-top"  alt="The ANthropocene Fashion Brand">
        <div class="card-body">
          <h5 class="card-title">Lost Place Calisthenics</h5>
          <p class="card-text">Calisthenics Moves in an old Industrial Hall </p>
          <a href="https://drive.google.com/file/d/1cBfSCzGEa36dDyk2WKxFRrZdRW18ntLr/view?usp=sharing" target="_blank" class="btn btn-dark">Anschauen</a>
          <p class="card-text"><small class="text-body-secondary">Juni 2020, Dortmund</small></p>
        </div>
      </div>
    </div>
    
    <div class="col" id="University Lunch Sport">
      <div class="card bg-transparent h-100" id="preLastElement">
        <img src="img/TUDortmund.png" class="card-img-top"alt="The ANthropocene Fashion Brand">
        <div class="card-body">
          <h5 class="card-title">University Lunch Break</h5>
          <p class="card-text">Random creating a short sportmovie with a student August 2019, Dortmund</p>
          <a href="https://drive.google.com/file/d/1OT4Ot6Lmn7Sz5LgT8xUhRT265H0I0lyu/view?usp=share_link" target="_blank" class="btn btn-dark">Anschauen</a>
          <p class="card-text"><small class="text-body-secondary">Ausgust 2019, Dortmund</small></p>
        </div>
      </div>
    </div>

    <div class="col" id="Jewrovision Motion Graphic">
      <div class="card bg-transparent h-100" id="lastElement">
        <img src="img/EMUNA.png" class="card-img-top" alt="Jewrovision Motion Graphic">
        <div class="card-body">
          <h5 class="card-title">Motion Graphic for Jewrovision Song Contest 2022</h5>
          <p class="card-text">Random creating a short sportmovie with a student August 2019, Dortmund</p>
          <a href="https://drive.google.com/file/d/1KNwPe0hOcfn_y6KMrb4pls1R6YueG0gm/view?usp=share_link" target="_blank" class="btn btn-dark">Anschauen</a>
          <p class="card-text"><small class="text-body-secondary"> Mai 2022, Berlin</small></p>
        </div>
      </div>
    </div>
  </div>

  <footer style="margin-top: 50px;">
    <p>&copy; 2023 Mein Portfolio. Alle Rechte vorbehalten.</p>
  </footer>
 
  
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe" crossorigin="anonymous"></script>

</div>
</body>
</html>
