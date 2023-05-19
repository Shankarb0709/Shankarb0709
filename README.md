
<h1 align="center">Hi 👋, I'm L. Bhavani Shankar Prasad</h1>
<h3 align="center">A passionate Learner looking forward to excel in web development.</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=shankarb0709&label=Profile%20views&color=0e75b6&style=flat" alt="shankarb0709" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=shankarb0709" alt="shankarb0709" /></a> </p>

- 🔭 I’m currently working on **URL Shortener**

- 🌱 I’m currently learning **Python**

- 👯 I’m looking to collaborate on **Python Projects**

- 💬 Ask me about **Electrical & Electronic**

- 📫 How to reach me **bhavanishankarr2003@gmail.com**

- ⚡ Fun fact **I am Lazy**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=shankarb0709&show_icons=true&locale=en&layout=compact" alt="shankarb0709" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=shankarb0709&show_icons=true&locale=en" alt="shankarb0709" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=shankarb0709&" alt="shankarb0709" /></p>

19-05-23(js)
const left = document.querySelector('.left');
const right = document.querySelector('.right');
const skillsContainer = document.querySelector('.skills container');

left.addEventListener('mouseenter',()=> {skills-container.classlist.add('hover-left')});
right.addEventListener('mouseenter',()=> {skills-container.classlist.add('hover-right')});
(css)
:root{
    --hover-width:70%;
    --min-width:30%
}
body{
    min-height: 200px;
}
.skills-container{
    background-color: bisque;
    position: relative;
    left: 30%;
    right: 30%;
    width: 50%;
    height: 100%;
}
.split{
    position: absolute;
    width: 50%;
    height: 100;
}

.split.left{
    background-color: red;
}
.split.right{
    background-color: rgb(187, 127, 255);
    right: 5%;
}
.split.left:hover{
    color: #d4d0d0;
}
.split.right:hover{
    color: royalblue;
}
.split.right,
.split.left,
.split.right::before,
.split.left::before{
    transition: all 3sec;
}
.hover-left .right{
    width: var(--min-width);
}
.hover-left .left{
    width: var(--hover-width);
}
.hover-right .right{
    width: var(--hover-width);
}
.hover-right .left{
    width: var(--min-width);
}
