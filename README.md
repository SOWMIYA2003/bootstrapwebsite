# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### Main page:
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <!-- Add icon library -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<style>
    .fakeimg {
      height: 300px;
     background: plum;
    }
    .img {
      height: 200px;
     background: white;
    }

    .nav-tabs
 {
   border-color:rgb(140, 12, 199);
   width:40%;
 }

.nav-tabs > li a { 
    border: 1px solid #68034f;
    background-color:#d273e6; 
    color:#fff;
    }

.nav-tabs > li.active > a,
.nav-tabs > li.active > a:focus,
.nav-tabs > li.active > a:hover{
    background-color:#D6E6F3;
    color:#000;
    border: 1px solid #b05fe6;
    border-bottom-color: transparent;
    }

.nav-tabs > li > a:hover{
  background-color: #1ab8bb !important;
    border-radius: 5px;
    color:#000;

} 

.tab-pane {
    border:solid 1px #7e3eb9;
    border-top: 0; 
    width:50%;
    background-color:#ededf5;
    padding:7px;

}

.btn:hover {
  background-color: RoyalBlue;
}
    </style>
</head>
<body>
          
          
   <!-- <div class="container">
        <div class="row">
            <div class="col-sm-12 text-center"> 
                <h2>Bootstrap Framework</h2>
            </div>-->
            <div class="p-5 bg-primary text-white text-center">
              <img src="logo.png" align="left" alt="logo" width="180" height="120"> 
                <h1>Bureau of Police Research and Development</h1>
                <h2>Ministry of Home Affairs</h2> 
              </div>
                 

              <nav class="navbar navbar-expand-sm bg-light navbar-light">
                <div class="container-fluid">

                    <button class="btn"><i class="fa fa-twitter" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-youtube-play" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-instagram" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-envelope" style="font-size:36px"></i></button>
                    



                
                    <form class=" d-flex">
                        <input class="form-control me-2" type="text" placeholder="Search" style="width: 500px; height: 40px">
                        <button class="btn btn-primary " type="button" style="width: 200px; height: 40px">Search</button>
                      </form>
                </div>
              </nav>


              <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
                <div class="container-fluid">
                  <a class="navbar-brand" href="#">Home</a>
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="collapsibleNavbar">
                    <ul class="navbar-nav">
                      <!--<li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                      </li>  -->
                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">ABOUT US</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Evolution Of BPRD</a></li>
                          <li><a class="dropdown-item" href="#">Awards/Medals</a></li>
                          <li><a class="dropdown-item" href="#">Work Allocation</a></li>
                          <li><a class="dropdown-item" href="#">Organization</a></li>
                          <li><a class="dropdown-item" href="#">Draft Legistation</a></li>
                          <li><a class="dropdown-item" href="#">Contact Us</a></li>
                          <li><a class="dropdown-item" href="#">Citizens Corner</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Training</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Domestic Courses</a></li>
                          <li><a class="dropdown-item" href="#">Foreign Courses</a></li>
                          <li><a class="dropdown-item" href="#">Training Calender</a></li>
                          <li><a class="dropdown-item" href="#">Miscellaneous</a></li>
                          <li><a class="dropdown-item" href="#">Training Policy</a></li>
                          <li><a class="dropdown-item" href="#">Training Material</a></li>
                          <li><a class="dropdown-item" href="#">Training Division</a></li>
                          <li><a class="dropdown-item" href="#">Training Symposium</a></li>
                          <li><a class="dropdown-item" href="#">CAPT,Bhopal</a></li>
                          <li><a class="dropdown-item" href="#">CDTI</a></li>
                          <li><a class="dropdown-item" href="#">Union Home Minister Trophy</a></li>
                          <li><a class="dropdown-item" href="#">Union Home Minister Training Medal</a></li>
                          <li><a class="dropdown-item" href="#">Publications</a></li>
                          <li><a class="dropdown-item" href="#">Women Safety</a></li>
                          <li><a class="dropdown-item" href="#">Online Courses</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">RESEARCH & CA</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Research</a></li>
                          <li><a class="dropdown-item" href="#">Correctional Admin</a></li>
                          <li><a class="dropdown-item" href="#">All India Prison Duty Meet</a></li>
                          <li><a class="dropdown-item" href="#">Women Safety And Security A Handbook</a></li>
                          <li><a class="dropdown-item" href="#">Model Prison Manual 2016</a></li>
                          <li><a class="dropdown-item" href="#">National Police Research Repository</a></li>
                          <li><a class="dropdown-item" href="#">Interns Talk</a></li>
                          <li><a class="dropdown-item" href="#">SC Questionnaire</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">MODERNIZATION</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">History</a></li>
                          <li><a class="dropdown-item" href="#">Mandate Of Modernization Division</a></li>
                          <li><a class="dropdown-item" href="#">Demonstration/Presentation/Trial</a></li>
                          <li><a class="dropdown-item" href="#">Ongoing Projects</a></li>
                          <li><a class="dropdown-item" href="#">Conference/Seminar/Workshop</a></li>
                          <li><a class="dropdown-item" href="#">Publications/Reports</a></li>
                          <li><a class="dropdown-item" href="#">Yoga At Workplace</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">NPM</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Genesis</a></li>
                          <li><a class="dropdown-item" href="#">Concept And Objectives</a></li>
                          <li><a class="dropdown-item" href="#">Structure</a></li>
                          <li><a class="dropdown-item" href="#">Status Of Projects</a></li>
                          <li><a class="dropdown-item" href="#">Publications of NPM</a></li>
                          <li><a class="dropdown-item" href="#">Model Police Act</a></li>
                          <li><a class="dropdown-item" href="#">National Conference Of Women In Police</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SPD</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Data On Police Organization</a></li>
                          <li><a class="dropdown-item" href="#">Police Book Of BPRandD</a></li>
                          <li><a class="dropdown-item" href="#">Indian Police Journal</a></li>
                          <li><a class="dropdown-item" href="#">Model Police Manual</a></li>
                          <li><a class="dropdown-item" href="#">Police Vigyan</a></li>
                          <li><a class="dropdown-item" href="#">Library</a></li>
                          <li><a class="dropdown-item" href="#">Raj Bhasha</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">ADMIN</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Administration Division</a></li>
                          <li><a class="dropdown-item" href="#">Recruitment Rules</a></li>
                          <li><a class="dropdown-item" href="#">Ongoing Projects</a></li>
                          <li><a class="dropdown-item" href="#">Recruitments</a></li>
                          <li><a class="dropdown-item" href="#">Women Welfare</a></li>
                          <li><a class="dropdown-item" href="#">IPR</a></li>
                          <li><a class="dropdown-item" href="#">Vacancies</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SPC</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Students Police Cadet Programme</a></li>
                          <li><a class="dropdown-item" href="#">SPC Web</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SP CONF. & POLICE EXPO</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Police Expo And 3rd Young SP Conference</a></li>
                          <li><a class="dropdown-item" href="#">Photo Gallery Police Expo 2020</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">GALLERY</a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Photo Gallery</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">PUBLICATIONS/REPORT</a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">PDF</a></li>
                        </ul>
                      </li>

                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">DOPO</a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">PDF</a></li>
                        </ul>
                      </li>
                    </ul>
                  </div>
                </div>
              </nav>
                
              <div class="p-1 my-1 bg-info">
                <div class="container mt-5">
                    <div class="row">
                      <div class="col-sm-4">
                        <img src="dg.jpg" align="left" alt="logo" width="420" height="300">
                        <div class="fakeimg text-center"></div>
                        
                        <h2>Director General</h2>
                        <h3 class="mt-4">Important Links</h3>
                        <ul class="nav nav-pills flex-column">
                          <li class="nav-item">
                            <a class="nav-link bg-dark" href="#" href="SmartPolicing.html">Smart Policing</a>
                          </li>
                          <li class="nav-item">
                            <a class="nav-link bg-warning" href="#">Data On Police Organization</a>
                          </li>
                        </ul>
                        <hr class="d-sm-none">
                      </div>
                      <div class="col-sm-8">
                        <img src="mp.jfif" align="left" alt="logo" width="854" height="300">
                        <div class="fakeimg text-center "></div>
                        <h2 class="mt-5">WHAT'S NEW</h2>
                        <div class="img">
                            <a href="#" class="link-primary">Bureau Darpan</a><br>
                            <a href="#" class="link-danger">Invitation of application for the paid Internship Programme at BPR&D for the year 2022-23</a><br>
                            <a href="#" class="link-primary">Proceedings of the Webinar on Woman Safety with Sensitivity</a><br>
                            <a href="#" class="link-danger">Pandit Govind vallab pant Puraskar Yojana</a><br>
                            <a href="#" class="link-primary">Directory of Prison Officials in India 2021</a><br>
                            <a href="#" class="link-danger">WOMEN SAFETY & SECURITY- A Handbook for First Responders and Investigators in the Police</a><br>
                            <a href="#" class="link-primary">Data on Police Organization</a><br>
                            <a href="#" class="link-danger">Investigative Workflow Manual on Cyber Harassment Cases</a><br>
                        </div>
                        
                    </div>
                  </div>
