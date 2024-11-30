# vincentresume<html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device=width, initial-scale=1.0">
        <title>Vincent's Web Resume</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
<style>
  *{
    margin: 0;
    padding: 0;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}
body{
    color: #fff;
}
a {
    text-decoration: none;
color: white;
}
.content{
    padding: 10px 10%;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}
nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}
nav ul li a{
    color: white;
    text-decoration: none;
    font-size: 18px;
    position: relative;
}
nav ul li a::after{
    content: '';
    width: 0;
    height: 3px;
    background: linear-gradient(110deg, #405de6, #f32626, #ffdc80);
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s;
}
nav ul li a:hover::after{
    width: 100%;
}
#header{
    width: 100%;
    height: 100vh;
    background-image: url(Vincent-Zyrell-image.png);
    background-size: cover;
    background-position: center;
}
.header-text{
    margin-top: 20%;
    font-size: 20px;
}
.header-text h1{
    margin-top: 20px;
    font-size: 30px;
    display: inline-block;
}
mark{
    padding: 4px 10px;
    background-image: linear-gradient(110deg, #405de6, #f32626, #ffdc80);
    color: #fff;
}

#about{
background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 35%, rgba(0,212,255,1) 100%);
    padding: 80px 0;
    color: white;
}
.row{
    display: flex;
    justify-content: space space-between;
    flex-wrap: wrap;
}
.about-col-1{
    flex-basis: 35%;
}
.about-col-1 img{
    border-radius: 15px;
}
.about-col-2{
    flex-basis: 60%;
}
.sub-title{
    font-size: 40px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    color: gold;
}
.paragraph{
    line-height: 35px;
}
.about-col-2 p{
    font-family: Arial, Helvetica, sans-serif;
}
.tab-names{
    display: flex;
    margin: 20px 0 40px;
}
#contact{
background: radial-gradient(circle, rgba(63,94,251,1) 0%, rgba(252,70,107,1) 100%);
}
.tab-links{
    margin-right: 50px;
    font-size: 20px;
    font-weight: 500;
    cursor: pointer;
    position: relative;
}
.tab-links::after{
    content: '';
    width: 0;
    height: 3px;
    background: aqua;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}
