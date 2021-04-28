# ShapeDemo121.github.io
WEB.DEV BOOTCAMP
<!DOCTYPE HTML>
<head>
<meta charaset="utf-8">
<link href="style.css" rel="stylesheet" type="text/css">
</head>
<body>
<section id="main">
<nav>
<a href="file:///C:/Users/ADITHI/OneDrive/Desktop/index.html" class="logo" ><img src="https://ih1.redbubble.net/image.263045882.6131/flat,750x1000,075,t.u2.jpg" alt="The logo of SRK"></a>
<span class="menu-space"></span>
<ul class="menu">
<li><a href="file:///C:/Users/ADITHI/OneDrive/Desktop/index.html">HOME</a></li>
<li><a href="https://sudarshanpurohit.com/shahrukh-khan-qualities/">SKILLS</a></li>
<li><a href="https://www.filmibeat.com/celebs/shahrukh-khan/upcoming-movies.html">RECENT NEWS</a></li>
<li><a href="https://srscreations.com/shahrukh-khan-all-movies-list/#:~:text=1%20Deewana.%20This%20was%20the%20debut%20movie%20of,is%20the%20Sixth%20Film%20of%20Shahrukh%20Khan.%20">FILMS</a></li>
<li><a href="https://celebritymanagercontact.blogspot.com/2019/09/official-contact-shahrukh-khan-number91.html">CONTACT</a></li>
</ul>
<a href="https://wonderfulmumbai.com/photo-of-mannat-shahrukh-khans-house-at-bandra-mumbai/" class="hey" ><strong>Say Hi!</strong></a>
</nav>
</section>
<div class="content">
<div class="image" >
<img src="https://th.bing.com/th/id/R7ef37459d7a87897e9d8dbf89f6e5da0?rik=sQvdsoY7b8Z9EA&riu=http%3a%2f%2f2.bp.blogspot.com%2f-seSoV0_4kZA%2fUrYQB4W5ZpI%2fAAAAAAAADuM%2ff5UFI4rZZQ8%2fs1600%2fshahrukh-khan2344.jpg&ehk=xObF2Shvb9Gyj9qV9j96%2fx8GCUdlTzOZy0%2bPS8RzLhw%3d&risl=&pid=ImgRaw" alt="SRK" >
</div>
<div class="main-text">
<h1>Hello,I am <br>Shahrukh Khan</h1>
<p>Hey in this video i will be showing you guys how to buld a website using HTML and CSS</p>
<a href="https://www.imdb.com/name/nm0451321/" class="resume-btn">See my Resume</a>
</div>
</body>
</html>


*{
box-sizing:border-box;
}
body{
margin:0px;
padding:0px;
font:poppins;
}
#main{
width:100%;
height:30vh;
position:relative;
}
nav{
display:flex;
justify-content:space-around;
align-items:center;
position:fixed;
top:0;
left:0;
width:100%;
background-color:white;
text-decoration:none;
box-shadow:5px 10px 30px rgba(0,0,0,0.02);
z-index:1;
}
.logo img{
height:100px;
}

.menu{
list-style:none;
display:flex;
}
a{
text-dexoration:none;
}
.menu li a{
height:40px;
line-height:43px;
margin:3px;
padding:0px 22px;
display:flex;
font-size:0.8em;
text-transform:uppercase;
font-weight:500;
letter-spacing:1px;
color:grey;
text-decoration:none;
}
.hey{
color:#39bfbd;
font-weight:500;
font-size:0.9em;
border-bottom:2px solid #39bfbd;
text-decoration:none;
}
image{
width:500px;
height:500px;
}
.image img{
width:100%;
height:100%;
object-fit:contain;
padding:20px;

}
.content{
display:flex;
width:90%;
justify-content:Space-around;
align-items:center;
position:sticky;
left:50%;
right:50%;
tranform:translate(-50%,-50%);
}
.main-text{
width:100%;
}
.main-text h1{
font-size:3.5em;
color:#1c3548;
margin:0px 0px 10px 0px;
line-height:60px;

}
.main-text p{
color:grey
}
.resume-btn{
width:190px;
height:44px;
display:flex;
justify-content:center;
align-items:center;
color:white;
background-color:#1db096;
text-decoration:none;
border-radius:0px 20px;
box-shadow:5px 10px 30px rgba(24,139,119,0.2);
}
.resume-btn:hover{
text-decoration:none;
background-color:#23cdaf;
color:white
transition:all ease0.2s;

}
.menu li a:hover{
background-color:#23cdaf;
color:white;
box-shadow:5px 10px 30px rgba(24,139,119,0.2);
transition:all ease 0.2s;

}