<div class="container">
                  <!-- Nav tabs -->
<ul class="nav nav-tabs " role="tablist">

    <li class="active"><a href="#prtab" role="tab" data-toggle="tab">Press Release</a></li>
    <li ><a href="#ttab" role="tab" data-toggle="tab">Tenders</a></li>
    <li ><a href="#mgtab" role="tab" data-toggle="tab">Media Gallery</a></li>
    <li ><a href="#intab" role="tab" data-toggle="tab">Important Notes</a></li>
    
  </ul>
  </li>
  
  <!-- Tab panes -->
  <div class="tab-content">
    <div class="tab-pane  active" id="prtab"><a href="#" class="link-primary">Press Release</a><br>
        <a href="#" class="link-primary">Press Release, 51st Foundation Day of BPR&D</a>
        </div>
    <div class="tab-pane " id="ttab">
        <a href="#" class="link-primary">Tender-2020</a>
        <br>
        <a href="#" class="link-primary">Tender-2021</a>
    </div>
    <div class="tab-pane " id="mgtab">
        <a href="#" class="link-primary">Latest Video</a><br>
        <a href="#" class="link-primary">Latest Photo</a>
    </div>
    <div class="tab-pane" id="intab"><a href="#" class="link-primary"></a></div>
    
  </div>
               </div>
