# TASK 1
#Portfolio Website
<!DOCTYPE html>
<html>
<head>
<title> Portfolio Website</title>
<style> 
* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
	-outline: 0;
	font-family Roboto, sans-serif, arial;
}
html, body 
	{
	font-size: 14px;
	font-weight: 400;
	background: navy;
	color: #fff;
}
.container {
	width: 1100px;
	margin: 0px auto;
	display: table;
}
.width-33 {
	width: 33%;
	float: left;
}
.width-66 {
	width: 66%;
	float: left;
}
.main-panel {
	width: 100%;
	float: left;
	padding-top: 20px;
	padding-bottom: 50px;
	height: 100vh;
}

.logo {
	font-size: 40px;
	font-weight: 600;
}

.span-col {
	color: #fff;
}

nav {
	float: right;
}

nav a {
	text-decoration: none;
	font-size: 16px;
	font-weight: 500;
	margin-left: 20px;
	color: white;
}
.width-50 {
	float: left;
	width: 50%;
}
.banner-section {
	width: 100%;
	float: left;
	margin-top: 25vh;
}
.banner-section h1 {
	font-size: 48px;
	margin-top: 10px;
	font-weight: bolder;
}
.banner-section h2 {
	font-size: 20px;
	line-height: 25px;
	margin-top: 10px;
	font-weight: 400;
}
.banner-section a {
	float: left;
	text-decoration: none;
	font-size: 18px;
	margin-top: 20px;
	border-radius: 50%;
	text-align: center;
	border: 2px solid #fff;
	color: #fff;
	margin-left: 10px;
	height: 50px;
	width: 50px;
	line-height: 50px;
}
.main-panel img {
	margin-top: 10%;
	width: 100%;
	margin-left: 10%;
}
.main-section {
	width: 100%;
	float: left;
	padding: 110px 0px 110px 0px;
}
.width-100 {
	width: 100%;
	float: left;
}
.mt-20 {
	margin-top: 20px;
}
.heading-text {
	width: 100%;
	float: left;
	font-size: 35px;
	text-align: center;
	margin-bottom: 50px;
	color: #fff;
}
.about-img {
	width: 100%;
	padding: 0px 50px;
	margin-top: 20px;
}
.about-us {
	width: 100%;
	float: left;
	padding: 20px;
}
.about-us p {
	font-size: 16px;
	margin-top: 15px;
	line-height: 27px;
}
table {
	width: 100%;
}
table th,
table td {
	font-size: 16px;
	text-align: left;
	padding: 5px 0px;
}
.skill {
	margin-top: 30px;
	font-size: 17px;
}

.skill span {
	float: right;
}

.skill div {
	width: 100%;
	float: left;
	margin-top: 5px;
	background: #fff;
	border-radius: 10px;
}

.skill div span {
	background: darkgreen;
	height: 5px;
	float: left;
}