.tab-links.act-link::after{
    width: 100%;
}
.tab-info ul li{
    list-style: none;
    margin: 10px 0;
}
.tab-info ul li span{
    color: aqua;
    font-size: 14px;
}
.tab-info{
    display: none;
}
.tab-info.act-info{
    display: block;
}
.contact-info{
    flex-basis: 35%;
}
.social-icon a{
    margin-right: 15px;
    display: inline-block;
    transition: transform 0.5s;
}
.social-icon a:hover{
    color: aqua;
    transform: translateY(-5px);
}
#about span{
font-size: 30px;
}
.secret{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100px;
}
.btn{
    width: 150%;
    height: 50px;
    border-radius: 8px;
    background: maroon;
    color: white;
    transition-duration: 0.8s;
}
.btn:hover{
    background: linear-gradient(110deg, #405de6, #f32626, #ffdc80); 
    color: white;
}
.copyright{
    width: 100%;
    text-align: center;
    padding: 25px 0;
    background: navy;
    font-weight: 300;
}
</style>
    </head>
    <body>
        <div id="header">
            <div class="content">
                <nav>
                    <a href="https://youtu.be/uHgt8giw1LY?si=Aq8ljZ7U8nuxsumk"><h1>Web Resume</h1></a>
                    <ul>
                        <li><a href="#header">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </nav>
                <div class="header-text">
                    <h1 style="font-size: 50px;"><mark>Vincent Zyrell</mark></h1><br> 
		<h1 style="font-size: 50px;"><mark>Dela Cruz</mark></h1><br>
		<h1 style="font-size: 35px;">Web Developer</h1><br>
                </div>
            </div>

        </div>

        <div id="about">
            <div class="content">
                <div class="row">
                    <div class="about-col-1">
                        <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0"><img src="Dela Cruz, Vincent Zyrell 11_STEM 11 (1).jpg" width="300" height="300">
                            </a>
                    </div>
                    <div class="about-col-2">
                        <p class ="paragraph" style="font-size: 20px;">Passionate web developer with an experience in developing designing websites.
			Has basic knowledge in HTML, CSS, and JS.
			Willing to seek an opportunity to work with the company to further develop technical skills 
			and experience in web development, specifically in frontend and backend.</p>
                    </div>
                </div>
                <div class="tab-names">
                    <p class="tab-links act-link" onclick="opentab('education')">Education</p>
                    <p class="tab-links" onclick="opentab('skills')">Skills</p>
                    <p class="tab-links" onclick="opentab('experiences')">Experience</p>
			<p class="tab-links" onclick="opentab('certificates')">Certificates</p>
			<p class="tab-links" onclick="opentab('languages')">Languages</p>
                </div> 
                <div class="tab-info act-info" id="education">
                    <ul>
                        <li><span><b>Elementary</b></span><br>Bethany College of Science and Arts (2011-2016)<br><br></li>
                        <li><span><b>Junior High School</b></span><br>New Era University (2016-2017)<br>Nyongani School (2017-2018)<br>
                        Golden Lamp School of Quezon City (2018-2021)<br><br></li>
                        <li><span><b>Senior High School</b></span><br>New Era University (2021-2023)<br><br></li>
                        <li><span><b>College</b></span><br>New Era University (BS Information Technology 2023-present)<br><br></li>
                    </ul>
                </div>
                <div class="tab-info" id="skills">
                    <ul>
                        <li><span><b>Technical Skills</b></span><br><br>HTML/CSS/JavaScript<br> <img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>
			UI/UX Design (FIgma)<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>Java<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>
                            PHP<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>DB2/MySQL<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>
			Software Development Life Cycle (SDLC)<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br><br></li>
                        <li><span><b>Soft Skills</b></span><br><br>Teamwork<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>
			Empathy<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>
			Leadership<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>
                            Critical Thinking<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br>Time Management<br><img src="star.png" style="width: 40px;"><img src="star.png" style="width: 40px;"><br><br></li>
                    </ul>
                </div>
                <div class="tab-info" id="experiences">
                    <ul>
                        <li><span><b>Tourism System Website</b></span><br>
	<h3>New Era University (2024)</h3>
	In charge of developing and designing a tourism website for a web development project.
	<br><br></li>
			<li><span><b>Hotel Booking Web Design</b></span><br>
	<h3>New Era University (2024)</h3>
	One of the members who synergistically design a hotel booking website using Figma for a Human Computer Interaction project.
	<br><br></li>
			</ul>
                </div>
                <div class="tab-info" id="certificates">
                    <ul>
                        <li><span><b>SQL and Relational Databases 101</b></span><br>
<h3>Cognitive Class</h3>
(2024)
<br><br></li>
			</ul>
                </div>
<div class="tab-info" id="languages">
                    <ul>
                        <li>
<h3>English (American)</h3><br>
<h3>Filipino</h3>
<br><br></li>
			</ul>
                </div>
            </div>
        </div>

        <script>
            var tab_links = document.getElementsByClassName("tab-links");
            var tab_infos = document.getElementsByClassName("tab-info");

            function opentab(tab_name){
                for(tab_link of tab_links){
                    tab_link.classList.remove("act-link");
                }
                for(tab_info of tab_infos){
                    tab_info.classList.remove("act-info");
                }
                event.currentTarget.classList.add("act-link");
                document.getElementById(tab_name).classList.add("act-info");
            }
        </script>

        <div id="contact">
            <div class="content">
                <div class="row">
                    <div class="contact-info">
    <h1 class="sub-title">Contact Information</h1><br>
    <p><i class="fas fa-envelope" style="font-size:25px;"></i> vincent.delacruz@neu.edu.ph</p><br>
    <p><i class="fas fa-phone" style="font-size: 25px;"></i> +63 9123456789</p><br>
    <div class="social-icon">
        <a href="https://www.linkedin.com/in/vincent-zyrell-dela-cruz-a46b4a28b" target="_blank">
            <i class="fab fa-linkedin" style="font-size:42px;"></i>
        </a>
        <a href="https://www.facebook.com/vincentzyrell.delacruz.3" target="_blank">
            <i class="fab fa-facebook" style="font-size:42px;"></i>
        </a>
    </div>
</div>

                </div>
            </div>
            <div class="secret">
                <a href="https://youtu.be/uHgt8giw1LY?si=Aq8ljZ7U8nuxsumk"><button class="btn">Click this if you want</button></a>
            </div>
            <div class="copyright">
                <p>© 2024 Dela Cruz, Vincent Zyrell (2BSIT-3). All rights reserved</p>
            </div>
        </div>

    </body>
</html>