<div class="mt-5 p-4 bg-dark text-white">
       
<a href="#" class="link-warning">Sitemap</a>
<a href="#" class="link-info">Accessibility Options</a>
<a href="#" class="link-warning">Privacy Policy</a>
<a href="#" class="link-info">Hyperlinking Policy</a>
<a href="#" class="link-warning">Copyright Policy</a>
<a href="#" class="link-info">Terms and Condition</a>
<a href="#" class="link-warning">Feedback</a>
<a href="#" class="link-info">Other Links</a>
<a href="#" class="link-warning">Archives</a>
<a href="#" class="link-info">RTI</a>
<a href="#" class="link-warning">Tender</a>
<a href="#" class="link-info">Help</a>
<a href="#" class="link-warning">Digital India</a>
<a href="#" class="link-info">my GOV</a>

</div>
</body>
</html>

```
### Data on police organization page:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <!-- Add icon library -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<style></style>
</head>
<body>
    <div class="p-5 bg-primary text-white text-center">
      <img src="logo.png" align="left" alt="logo" width="180" height="120"> 
        <h1>Bureau of Police Research and Development</h1>
        <h2>Ministry of Home Affairs</h2> 
      </div>
         

      <nav class="navbar navbar-expand-sm bg-light navbar-light">
        <div class="container-fluid">

            <button class="btn"><i class="fa fa-twitter" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-youtube-play" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-instagram" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-envelope" style="font-size:36px"></i></button>
            



        
            <form class=" d-flex">
                <input class="form-control me-2" type="text" placeholder="Search" style="width: 500px; height: 40px">
                <button class="btn btn-primary " type="button" style="width: 200px; height: 40px">Search</button>
              </form>
        </div>
      </nav>


      <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Home</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="collapsibleNavbar">
            <ul class="navbar-nav">
              <!--<li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>  -->
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">ABOUT US</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Evolution Of BPRD</a></li>
                  <li><a class="dropdown-item" href="#">Awards/Medals</a></li>
                  <li><a class="dropdown-item" href="#">Work Allocation</a></li>
                  <li><a class="dropdown-item" href="#">Organization</a></li>
                  <li><a class="dropdown-item" href="#">Draft Legistation</a></li>
                  <li><a class="dropdown-item" href="#">Contact Us</a></li>
                  <li><a class="dropdown-item" href="#">Citizens Corner</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Training</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Domestic Courses</a></li>
                  <li><a class="dropdown-item" href="#">Foreign Courses</a></li>
                  <li><a class="dropdown-item" href="#">Training Calender</a></li>
                  <li><a class="dropdown-item" href="#">Miscellaneous</a></li>
                  <li><a class="dropdown-item" href="#">Training Policy</a></li>
                  <li><a class="dropdown-item" href="#">Training Material</a></li>
                  <li><a class="dropdown-item" href="#">Training Division</a></li>
                  <li><a class="dropdown-item" href="#">Training Symposium</a></li>
                  <li><a class="dropdown-item" href="#">CAPT,Bhopal</a></li>
                  <li><a class="dropdown-item" href="#">CDTI</a></li>
                  <li><a class="dropdown-item" href="#">Union Home Minister Trophy</a></li>
                  <li><a class="dropdown-item" href="#">Union Home Minister Training Medal</a></li>
                  <li><a class="dropdown-item" href="#">Publications</a></li>
                  <li><a class="dropdown-item" href="#">Women Safety</a></li>
                  <li><a class="dropdown-item" href="#">Online Courses</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">RESEARCH & CA</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Research</a></li>
                  <li><a class="dropdown-item" href="#">Correctional Admin</a></li>
                  <li><a class="dropdown-item" href="#">All India Prison Duty Meet</a></li>
                  <li><a class="dropdown-item" href="#">Women Safety And Security A Handbook</a></li>
                  <li><a class="dropdown-item" href="#">Model Prison Manual 2016</a></li>
                  <li><a class="dropdown-item" href="#">National Police Research Repository</a></li>
                  <li><a class="dropdown-item" href="#">Interns Talk</a></li>
                  <li><a class="dropdown-item" href="#">SC Questionnaire</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">MODERNIZATION</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">History</a></li>
                  <li><a class="dropdown-item" href="#">Mandate Of Modernization Division</a></li>
                  <li><a class="dropdown-item" href="#">Demonstration/Presentation/Trial</a></li>
                  <li><a class="dropdown-item" href="#">Ongoing Projects</a></li>
                  <li><a class="dropdown-item" href="#">Conference/Seminar/Workshop</a></li>
                  <li><a class="dropdown-item" href="#">Publications/Reports</a></li>
                  <li><a class="dropdown-item" href="#">Yoga At Workplace</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">NPM</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Genesis</a></li>
                  <li><a class="dropdown-item" href="#">Concept And Objectives</a></li>
                  <li><a class="dropdown-item" href="#">Structure</a></li>
                  <li><a class="dropdown-item" href="#">Status Of Projects</a></li>
                  <li><a class="dropdown-item" href="#">Publications of NPM</a></li>
                  <li><a class="dropdown-item" href="#">Model Police Act</a></li>
                  <li><a class="dropdown-item" href="#">National Conference Of Women In Police</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SPD</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Data On Police Organization</a></li>
                  <li><a class="dropdown-item" href="#">Police Book Of BPRandD</a></li>
                  <li><a class="dropdown-item" href="#">Indian Police Journal</a></li>
                  <li><a class="dropdown-item" href="#">Model Police Manual</a></li>
                  <li><a class="dropdown-item" href="#">Police Vigyan</a></li>
                  <li><a class="dropdown-item" href="#">Library</a></li>
                  <li><a class="dropdown-item" href="#">Raj Bhasha</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">ADMIN</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Administration Division</a></li>
                  <li><a class="dropdown-item" href="#">Recruitment Rules</a></li>
                  <li><a class="dropdown-item" href="#">Ongoing Projects</a></li>
                  <li><a class="dropdown-item" href="#">Recruitments</a></li>
                  <li><a class="dropdown-item" href="#">Women Welfare</a></li>
                  <li><a class="dropdown-item" href="#">IPR</a></li>
                  <li><a class="dropdown-item" href="#">Vacancies</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SPC</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Students Police Cadet Programme</a></li>
                  <li><a class="dropdown-item" href="#">SPC Web</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SP CONF. & POLICE EXPO</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Police Expo And 3rd Young SP Conference</a></li>
                  <li><a class="dropdown-item" href="#">Photo Gallery Police Expo 2020</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">GALLERY</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Photo Gallery</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">PUBLICATIONS/REPORT</a>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="#">PDF</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">DOPO</a>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="#">PDF</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <div class="p-1 my-1 bg-info">
        <div class="container mt-5">

            <table class="table">
                <thead>
                  <tr>
                    <th>S.NO</th>
                    <th>TITLE</th>
                    <th>READ MORE</th>
                  </tr>
                </thead>
                <tbody>     
                  <tr class="success">
                    <td>1</td>
                    <td>Data on Police Organization -2020</td>
                    <td><a href="#" class="link-danger">Read More...</a></td>
                  </tr>
                  <tr class="warning">
                    <td>2</td>
                    <td> Data on Police Organization -2019</td>
                    <td><a href="#" class="link-danger">Read More...</a></td>
                  </tr>
                  <tr class="warning">
                    <td>2</td>
                    <td> Data on Police Organization -2018</td>
                    <td><a href="#" class="link-danger">Read More...</a></td>
                  </tr>
                </tbody>
              </table>

<div class="mt-5 p-4 bg-dark text-white">
       
       <a href="#" class="link-warning">Sitemap</a>
       <a href="#" class="link-info">Accessibility Options</a>
       <a href="#" class="link-warning">Privacy Policy</a>
       <a href="#" class="link-info">Hyperlinking Policy</a>
       <a href="#" class="link-warning">Copyright Policy</a>
       <a href="#" class="link-info">Terms and Condition</a>
       <a href="#" class="link-warning">Feedback</a>
       <a href="#" class="link-info">Other Links</a>
       <a href="#" class="link-warning">Archives</a>
       <a href="#" class="link-info">RTI</a>
       <a href="#" class="link-warning">Tender</a>
       <a href="#" class="link-info">Help</a>
       <a href="#" class="link-warning">Digital India</a>
       <a href="#" class="link-info">my GOV</a>
       
       </div>
       </div>
       </div>
       </body>
       </html>

```
### About us (Evolution of BPRD) page:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <!-- Add icon library -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<style></style>
</head>
<body>
    <div class="p-5 bg-primary text-white text-center">
      <img src="logo.png" align="left" alt="logo" width="180" height="120"> 
        <h1>Bureau of Police Research and Development</h1>
        <h2>Ministry of Home Affairs</h2> 
      </div>
         

      <nav class="navbar navbar-expand-sm bg-light navbar-light">
        <div class="container-fluid">

            <button class="btn"><i class="fa fa-twitter" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-youtube-play" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-instagram" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-envelope" style="font-size:36px"></i></button>
            



        
            <form class=" d-flex">
                <input class="form-control me-2" type="text" placeholder="Search" style="width: 500px; height: 40px">
                <button class="btn btn-primary " type="button" style="width: 200px; height: 40px">Search</button>
              </form>
        </div>
      </nav>


      <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Home</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="collapsibleNavbar">
            <ul class="navbar-nav">
              <!--<li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>  -->
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">ABOUT US</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Evolution Of BPRD</a></li>
                  <li><a class="dropdown-item" href="#">Awards/Medals</a></li>
                  <li><a class="dropdown-item" href="#">Work Allocation</a></li>
                  <li><a class="dropdown-item" href="#">Organization</a></li>
                  <li><a class="dropdown-item" href="#">Draft Legistation</a></li>
                  <li><a class="dropdown-item" href="#">Contact Us</a></li>
                  <li><a class="dropdown-item" href="#">Citizens Corner</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Training</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Domestic Courses</a></li>
                  <li><a class="dropdown-item" href="#">Foreign Courses</a></li>
                  <li><a class="dropdown-item" href="#">Training Calender</a></li>
                  <li><a class="dropdown-item" href="#">Miscellaneous</a></li>
                  <li><a class="dropdown-item" href="#">Training Policy</a></li>
                  <li><a class="dropdown-item" href="#">Training Material</a></li>
                  <li><a class="dropdown-item" href="#">Training Division</a></li>
                  <li><a class="dropdown-item" href="#">Training Symposium</a></li>
                  <li><a class="dropdown-item" href="#">CAPT,Bhopal</a></li>
                  <li><a class="dropdown-item" href="#">CDTI</a></li>
                  <li><a class="dropdown-item" href="#">Union Home Minister Trophy</a></li>
                  <li><a class="dropdown-item" href="#">Union Home Minister Training Medal</a></li>
                  <li><a class="dropdown-item" href="#">Publications</a></li>
                  <li><a class="dropdown-item" href="#">Women Safety</a></li>
                  <li><a class="dropdown-item" href="#">Online Courses</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">RESEARCH & CA</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Research</a></li>
                  <li><a class="dropdown-item" href="#">Correctional Admin</a></li>
                  <li><a class="dropdown-item" href="#">All India Prison Duty Meet</a></li>
                  <li><a class="dropdown-item" href="#">Women Safety And Security A Handbook</a></li>
                  <li><a class="dropdown-item" href="#">Model Prison Manual 2016</a></li>
                  <li><a class="dropdown-item" href="#">National Police Research Repository</a></li>
                  <li><a class="dropdown-item" href="#">Interns Talk</a></li>
                  <li><a class="dropdown-item" href="#">SC Questionnaire</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">MODERNIZATION</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">History</a></li>
                  <li><a class="dropdown-item" href="#">Mandate Of Modernization Division</a></li>
                  <li><a class="dropdown-item" href="#">Demonstration/Presentation/Trial</a></li>
                  <li><a class="dropdown-item" href="#">Ongoing Projects</a></li>
                  <li><a class="dropdown-item" href="#">Conference/Seminar/Workshop</a></li>
                  <li><a class="dropdown-item" href="#">Publications/Reports</a></li>
                  <li><a class="dropdown-item" href="#">Yoga At Workplace</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">NPM</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Genesis</a></li>
                  <li><a class="dropdown-item" href="#">Concept And Objectives</a></li>
                  <li><a class="dropdown-item" href="#">Structure</a></li>
                  <li><a class="dropdown-item" href="#">Status Of Projects</a></li>
                  <li><a class="dropdown-item" href="#">Publications of NPM</a></li>
                  <li><a class="dropdown-item" href="#">Model Police Act</a></li>
                  <li><a class="dropdown-item" href="#">National Conference Of Women In Police</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SPD</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Data On Police Organization</a></li>
                  <li><a class="dropdown-item" href="#">Police Book Of BPRandD</a></li>
                  <li><a class="dropdown-item" href="#">Indian Police Journal</a></li>
                  <li><a class="dropdown-item" href="#">Model Police Manual</a></li>
                  <li><a class="dropdown-item" href="#">Police Vigyan</a></li>
                  <li><a class="dropdown-item" href="#">Library</a></li>
                  <li><a class="dropdown-item" href="#">Raj Bhasha</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">ADMIN</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Administration Division</a></li>
                  <li><a class="dropdown-item" href="#">Recruitment Rules</a></li>
                  <li><a class="dropdown-item" href="#">Ongoing Projects</a></li>
                  <li><a class="dropdown-item" href="#">Recruitments</a></li>
                  <li><a class="dropdown-item" href="#">Women Welfare</a></li>
                  <li><a class="dropdown-item" href="#">IPR</a></li>
                  <li><a class="dropdown-item" href="#">Vacancies</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SPC</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Students Police Cadet Programme</a></li>
                  <li><a class="dropdown-item" href="#">SPC Web</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SP CONF. & POLICE EXPO</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Police Expo And 3rd Young SP Conference</a></li>
                  <li><a class="dropdown-item" href="#">Photo Gallery Police Expo 2020</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">GALLERY</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Photo Gallery</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">PUBLICATIONS/REPORT</a>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="#">PDF</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">DOPO</a>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="#">PDF</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <div class="p-1 my-1 bg-info">
        <div class="container mt-5">

            <div class="btn-group">
                <button type="button" class="btn btn-primary">About Us</button>
                <button type="button" class="btn btn-primary">Evolution of BPRD</button>
                <button type="button" class="btn btn-primary">Awards/Medals</button>
                <button type="button" class="btn btn-primary">Work Allocation</button>
                <button type="button" class="btn btn-primary">Organization</button>
                <button type="button" class="btn btn-primary">Draft Legislation</button>
                <button type="button" class="btn btn-primary">Contact Us</button>
                <button type="button" class="btn btn-primary">Citizens Corner</button>
                

              </div>
            
            <h2>Evolution of BPRD</h2><br>
            <h3>CREATION</h3><br>
            <p>1. The Government of India vied Resolution No.8/136/68-P.I (Pers.I) dated 28.08.1970 formally established the Bureau of Police Research and Development (BPR&D), under the Ministry of Home Affairs giving a new orientation to then existing Police Research and Advisory Council (1966) for the following reasons and with the primary objective of modernization of police force:</p><br>

               <p> 1.    To take direct and active interest in the issues<br>
                
                2.    To promote a speedy and systematic study of the police problems,<br>
                
                3.    To apply science and technology in the methods and techniques used by police.<br>
                
                In addition and as a secondary, the Resolution mandated an advisory role also for the Bureau.<br>
                
                <br> <p>2. The Bureau was established with the following two divisions initially with a well laid out charter of duties</p>
                
                <br> 1.    Research, Statistics and Publication
             
                <br> 2.    Development
                
                <br> 3. Training is a vital and growing requirement to improve the competency of police forces in the country. The Gore-Committee (1971) set up by the Government of India studied the training aspects of police and gave several recommendations. The government of India in accepting its recommendations created a Training Division (1973) in addition to the two divisions already existing to function under the Bureau.
                
                <br> 4. The forensic science services uncompromising & Geese under the Development Division grew over a period and a separate Directorate of Forensic Sciences under the BPR&D came into existence in 1983.
                
                <br>  5. Further in 1995 Government of India decided to entrust issues relating to Correctional Administration Work to the BPR&D so that problems relating to prisons and implementation of deemed prison reforms can be taken up by the Bureau in a cohesive manner. This set up is operating out of the existing manpower resources.<br>
                
                6. During the year 2008, the Government of India further decided to create National Police Mission under the administrative control of BPR&D to transform the police forces in the country into effective instrument for maintenance of internal security and facing the challenges in future, by equipping them with the necessary material, intellectual and organizational resources</p>
               </p>
               <h3>SEPARATION</h3><br>
               <p>1.    Though the Institute of Criminology and Forensic Science (ICFS) was established under the overall supervision and guidance of BPR&D as part of the same exercise, it was allowed to function as a separate entity in 1976; since the ultimate objective of setting up the Institute was to develop a full-fledged academic institution for furthering studies in Criminology and forensic science. The same which has been re-christened in the year 1991 is now functioning as Lok Nayak Jai Prakash Narayan (LNJN), National Institute of Criminology and Forensic Science from 1982. The institute provides training courses for officers of the criminal justice system in the two subjects i.e. Criminology and Forensic Science and carries out research.</p>

                <br><p>2.    Growth dynamics took over and the need to specialize in each area arose. The National Police Commission (1977) also recommended certain measures requiring implementation. Simultaneously, technological innovations particularly computers held promises of support to many areas of crime control and crime detection besides processing statistical data for the purpose of analysis. The Government of India, therefore, decided to establish a National Crime Records Bureau in 1986 build another Resolution and entrusted statistics and publications work of the Research Division to the newly constituted Bureau along with the plans for their computerization.</p><br>               
                3.    In an identical move brought about by compulsions of growth, the Government of India decided to give an independent status to the Forensic Science Division by creating a Forensic Science Directorate having an autonomous status under the direct control of the Ministry of Home Affairs.</p>