div[role="progressbar"] {
	color: #fff;
	margin-left: 100px;
	margin-bottom: 20px;
	width: 100px;
	;
	height: 100px;
	;
	border-radius: 50%;

	place-items: center;
	display: grid;

	--pgPercentage: var(--value);
	background: radial-gradient(closest-side, black 80%, transparent 0 99.9%, black 0),
		conic-gradient(yellow calc(var(--pgPercentage) * 1%), #fff 0);

}
.bg-lightgrey {
	background-color: #1a1a1a;
}
.service-list {
	padding: 40px;
	margin-top: 35px;
	background: #262626;
	border-radius: 15px;
	width: 94%;
	float: left;
}

.service-list i {
	font-size: 50px;
	color: #ffbf35;
	width: 70px;
	float: left;
}

.service-list h3 {
	font-size: 28px;
	margin-top: 8px;
	margin-bottom: 15px;
}

.service-list p {
	font-size: 15px;
	line-height: 25px;
}
.contact form {
	width: 66%;
	margin: 0px auto;
}
.contact input,
textarea {
	width: 100%;
	float: left;
	margin-bottom: 20px;
	height: 40px;
	padding: 10px;
	border: 1px solid #a1a1a1;
}
.contact textarea {
	height: 80px;
}
.contact button {
	width: 100%;
	float: left;
	margin-bottom: 20px;
	height: 40px;
	padding: 10px;
	background: #fff;
	color: #fff;
	border: none;
	font-size: 16px;
}
.contact h3 {
	font-size: 26px;
	text-align: center;
	margin-top: 60px;
	color: #fff;
}
.contact h4 {
	font-size: 22px;
	text-align: center;
	margin-top: 10px;
}
.contact p {
	text-align: center;
	font-size: 16px;
	margin-top: 5px;
}

.footer {
	background-color: #202020;
	padding: 30px 0px 40px 0px;
	width: 100%;
	float: left;
}
.footer-sect {
	color: #b3b3b3;
}
.footer-sect a {
	color: #b3b3b3;
	margin-left: 10px;
	text-decoration: none;
	font-size: 18px;
	text-align: center;
}
.social-icon a i {
	width: 50px;
	height: 50px;
	border: 1px solid #cdcdcd;
	line-height: 50px;
	font-size: 20px;
	border-radius: 50%;
}
</style>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="css/style.css">
</head>

<body>
<div class="main-panel">
    <div class="container">
      <div class="width-33 logo">Port <span class="span-col">folio</span>
      </div>
      <div class="width-66">
        <nav>
          <a href="#">
            <span class="span-col">Home</span>
          </a>
          <a href="#">About me</a>
          <a href="#">Skills</a>
          <a href="#">My Services</a>
          <a href="#">Contact</a>
        </nav>
      </div>
    </div>
<div class="container ">
    <div class="width-50">
      <div class="banner-section">
        <span class="span-col">Welcome To Protfolio page of</span>
        <h1>Javvaji<span class="span-col"> Mallika</span>
        </h1>
        <h2>- I'm passionate to be a Web Developer .</h2>
        <a href="#">
          <i class="fa fa-facebook"></i>
        </a>
        <a href="#">
          <i class="fa fa-twitter"></i>
        </a>
        <a href="#">
          <i class="fa fa-linkedin"></i>
        </a>
        <a href="#">
          <i class="fa fa-instagram"></i>
        </a>
        <a href="#">
          <i class="fa fa-github"></i>
        </a>
      </div>
    </div>
    <div class="width-50">
      <img src="https://media.istockphoto.com/id/1332378618/photo/close-up-of-a-smart-young-woman-coding.webp?b=1&s=170667a&w=0&k=20&c=5vAWLufWcLP1a6CDjUUqCSBAzMHUBnq-ONJjXhIen2M=">
    </div>
  </div>
  </div>
<div class="main-section bg-lightgrey">
    <div class="container">
      <div class="width-50">
        <img src="https://cdn-media-1.freecodecamp.org/images/TKIz7QINBW86qDpRxZj03KU7DiMWcMW08H25" class="about-img">
      </div>
      <div class="width-50">
        <div class="about-us">
          <h2 class="heading-text">About Me</h2>
          <p>Hi, I am Javvaji Mallika, From India.</p>
          <div class="width-50 mt-20">
            <table cellspacing="8" cellpadding="8">
              <tr>
                <th>Name:</th>
                <td>Javvaji Mallika</td>
              </tr>
              <tr>
                <th>Email:</th>
                <td> javvajimallika1383@gmail.com</td>
              </tr>
              <tr>
                <th>Birthday:</th>
                <td> 13 August, 2003</td>
              </tr>
              <tr>
                <th>Study:</th>
                <td> Osmania University</td>
              </tr>
            </table>
          </div>
          <div class="width-50 mt-20">
            <table cellspacing="8" cellpadding="8">
              <tr>
                <th>Phone:</th>
                <td>9133628186</td>
              </tr>
              <tr>
                <th>City:</th>
                <td>Hyderabad, India</td>
              </tr>
              <tr>
                <th>Freelancer:</th>
                <td> Available</td>
              </tr>
              <tr>
                <th>Website:</th>
                <td> www.portfolio.com</td>
              </tr>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
<div class="main-section">
    <div class="container">
      <h2 class="heading-text">My Skills</h2>
      <div class="width-50">
        <div class="skill">
          <b>HTML</b>
          <span>95%</span>
          <div>
            <span style="width:95%"></span>
          </div>
        </div>
        <div class="skill">
          <b>CSS</b>
          <span>85%</span>
          <div>
            <span style="width:85%"></span>
          </div>
        </div>
        <div class="skill">
          <b>JavaScript</b>
          <span>85%</span>
          <div>
            <span style="width:85%"></span>
          </div>
        </div>
        <div class="skill">
          <b>Python</b>
          <span>79%</span>
          <div>
            <span style="width:79%"></span>
          </div>
        </div>
      </div>
      <div class="width-50">
        <div class="width-50">
          <div role="progressbar" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100" style="--value:95">HTML</div>
        </div>
        <div class="width-50">
          <div role="progressbar" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" style="--value:85">CSS</div>
        </div>
        <div class="width-50">
          <div role="progressbar" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" style="--value:85">JAVASCRIPT</div>
        </div>
        <div class="width-50">
          <div role="progressbar" aria-valuenow="79" aria-valuemin="0" aria-valuemax="100" style="--value:79">PYTHON</div>
        </div>
      </div>
    </div>
  </div>
<div class="main-section">
  <div class="container">
    <h2 class="heading-text">My Service</h2>
    <div class="width-50">
      <div class="service-list">
        <i class="fa fa-chrome"></i>
        <h3>Web Development</h3>
      </div>
    </div>
    <div class="width-50">
      <div class="service-list">
        <i class="fa fa-instagram"></i>
        <h3>Web Design</h3>

      </div>
    </div>
    <div class="width-50">
      <div class="service-list">
        <i class="fa fa-reddit"></i>
        <h3>Creative Design</h3>
      </div>
    </div>
    <div class="width-50">
      <div class="service-list">
        <i class="fa fa-video-camera"></i>
        <h3>Video Editing</h3>
      </div>
    </div>
    <div class="width-50">
      <div class="service-list">
        <i class="fa fa-camera"></i>
        <h3>Photography</h3>
      </div>
    </div>
    <div class="width-50">
      <div class="service-list">
        <i class="fa fa-apple"></i>
        <h3>App Developing</h3>
      </div>
    </div>
  </div>
</div>
<div class="main-section contact bg-lightgrey">
  <div class="container">
    <h2 class="heading-text">Get In Touch</h2>
    <div class="width-100">
      <form>
        <input type="text" placeholder="Full Name...">
        <input type="text" placeholder="Full Email Id...">
        <input type="text" placeholder="Full Mobile No...">
        <input type="submit" value="Submit">
      </form>
    </div>
    <div class="width-33">
      <h3>
        <i class="fa fa-map-marker"></i>
      </h3>
      <h4>Address</h4>
      <p>H. no: 10-1-136,Mankammathota, Karimnagar,Telangana</p>
    </div>
    <div class="width-33">
      <h3>
        <i class="fa fa-phone"></i>
      </h3>
      <h4>Phone</h4>
      <p>+91 9133628186</p>
    </div>
    <div class="width-33">
      <h3>
        <i class="fa fa-envelope-o"></i>
      </h3>
      <h4>Email</h4>
      <p>javvajimallika1383@gmail.com</p>
    </div>
  </div>
</div>
<div class="footer">
  <div class="container">
    <div class="footer-sect social-icon width-50">
      <a href="#">
        <i class="fa fa-facebook"></i>
      </a>
      <a href="#">
        <i class="fa fa-twitter"></i>
      </a>
      <a href="#">
        <i class="fa fa-linkedin"></i>
      </a>
      <a href="#">
        <i class="fa fa-instagram"></i>
      </a>
    </div>
    <div class="footer-sect mt-20 width-50">CopyRight © 2020. All Rights Reserved</div>
  </div>
</div>
  </body>
  </html>
