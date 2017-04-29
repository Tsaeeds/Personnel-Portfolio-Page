<!DOCTYPE html>
<header>
<style>
.nav-pills{
  font-family: Monospace;
  font-size: 20px;
  background-color: #6d3491;
  margin-bottom:10%;
  
}
body{
  background-color: white;
  color:white;
}

#name{
  font-family: lobster;
  color: white;
}
.main{
  padding: 0px;
  margin-top:0px;
  font-size: 6.0em;
  font-family: Lobster;
}

.btn-default{
  background-color: black;
  border-color: black;
  color: #337ab7;
  font-size: 1.7em;
}
.pageOne{
  /*background:url("http://img08.deviantart.net/2dec/i/2006/014/9/5/love_beach_high_resolution_by_keyzersoze.jpg");*/
  backgroud-size: cover;
  padding-bottom:5%;
  background-color: #d7cbdb; 
  }
.pageTwo{
  /*background:url("https://www.bhmpics.com/download/blue_mountains_lake_landscape-1920x1200.jpg");*/
  background-size: cover;
  background-color:grey;
  
  padding-top: 5%;
  padding-bottom: 5%;
}
.pageThree{
  /*background:url("http://cdn.wallpapersafari.com/15/10/Rn0adb.jpg");*/
  background-size: cover;
  background-color: #d7cbdb;
   padding-top: 5%;
  padding-bottom: 5%;
}

.pageFour{
  /*background:url("http://cdn.wallpapersafari.com/95/91/hgFCsT.jpg");*/
  background-size: cover;
  background-color:grey;
  font-family: Sans-serif;
  padding-top: 5%;
  padding-bottom: 5%;
}

.block{
  font-family: lobster;
  background-color: grey;
  opacity: 0.7;
  padding: 10px;
  width: 50%;
  margin-left:auto;
  margin-right:auto;
  border-radius: 10px;
  }
.btnList{
  margin-top: 15px;
}


p{
 font-size: 2.2em
}

.me{
  margin-left:100px;
  border-radius: 50%;
}
#faceBookIcon{
  color: rgb(59, 89, 163)
}
#twitterIcon{
  color: rgb(0, 172, 237)
}
#linkedInIcon{
  color: rgb(0, 127, 178)
}
#gitHubIcon{
  color: rgb(102, 43, 129)
}

.portImg{
  width:500px;
  height: 300px;
  margin-left: auto;
  margin-right:auto;
 }

.cont{
  padding-top: 3%;
}
</style>
  <link rel="stylesheet" type="text/css" href="//fonts.googleapis.com/css?family=Lobster" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</header>


<div class="pageOne">
  <ul class="nav nav-pills">
    <li id="name"><a href="#"><font color="white">Tahir Siddiqui</font></a></li>
    <li class="pull-right"><a href="#p4"><font color="white">Contact</font></a></li>
    <li class="pull-right"><a href="#p3"><font color="white">Portfolio</font></a></li>
    <li class="pull-right"><a href="#p2"><font color="white">About</font></a></li>
  </ul>

  <div class="block text-center">
  <h1 class="main">Tahir Siddiqui</h1>
    <h2>Be The Best Version of You<h2>
    </div>
  <div class="btnList text-center">
    <a class="btn btn-default" href="https://www.facebook.com/tahir.siddiqui.92102"><i id="faceBookIcon" class="fa fa-facebook-official fa-lg" aria-hidden="true"></i> FaceBook</a>
    <a class="btn btn-default" href="https://twitter.com/tahirsaeed800"><i id="twitterIcon" class="fa fa-twitter fa-lg" aria-hidden="true"></i> Twitter</a>
    <a class="btn btn-default" href="https://www.linkedin.com/in/tahir-siddiqui-545215a9/"><i id="linkedInIcon" class="fa fa-linkedin-square fa-lg" aria-hidden="true"></i> LinkedIn</a>
    <a class="btn btn-default" href="https://github.com/Tsaeeds"><i id="gitHubIcon" class="fa fa-github fa-lg" aria-hidden="true"></i> GitHub</a>
  </div>
</div>
 <div class="pageTwo" id="p2">
    <div class="row">
      <div class="col-md-6 text-center">
         <h1 class="main"> Tahir Siddiqui</h1>
        <p>Front-End Developer and UX/UI designer, with practical experience in project management, branding strategy, and creative direction; devoted to functional programming and information architecture.</p>
<hr>
        <p>
        Web Developer - User Experience Designer - Graphic Artist
</p>
      </div>
      <div class="col-md-6">
      <img src="https://www.linkedin.com/mpr/mpr/AAEAAQAAAAAAAAhpAAAAJDlmNWI1OWZkLWVjYjktNGVjZi04MDA0LWU3OTc5MTk3OGVjYQ.jpg" class="me">
      </div>
   </div>
 </div>   
    <div class="pageThree text-center" id="p3">
      <hr>
      <h1><font  size="40px" color="grey">Portfolio</font></h1>
      <hr>
      <div class="row">
      <div class="col-md-6 ">
        <img class="portImg" src="http://get1car.com/wallpapers/lamborghini/lamborghini_aventador_high_resolution-widescreen_wallpapers.jpg">
        <hr>
        <img class="portImg" src="http://hdpic.org/wp-content/uploads/2015/03/Tokyo-Awesome-HD-Picture-High-Resolution-Free-Wallpaper.jpg">
      </div>
      <div class="col-md-6">
        <img class="portImg" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT0Hio_u-c7H99BsyrsiL0RQ6s2mlVOaA1_usp3T33oGCJqlcVM4A">
        <hr>
        <img class="portImg" src="http://cdn.wonderfulengineering.com/wp-content/uploads/2014/03/high-resolution-wallpapers-12.jpg">
      </div>
        </div>
      </div>
    
    <div class="pageFour text-center" id="p4">
      <hr>
      <h1><font size="40px">Contact Me</font></h1>
      <hr>
      <div class="cont row">
       <div class="col-md-4">
          <form action="action_page.php">
Name:<br>
<font color="black"><input type="text" name="Name"></font>
<br>
Email Address:<br>
<font color="black"><input type="text" name="email"></font>
<br>
            Phone Number:<br>
<font color="black"><input type="text" name="email"></font>
<br><br>
<button class="btn text-primary">Submit</button>
            
</form>
 </div>
        <div class="col-md-7">
        <p><font size="5px">Want to get in touch with me? Be it to request more info about myself or my experience, to ask for my resume, tips on how to solve your sudoku, random questions about the universe and the meaning of life, or even if only for some nice Fika here in stunning Toronto... just feel free to drop me a line anytime.
          <hr>
I promise to reply A.S.A.P.
Note: No spam/soliciting pour moi, merci :</font></p>
        </div>
          </div>
        <hr>
        <div>
     <a href="https://www.facebook.com/tahir.siddiqui.92102"> <i style="font-size:34px; color: rgb(59, 89, 163)" class="fa">&#xf230;</i></a>
     <a href="https://www.linkedin.com/in/tahir-siddiqui-545215a9/"><i style="font-size:34px; color: rgb(0, 127, 178)" class="fa">&#xf08c;</i></a>
      <a href="https://twitter.com/tahirsaeed800"><i style="font-size:34px; color: rgb(0, 172, 237)" class="fa">&#xf081;</i></a>
      <a href="https://github.com/Tsaeeds"><i style="font-size:34px; color: rgb(102, 43, 129)" class="fa">&#xf09b;</i></a>
          </div>
          
    </div>
    
</html>
