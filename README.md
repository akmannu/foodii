<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="E:\atom\project1\bootstrap1\design.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
link href="https://fonts.googleapis.com/css?family=Russo+One&display=swap" rel="stylesheet">  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
  <style>
  h1{
    padding-left: 20px;
  }
  </style>
</head>
<body>


<div class="container-fluid" style="background-color: #c3761ad1; padding:30px;">
 <nav class="navbar navbar-expand-md  navbar-dark fixed-top" style="background-color:#c16519;">
    <a class="navbar-brand" href="#"><h1 style="font-family: 'Russo One';">foodii.com</h1></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="collapsibleNavbar">
      <ul class="navbar-nav ml-auto"  >


        <li class="nav-item">
          <a class="nav-link active" href="#">HOME</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">MENU</a>
        </li>

        <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
        OUR SERVICES
      </a>
      <div class="dropdown-menu "  style="background-color:#0000b3; color:white;">
        <a class="dropdown-item" href="#">ORDER ONLINE</a>
        <a class="dropdown-item" href="#">OFFERS</a>
        <a class="dropdown-item" href="#">PERMANENT USER</a>
      </div>

    </li>
        <li class="nav-item">
          <a class="nav-link" href="#">NEAR YOU</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">FEEDBACK</a>
        </li>
      </ul>
    </div>
  </nav>

      <br><br><br><br>
      <div class="row">
    <div class=col-lg-6>  <h1><i>Your favorite food is here</i></h1>
              </div>
    <div class=col-lg-6>  <img src="E:\atom\project1\bootstrap1\burger1.jpg" >  </div>
  </div>
  <div class="row">
    <div class=col-lg-6>  <button type="button" class="btn btn-lg" style="background-color:red;">ORDER ONLINE</button></div>
  </div>
</div>
 <div class="container-fluid" style="background-color:grey;">
   <img src="E:\atom\project1\bootstrap1\pizza.jpg">
</div>
</body>
</html>
