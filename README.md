<?php 
session_start();
if(!isset($_SESSION["nombre"])){
	header('Location:principal_esss.html');
}
?>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="shortcut icon" href="../../assets/ico/favicon.ico">

    <title>Happy Life-Juegos Para Ni&#241os</title>

    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom styles for this template -->
    <link href="css/jumbotron.css" rel="stylesheet">
  <style type="text/css">
 
    </style>

    <!-- Just for debugging purposes. Don't actually copy this line! -->
    <!--[if lt IE 9]><script src="../../assets/js/ie8-responsive-file-warning.js"></script><![endif]-->

    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
  <script type="text/javascript">
function MM_preloadImages() { //v3.0
  var d=document; if(d.images){ if(!d.MM_p) d.MM_p=new Array();
    var i,j=d.MM_p.length,a=MM_preloadImages.arguments; for(i=0; i<a.length; i++)
    if (a[i].indexOf("#")!=0){ d.MM_p[j]=new Image; d.MM_p[j++].src=a[i];}}
}
function MM_swapImgRestore() { //v3.0
  var i,x,a=document.MM_sr; for(i=0;a&&i<a.length&&(x=a[i])&&x.oSrc;i++) x.src=x.oSrc;
}
function MM_findObj(n, d) { //v4.01
  var p,i,x;  if(!d) d=document; if((p=n.indexOf("?"))>0&&parent.frames.length) {
    d=parent.frames[n.substring(p+1)].document; n=n.substring(0,p);}
  if(!(x=d[n])&&d.all) x=d.all[n]; for (i=0;!x&&i<d.forms.length;i++) x=d.forms[i][n];
  for(i=0;!x&&d.layers&&i<d.layers.length;i++) x=MM_findObj(n,d.layers[i].document);
  if(!x && d.getElementById) x=d.getElementById(n); return x;
}

function MM_swapImage() { //v3.0
  var i,j=0,x,a=MM_swapImage.arguments; document.MM_sr=new Array; for(i=0;i<(a.length-2);i+=3)
   if ((x=MM_findObj(a[i]))!=null){document.MM_sr[j++]=x; if(!x.oSrc) x.oSrc=x.src; x.src=a[i+2];}
}
  </script>
</head>

  <body background="imgs/nubes.jpg" onLoad="MM_preloadImages('imgs/flora2.png')">

  <div class="navbar navbar-inverse navbar-fixed-top" role="navigation">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">   Happy Life </a>
          <div class="navbar-collapse collapse">
          <form class="navbar-form navbar-right" role="form">
            <div class="tooltip-inner">Bienvenido(a)    
                    <?php echo $_SESSION["nombre"]; ?></div>
                 <div class="form-group">
                

</div>
        

           
             <a href="logout.php" type="submit" class="btn btn-success">Cerrar sesi&oacute;n</a>
          
               
             <a href="modificar.php" type="submit" class="badge">Modificar Datos</a>
          
            
        </div>
          <!--/.navbar-collapse -->
      </div>
    </div><!--/.navbar-collapse -->
  </div>
    </div>

    <div align="center">
      <!-- Main jumbotron for a primary marketing message or call to action -->
    </div>
    <div>
      <div align="center">
        <p>&nbsp;</p>
        <p>&nbsp;</p>
        <p>&nbsp;</p>
        <p></p>
        <p><img src="imgs/happy-life-logo.png" class="img-responsive" ></p>
        <p>&nbsp;</p>
      </div>
  </div>

    <div class="container"><strong></strong>
      <!-- Example row of columns -->
      <div class="row">
        <div class="col-md-4">
          <h2 align="center"><a href="#" onMouseOut="MM_swapImgRestore()" onMouseOver="MM_swapImage('Image2','','imgs/flora2.png',1)"><img src="imgs/flora.png" width="165" height="163" id="Image2"></a></h2>
          <p align="center" class="h3">Flora Piano</p>
          <p align="center"><a class="btn btn-default" href="#" role="button">Jugar&raquo;</a></p>
        </div>
        <div class="col-md-4">
          <h2 align="center">Juego 2</h2>
          <p align="center">Juego Juego</p>
          <p align="center"><a class="btn btn-default" href="#" role="button">Jugar&raquo;</a></p>
       </div>
        <div class="col-md-4">
          <h2 align="center">Juego 3</h2>
          <p align="center">juego juego</p>
          <p align="center"><a class="btn btn-default" href="#" role="button">Jugar&raquo;</a></p>
        </div>
      </div>

      <hr>
      <a class="btn btn-default" href="#" role="button">Mapa del sitio&raquo;</a>

      <footer>
        <p align="center">&copy; <strong>Happy Life Company all rights reserved 2014</strong>   </p>
        <p align="center">Designed by JG</p>
      </footer>
      
  </div> <!-- /container -->


    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="js/jquery-1.10.2.min.js"></script>
    <script src="js/bootstrap.js"></script>
</body>
</html>
