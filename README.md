
  <style>

    /* estilo parar la base del menu */
    .topnav {
      overflow: hidden;
      background-color: BLACK;
    }

    /* Enlaces del menu */
    .topnav a {
      float: left;
      display: block;
      color: RED;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }

    /* Animacion para el menu */
    .topnav a:hover {
      background-color: BLACK;
      color: BLACK
    }

  
    /* Contenido deje de ser flotante */
    .row::after {
      content: "";
      display: table;
      clear: both;
    }

    /* Plantilla responsiva */
    @media screen and (max-width: 600px) {
      .row__column {
        width: 100%;
      }
    }

    /* Pie de pagina */
    .footer {
      background-color: BLACK;
      padding: 30px;
      text-align: center;  
    }
	
	<link rel="stylesheet" type="text/css" href="css/estilo.css" /> 
	
  </style>


<body>
    <!--header section start -->
    <div id="index.html" class="header_section">
        <div class="container">
            <div class="row">
                <div class="col-sm-6 col-lg-3">
                    <div class="logo"><a href="index.html"><img src="images/logo.png"></a></div>
                </div>
                <div class="col-sm-6 col-lg-9">
                    <div class="menu_text">
                        <ul>
                        <li><a href="index.html">INICIO</a></li>                                                    
                        <li><a href="https://wa.me/qr/UECKUOH36TMPB1">CONSULTAR</a></li>
                            <li><a href="https://wa.me/qr/UECKUOH36TMPB1">TAXI</a></li>
                            <li><a href="https://wa.me/qr/UECKUOH36TMPB1">RESERVAR</a></li>
                          
                            <div id="myNav" class="overlay">
                <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
                <div class="overlay-content">
                    <a href="index.html">INICIO</a>
                    <a href="https://wa.me/qr/UECKUOH36TMPB1">CONSULTAR</a>
                    <a href="https://wa.me/qr/UECKUOH36TMPB1">TAXI</a>
                  <a href="https://wa.me/qr/UECKUOH36TMPB1">RESERVAR</a>
                  <a href="https://wa.me/qr/UECKUOH36TMPB1">CONTACTAR</a>
                </div>
                </div>
          <span  style="font-size:33px;cursor:pointer; color: #ffffff;" onclick="openNav()"><img src="images/buscar.png" class="toggle_menu"></span>
              
                        </ul>
                    </div>
            </div>
        </div>
    </div>
    <!-- header section end -->
    <!-- banner section start -->
    <div class="banner_section">
      <div class="container-fluid">
        <div id="main_slider" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <div class="row">
          <div class="col-md-6">
            <div class="book_now">
                <h1 class="book_text">NUMERO TEL:</h1>
                <h1 class="call_text">(+503) 7865-2329</h1>
            </div>
            <div class="image_1"><img src="images/QUTE3.jpeg"></div>
          </div>
          <div class="col-md-6">
              <h1 class="booking_text">RESERVA TU QUTE</h1>
            <div class="contact_bg">
            <div class="input_main">
              <div class="container">
                  <h2 class="request_text">VIVE UNA GRAN EXPERIENCIA</h2>
                <form action="/action_page.php">
                <div class="form-group">
                  <input type="text" class="email-bt" placeholder="PICKUP" name="Name">
                </div>
                <div class="form-group">
                    <input type="text" class="email-bt" placeholder="QUTE" name="Email">
                </div>
                <div class="form-group">
                    <input type="text" class="email-bt" placeholder="OTROS" name="Email">
                </div>
                  </form>
                  </div> 
                  </div>
    <div class="send_bt"><a href="#">BUSCAR</a></div>
          </div>
          </div>
        </div>
    </div>
    <div class="carousel-item">
      <div class="row">
          <div class="col-md-6">
            <div class="book_now">
                <h1 class="book_text">TAXI CALUCO</h1>
              <h1 class="call_text">EDUARDO FLORES</h1>
            </div>
          <div class="image_1"><img src="images/QUTE2.jpeg"></div>
          </div>
          <div class="col-md-6">
              <h1 class="booking_text">RESERVA TU QUTE</h1>
            <div class="contact_bg">
            <div class="input_main">
              <div class="container">
                  <h2 class="request_text">VIVE LA MEJOR EXPERIENCIA</h2>
                <form action="/action_page.php">
                <div class="form-group">
                  <input type="text" class="email-bt" placeholder="PICKUP" name="Name">
                </div>
                <div class="form-group">
                    <input type="text" class="email-bt" placeholder="QUTE" name="Email">
                </div>
                <div class="form-group">
                    <input type="text" class="email-bt" placeholder="OTRO" name="Email">
                </div>
                  </form>
                  </div> 
                  </div>
    <div class="send_bt"><a href="#">BUSCAR</a></div>
          </div>
          </div>
        </div>
    </div>
    <div class="carousel-item">
      <div class="row">
          <div class="col-md-6">
            <div class="book_now">
                <h1 class="book_text">TAXI CALUCO</h1>
                <h1 class="call_text">EDUARDO FLORS</h1>
            </div>
          <div class="image_1"><img src="images/QUTE.jpeg"></div>
          </div>
          <div class="col-md-6">
              <h1 class="booking_text">RESERVA TU QUTE</h1>
            <div class="contact_bg">
            <div class="input_main">
              <div class="container">
                  <h2 class="request_text">VIAJA RAPIDO Y FELIZ</h2>
                <form action="/action_page.php">
                <div class="form-group">
                  <input type="text" class="email-bt" placeholder="PICKUP" name="Name">
                </div>
                <div class="form-group">
                    <input type="text" class="email-bt" placeholder="QUTE" name="Email">
                </div>
                <div class="form-group">
                    <input type="text" class="email-bt" placeholder="OTRO" name="Email">
                </div>
                  </form>
                  </div> 
                  </div>
    <div class="send_bt"><a href="#">BUSCAR</a></div>
          </div>
          </div>
        </div>
    </div>
  </div>
<video width="400" height="250" controls>
     <source src="3.mp4" type="video/mp4">
       </video>

       <video width="400" height="250" controls>
        <source src="2.mp4" type="video/mp4">
       </video>
       <video width="400" height="250" controls>
       <source src="3.mp4" type="video/mp4">
       </video>

 


    <!-- Javascript files-->
    <script src="js/jquery.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.bundle.min.js"></script>
    <script src="js/jquery-3.0.0.min.js"></script>
    <script src="js/plugin.js"></script>
    <!-- sidebar --1
    <script src="js/jquery.mCustomScrollbar.concat.min.js"></script>
    <script src="js/custom.js"></script>
    <!-- javascript --> 
    <script src="js/owl.carousel.js"></script>
    <script src="https:cdnjs.cloudflare.com/ajax/libs/fancybox/2.1.5/jquery.fancybox.min.js"></script>
    <script>
    $(document).ready(function(){
    $(".fancybox").fancybox({
    openEffect: "none",
    closeEffect: "none"
    });
       
    $(".zoom").hover(function(){
         
    $(this).addClass('transition');
    }, function(){
         
    $(this).removeClass('transition');
    });
    });
    </script> 
    <script>
    function openNav() {
    document.getElementById("myNav").style.width = "100%";
    }
    <BODY BGCOLOR="BLACK">

    function closeNav() {
   document.getElementById("myNav").style.width = "100%";
   }
</script>  
 

