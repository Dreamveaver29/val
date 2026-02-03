<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Be My Valentine ❤️</title>

<style>
*{ box-sizing:border-box; }

body{
  margin:0;
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  font-family:Arial, sans-serif;
  overflow:hidden;

  background:url("bg1.jpeg") center/cover no-repeat;
  transition:background 1s ease-in-out;
}

body.yes-bg{
  background:url("bg2.jpeg") center/cover no-repeat;
}

.container{
  text-align:center;
  padding:20px;
  width:100%;
  max-width:420px;
}

/* TEXT */
h1{
  font-size:clamp(22px,6vw,32px);
  color:#ff2e63;
  margin-bottom:16px;
  text-shadow:0 4px 10px rgba(0,0,0,0.3);
}

h2{
  font-size:clamp(16px,4.5vw,22px);
  margin-top:16px;
}

.love-text{
  color:#ff2e63;
  font-weight:600;
}

/* BUTTONS */
button{
  width:80%;
  max-width:280px;
  font-size:clamp(18px,5vw,22px);
  padding:14px;
  margin:12px auto;
  border:none;
  border-radius:40px;
  cursor:pointer;
}

#yes{
  background:#ff2e63;
  color:white;
}

#no{
  background:#333;
  color:white;
  position:absolute;
  bottom:18%;
}

/* POPUP IMAGE */
.popup-img{
  width:70vw;
  max-width:260px;
  border-radius:20px;
  box-shadow:0 15px 35px rgba(0,0,0,0.4);
  animation:pop 0.6s ease forwards;
}

/* HEARTS */
.heart{
  position:absolute;
  font-size:20px;
  animation:fall 4s linear forwards;
}

@keyframes fall{
  from{transform:translateY(-80px);}
  to{transform:translateY(110vh);}
}

@keyframes pop{
  from{transform:scale(0.4); opacity:0;}
  to{transform:scale(1); opacity:1;}
}

/* SMALL PHONES */
@media (max-height: 650px){
  #no{ bottom:12%; }
}
</style>
</head>

<body>

<div class="container">
  <h1>Will you be my Catwoman? ❤️</h1>
  <button id="yes">YES 💖</button>
  <button id="no">NO 😜</button>
</div>

<audio id="music" src="music.mp3" loop></audio>

<script>
const noBtn = document.getElementById("no");
const yesBtn = document.getElementById("yes");
const music = document.getElementById("music");

/* NO button runs away */
function move(){
  noBtn.style.left = Math.random()*(window.innerWidth-120)+"px";
  noBtn.style.top  = Math.random()*(window.innerHeight-80)+"px";
}
noBtn.addEventListener("touchstart", move);
noBtn.addEventListener("mouseover", move);

/* HEART RAIN */
const heartInterval = setInterval(()=>{
  const h=document.createElement("div");
  h.className="heart";
  h.innerHTML="💖";
  h.style.left=Math.random()*100+"vw";
  document.body.appendChild(h);
  setTimeout(()=>h.remove(),4000);
},350);

/* YES CLICK */
yesBtn.onclick = () => {

  /* 💓 HEARTBEAT HAPTIC */
  if (navigator.vibrate) {
    navigator.vibrate([80, 40, 80, 40, 120]);
  }

  document.body.classList.add("yes-bg");
  music.play();
  clearInterval(heartInterval);

  document.querySelector(".container").innerHTML = `
    <h1>Yayyy ❤️</h1>
    <img src="popup.jpeg" class="popup-img">
    <h2 class="love-text">I knew babe 🥰</h2>
  `;
};
</script>

</body>
</html>
