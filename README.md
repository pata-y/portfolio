<link rel="stylesheet" href="styles.css"/>
<link rel="stylesheet" href="mojeprojekty.css"/>
<link rel="stylesheet" href="informacja.css"/>


<!DOCTYPE html>
<html lang="pl">
<head>
  <style>
  body {  height: 100%;margin: 0;
      
      background-image: url("https://images.pexels.com/photos/925743/pexels-photo-925743.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2");
      height: 100%;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
     
    }
  </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Patay</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
    <link href="/path/to/css/font-awesome.css" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="/path/to/css/bootstrap-social.css" />
    <link href="/path/to/css/font-awesome.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="icon" href="images/favicon.ico" type="image/x-icon">
</head>

<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">
      Patay
      <img src="images/favicon.ico" alt="">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="/portfolio.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/Moje projekty.html">Moje projekty</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/Informacja.html">O mnie</a>
        </li>
      </ul>
    </div>
    <form class="form-inline">
      <input class="form-control mr-sm-2" type="search" placeholder="Szukaj" aria-label="Search">
      <p></p>
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Szukaj</button>
    </form>
  
  

          <ul class="navbar-nav sm-icons">
            <li><a class="nav-link" target="_blank" href="https://www.facebook.com/"><i class="bi bi-facebook"></i></a></li>
            <li><a class="nav-link" target="_blank" href="https://www.instagram.com/"><i class="bi bi-instagram"></i></a></li>
            <li><a class="nav-link" target="_blank" href="https://www.youtube.com/@nenikita3022"><i class="bi bi-youtube"></i></a></li>
          </ul>
        </div>
      </nav>

    <header>
        <div class="header-center">
          <strong>
            
          <p style="font-size: x-large; font: bold; font-style: italic; color: dimgrey;">Cześć, </p> 
          <p style="font-size: x-large; font: bold; font-style: italic; color: dimgrey;">nazywam się Nikita,</p> 
          <p style="font-size: x-large; font: bold; font-style: italic; color: dimgrey;">poszukuję siebie</p>

        </strong>

        </div>
        
    </header>

    <div class="container">
      <form action="action_page.php">
    
        <label for="fname">Imię</label>
        <input type="text" id="fname" name="firstname" placeholder="Twoje imie">
    
        <label for="lname">Nazwisko</label>
        <input type="text" id="lname" name="lastname" placeholder="Twoje nazwisko">
    
        <label for="country">Kraj</label>
        <select id="country" name="country">
          <option value="poland">Polska</option>
          <option value="belarus">Białoruś</option>
          <option value="ukraine">Ukraina</option>
          <option value="czech republic">Czechy</option>
          <option value="germany">Niemcy</option>
          <option value="lithuania">Litwa</option>
          <option value="latvia">Łotwa</option>
          <option value="another">Inny kraj</option>
        </select>
    
        <label for="subject">Temat</label>
        <textarea id="subject" name="subject" placeholder="Napisz..." style="height:200px"></textarea>
    
        <input type="submit" value="Wyślij">
    
      </form>
    </div>

    

    <script src="script.js"></script>

</body>
</html>