<div class="mt-5 p-4 bg-dark text-white">
       
       <a href="#" class="link-warning">Sitemap</a>
       <a href="#" class="link-info">Accessibility Options</a>
       <a href="#" class="link-warning">Privacy Policy</a>
       <a href="#" class="link-info">Hyperlinking Policy</a>
       <a href="#" class="link-warning">Copyright Policy</a>
       <a href="#" class="link-info">Terms and Condition</a>
       <a href="#" class="link-warning">Feedback</a>
       <a href="#" class="link-info">Other Links</a>
       <a href="#" class="link-warning">Archives</a>
       <a href="#" class="link-info">RTI</a>
       <a href="#" class="link-warning">Tender</a>
       <a href="#" class="link-info">Help</a>
       <a href="#" class="link-warning">Digital India</a>
       <a href="#" class="link-info">my GOV</a>
       
       </div>
       </div>
       </div>
       </body>
       </html>

```
### Smart policing page:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <!-- Add icon library -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<style></style>
</head>
<body>
    <div class="p-5 bg-primary text-white text-center">
      <img src="logo.png" align="left" alt="logo" width="180" height="120"> 
        <h1>Bureau of Police Research and Development</h1>
        <h2>Ministry of Home Affairs</h2> 
      </div>
         

      <nav class="navbar navbar-expand-sm bg-light navbar-light">
        <div class="container-fluid">

            <button class="btn"><i class="fa fa-twitter" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-youtube-play" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-instagram" style="font-size:36px"></i></button>
            <button class="btn"><i class="fa fa-envelope" style="font-size:36px"></i></button>
            



        
            <form class=" d-flex">
                <input class="form-control me-2" type="text" placeholder="Search" style="width: 500px; height: 40px">
                <button class="btn btn-primary " type="button" style="width: 200px; height: 40px">Search</button>
              </form>
        </div>
      </nav>


      <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Home</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="collapsibleNavbar">
            <ul class="navbar-nav">
              <!--<li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>  -->
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">ABOUT US</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Evolution Of BPRD</a></li>
                  <li><a class="dropdown-item" href="#">Awards/Medals</a></li>
                  <li><a class="dropdown-item" href="#">Work Allocation</a></li>
                  <li><a class="dropdown-item" href="#">Organization</a></li>
                  <li><a class="dropdown-item" href="#">Draft Legistation</a></li>
                  <li><a class="dropdown-item" href="#">Contact Us</a></li>
                  <li><a class="dropdown-item" href="#">Citizens Corner</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Training</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Domestic Courses</a></li>
                  <li><a class="dropdown-item" href="#">Foreign Courses</a></li>
                  <li><a class="dropdown-item" href="#">Training Calender</a></li>
                  <li><a class="dropdown-item" href="#">Miscellaneous</a></li>
                  <li><a class="dropdown-item" href="#">Training Policy</a></li>
                  <li><a class="dropdown-item" href="#">Training Material</a></li>
                  <li><a class="dropdown-item" href="#">Training Division</a></li>
                  <li><a class="dropdown-item" href="#">Training Symposium</a></li>
                  <li><a class="dropdown-item" href="#">CAPT,Bhopal</a></li>
                  <li><a class="dropdown-item" href="#">CDTI</a></li>
                  <li><a class="dropdown-item" href="#">Union Home Minister Trophy</a></li>
                  <li><a class="dropdown-item" href="#">Union Home Minister Training Medal</a></li>
                  <li><a class="dropdown-item" href="#">Publications</a></li>
                  <li><a class="dropdown-item" href="#">Women Safety</a></li>
                  <li><a class="dropdown-item" href="#">Online Courses</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">RESEARCH & CA</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Research</a></li>
                  <li><a class="dropdown-item" href="#">Correctional Admin</a></li>
                  <li><a class="dropdown-item" href="#">All India Prison Duty Meet</a></li>
                  <li><a class="dropdown-item" href="#">Women Safety And Security A Handbook</a></li>
                  <li><a class="dropdown-item" href="#">Model Prison Manual 2016</a></li>
                  <li><a class="dropdown-item" href="#">National Police Research Repository</a></li>
                  <li><a class="dropdown-item" href="#">Interns Talk</a></li>
                  <li><a class="dropdown-item" href="#">SC Questionnaire</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">MODERNIZATION</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">History</a></li>
                  <li><a class="dropdown-item" href="#">Mandate Of Modernization Division</a></li>
                  <li><a class="dropdown-item" href="#">Demonstration/Presentation/Trial</a></li>
                  <li><a class="dropdown-item" href="#">Ongoing Projects</a></li>
                  <li><a class="dropdown-item" href="#">Conference/Seminar/Workshop</a></li>
                  <li><a class="dropdown-item" href="#">Publications/Reports</a></li>
                  <li><a class="dropdown-item" href="#">Yoga At Workplace</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">NPM</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Genesis</a></li>
                  <li><a class="dropdown-item" href="#">Concept And Objectives</a></li>
                  <li><a class="dropdown-item" href="#">Structure</a></li>
                  <li><a class="dropdown-item" href="#">Status Of Projects</a></li>
                  <li><a class="dropdown-item" href="#">Publications of NPM</a></li>
                  <li><a class="dropdown-item" href="#">Model Police Act</a></li>
                  <li><a class="dropdown-item" href="#">National Conference Of Women In Police</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SPD</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Data On Police Organization</a></li>
                  <li><a class="dropdown-item" href="#">Police Book Of BPRandD</a></li>
                  <li><a class="dropdown-item" href="#">Indian Police Journal</a></li>
                  <li><a class="dropdown-item" href="#">Model Police Manual</a></li>
                  <li><a class="dropdown-item" href="#">Police Vigyan</a></li>
                  <li><a class="dropdown-item" href="#">Library</a></li>
                  <li><a class="dropdown-item" href="#">Raj Bhasha</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">ADMIN</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Administration Division</a></li>
                  <li><a class="dropdown-item" href="#">Recruitment Rules</a></li>
                  <li><a class="dropdown-item" href="#">Ongoing Projects</a></li>
                  <li><a class="dropdown-item" href="#">Recruitments</a></li>
                  <li><a class="dropdown-item" href="#">Women Welfare</a></li>
                  <li><a class="dropdown-item" href="#">IPR</a></li>
                  <li><a class="dropdown-item" href="#">Vacancies</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SPC</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Students Police Cadet Programme</a></li>
                  <li><a class="dropdown-item" href="#">SPC Web</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">SP CONF. & POLICE EXPO</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Police Expo And 3rd Young SP Conference</a></li>
                  <li><a class="dropdown-item" href="#">Photo Gallery Police Expo 2020</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">GALLERY</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Photo Gallery</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">PUBLICATIONS/REPORT</a>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="#">PDF</a></li>
                </ul>
              </li>

              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">DOPO</a>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="#">PDF</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <div class="p-1 my-1 bg-info">
        <div class="container mt-5">

            <table class="table">
                <thead>
                  <tr>
                    <th>S.NO</th>
                    <th>TOPIC</th>
                    <th>PDF LINK</th>
                  </tr>
                </thead>
                <tbody>     
                  <tr class="success">
                    <td>1</td>
                    <td>FICCI Compendium of Best Practices in SMART Policing 2017</td>
                    <td><a href="#" class="link-danger">click here</a></td>
                  </tr>
                  <tr class="warning">
                    <td>2</td>
                    <td> FICCI Compendium of Best Practices in SMART Policing 2018</td>
                    <td><a href="#" class="link-danger">click here</a></td>
                  </tr>
                </tbody>
              </table>

<div class="mt-5 p-4 bg-dark text-white">
       
       <a href="#" class="link-warning">Sitemap</a>
       <a href="#" class="link-info">Accessibility Options</a>
       <a href="#" class="link-warning">Privacy Policy</a>
       <a href="#" class="link-info">Hyperlinking Policy</a>
       <a href="#" class="link-warning">Copyright Policy</a>
       <a href="#" class="link-info">Terms and Condition</a>
       <a href="#" class="link-warning">Feedback</a>
       <a href="#" class="link-info">Other Links</a>
       <a href="#" class="link-warning">Archives</a>
       <a href="#" class="link-info">RTI</a>
       <a href="#" class="link-warning">Tender</a>
       <a href="#" class="link-info">Help</a>
       <a href="#" class="link-warning">Digital India</a>
       <a href="#" class="link-info">my GOV</a>
       
       </div>
       </div>
       </div>
       </body>
       </html>

```
## OUTPUT:

### Main page (Home page):
![output](./mainop1.png)
![output](./mainop2.png)

### Data on police organization page:

![output](./dataop.png)

### About us (Evolution of BPRD) page:
![output](./aboutop.png)
![output](./aboutop2.png)

### Smart policing page:
![output](./policeop.png)

### HTML validator output:
### Main page:

![output](./Samplehtmlv.png)
### Data on police organization page:
![output](./dhv.png)
### About us (Evolution of BPRD) page:
![output](./ehv.png)
### Smart policing page:
![output](./sphv.png)


## Result:

A website using bootstrap framework is designed.