<!DOCTYPE html>
<html>
<head>
<title>Happy Birthday Nitya ❤️</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body{
  margin:0;
  padding:0;
  background:black;
  color:white;
  font-family: 'Segoe UI', sans-serif;
  text-align:center;
}

h1{
  margin-top:40px;
  font-size:38px;
  color:#ff4da6;
}

p{
  width:85%;
  margin:auto;
  font-size:18px;
  line-height:28px;
}

.gallery{
  margin-top:40px;
}

.gallery img{
  width:260px;
  height:320px;
  object-fit:cover;
  border-radius:20px;
  margin:15px;
  box-shadow:0 0 25px #ff4da6;
  transition:0.4s;
}

.gallery img:hover{
  transform:scale(1.05);
}

button{
  padding:15px 30px;
  margin-top:30px;
  background:#ff4da6;
  border:none;
  color:white;
  font-size:18px;
  border-radius:30px;
  cursor:pointer;
}

#hidden{
  display:none;
  margin-top:30px;
  font-size:22px;
  color:#ff99cc;
}

.heart{
  position:fixed;
  color:red;
  font-size:20px;
  animation:float 6s linear infinite;
}

@keyframes float{
  0%{transform:translateY(100vh); opacity:1;}
  100%{transform:translateY(-10vh); opacity:0;}
}
</style>
</head>

<body>

<h1>Happy Birthday My Love, Nitya ❤️</h1>

<p>
Nitya, you are not just my girlfriend, you are my best friend, my safe place,
and the most beautiful part of my life. Our journey started in class 11,
when we were just school kids who never imagined this bond would grow so deep.

From sharing notes in school to sharing dreams about our future,
from silly fights to emotional talks, we have grown together in every way.
And on 6th March, we complete 3 beautiful years of being "US".

Thank you for loving me, supporting me, and standing beside me always.
You are my today, my tomorrow, and my forever.

Happy Birthday to the most special girl in my life.
I love you more than words can ever explain. ❤️
</p>

<h2 style="margin-top:40px;color:#ff66b2;">Our Beautiful Memories 💕</h2>

<div class="gallery">
  <img src="Index/Snapchat-1661872312.jpg">
  <img src="Index/Snapchat-87786379.jpg">
  <img src="Index/Snapchat-467039550.jpg">
  <img src="Index/Snapchat-233024200.jpg">
</div>

<button onclick="showMessage()">Click Here My Love 💖</button>

<div id="hidden">
✨ 3 Years of Togetherness…  
And Forever To Go With You ✨  
I Love You So Much Nitya ❤️
</div>

<script>
function showMessage(){
  document.getElementById("hidden").style.display="block";
}

function createHeart(){
  const heart=document.createElement("div");
  heart.className="heart";
  heart.innerHTML="❤️";
  heart.style.left=Math.random()*100+"vw";
  heart.style.animationDuration=(Math.random()*3+3)+"s";
  document.body.appendChild(heart);
  setTimeout(()=>{heart.remove();},6000);
}
setInterval(createHeart,300);
</script>

</body>
</html>
