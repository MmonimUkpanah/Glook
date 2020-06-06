<template>
    <div class="bg-light">
<nav class="navbar navbar-expand-lg  first">
  <a class="navbar-brand" href="#"><img src="~/assets/title.png" class=" img-responsive"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse second" id="navbarTogglerDemo02">
    <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
      <li class="nav-item">
    <a class="nav-link active" href="#">Home</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Services</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Salons</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">About Us</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Contact Us</a>
  </li>
  <li class="nav-item">
    <button class="btn1">Book Appointment</button>
  </li>
  <li class="nav-item">
    <Button class="btn2">Log in</Button>
  </li>
    </ul>
  </div>
</nav>

    </div>
</template>


<style scoped>
.first{
  margin-left: 200px;

}
.second{
  margin-left: 250px;
}
.btn1{
    color: #ffffff;
    background: #7B1777;
    padding: 10px 15px;
    border: none;
    border-radius: 15px;
}
.btn1:hover{
    color: #7B1777;
    background: #ffffff;
    padding: 10px 15px;
    border: none;
    border-radius: 15px;

}
.btn2{
    color: #7B1777;
    background: #ffffff;
    padding: 10px 15px;
    margin-left: 15px;
     border: none;
    border-radius: 15px;
}
.btn2:hover{
    color: #ffffff;
    background: #7B1777;
    padding: 10px 15px;
    margin-left: 15px;
     border: none;
    border-radius: 15px;
}
a{
    text-decoration: none;
    color: #7B1777;

}
a:hover{
    font-weight: bold;
    
}




@media (min-width: 769px) and (max-width: 1200px){
  .first{
    margin-left: 10px;
  }
  .second{
  margin-left: 200px;
}

}


@media (min-width: 501px) and (max-width: 768px){
  .first{
    margin-left: 10px;
  }
  .second{
  margin-left: 500px;
  }
  .btn1{
  display: none;
}
.btn2{
  display: none;
}


}



@media (min-width:376px) and (max-width: 500px){
  .first{
    margin-left: 10px;
  }
  .second{
  margin-left: 200px;
  }
  .btn1{
  display: none;
}
.btn2{
  display: none;
}
}


@media (max-width: 375px){
  .first{
    margin-left: 10px;
  }
  .second{
  margin-left: 150px;
  }
  .btn1{
  display: none;
}
.btn2{
  display: none;
}
}










</style>