<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday</title>
  <style>
    body {
      margin: 0;
      background: black;
      overflow: hidden;
    }

    /* Popup nhỏ */
    .popup {
      position: absolute;
      padding: 10px 20px;
      background: #ff4d6d;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      font-weight: bold;
      font-size: 18px;
      color: white;
      border-radius: 10px;
      box-shadow: 0 0 15px pink;
      animation: fadeOut 8s ease forwards;
    }
    @keyframes fadeOut {
      0% { opacity: 1; transform: scale(1);}
      100% { opacity: 0; transform: scale(0.5);}
    }

    /* Dòng nhấn vào đây */
    #startDialog {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: rgba(255, 77, 109, 0.9);
      color: white;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      font-size: 22px;
      padding: 15px 25px;
      border-radius: 15px;
      box-shadow: 0 0 20px pink;
      z-index: 3000;
    }

    /* Thiệp sinh nhật */
    #birthdayCard {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) scaleX(0);
      transform-origin: left center;
      background: #fff0f6;
      border: 3px solid #ff4d6d;
      border-radius: 20px;
      padding: 30px;
      text-align: center;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      color: #d63384;
      font-size: 22px;
      box-shadow: 0 0 20px rgba(255, 0, 100, 0.6);
      z-index: 2000;
      transition: transform 1s ease;
    }
    #birthdayCard.open {
      transform: translate(-50%, -50%) scaleX(1);
    }

    /* Trái tim + chữ */
    #pinkboard { display:none; position:absolute; width:100%; height:100%; }
    #loveText {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 42px;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      color: #ff4d6d;
      text-shadow: 0 0 15px pink;
      z-index: 1500;
      text-align: center;
    }

    /* Nút nhạc */
    #musicBtn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      padding: 8px 16px;
      background: #ff4d6d;
      color: white;
      border: none;
      border-radius: 20px;
      cursor: pointer;
      font-size: 14px;
      display: none;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
      z-index: 2000;
    }
    #musicBtn:hover { background:#ff1a4c; }
  </style>
</head>
<body>
  <!-- Nhạc nền (file mp3 để cùng thư mục với file này) -->
  <audio id="backgroundMusic" src="sinhnhat.mp3" preload="auto" loop muted></audio>
  <button id="musicBtn">⏸ Tắt nhạc</button>

  <!-- Dòng nhấn vào đây -->
  <div id="startDialog">👉 Click vào đây nhaaaa 👈</div>

  <!-- Thiệp sinh nhật -->
  <div id="birthdayCard">
    <h2>🎉 Happy Birthday 🎉</h2>
    <p>Chúc anh iu luôn vui vẻ, hạnh phúc<br>
       Và mãi bên em 💖</p>
  </div>

  <!-- Trái tim đỏ -->
  <canvas id="pinkboard"></canvas>
  <div id="loveText">I love You </div>

<script>
  const messages = ["Happy birthday anh iu 💖"];
  const audio = document.getElementById("backgroundMusic");
  const musicBtn = document.getElementById("musicBtn");
  const birthdayCard = document.getElementById("birthdayCard");
  const pinkboard = document.getElementById("pinkboard");
  const loveText = document.getElementById("loveText");
  const startDialog = document.getElementById("startDialog");

  function createPopup() {
    const popup = document.createElement("div");
    popup.className = "popup";
    popup.textContent = messages[0];
    popup.style.left = Math.random() * (window.innerWidth - 150) + "px";
    popup.style.top = Math.random() * (window.innerHeight - 50) + "px";
    document.body.appendChild(popup);
    setTimeout(() => popup.remove(), 8000);
  }

  function startPopups(count) {
    let created = 0;
    const interval = setInterval(() => {
      if (created >= count) {
        clearInterval(interval);

        // 👉 Sau khi popup chạy xong → hiện thiệp
        setTimeout(() => {
          birthdayCard.style.display = "block";
          setTimeout(() => birthdayCard.classList.add("open"), 100);

          // Sau 5 giây → thiệp biến mất, hiện trái tim
          setTimeout(() => {
            birthdayCard.style.display = "none";
            pinkboard.style.display = "block";
            loveText.style.display = "block";
            startHeart();
          }, 6000);

        }, 1000);
        return;
      }
      createPopup(); created++;
    }, 40);
  }

  // Fullscreen
  function enterFullscreen() {
    const elem = document.documentElement;
    if (elem.requestFullscreen) elem.requestFullscreen();
  }

  // Start khi click lần đầu
  document.addEventListener("click", function startExperience() {
    startDialog.style.display = "none";

    // Bỏ mute và phát nhạc
    audio.muted = false;
    audio.play().then(() => musicBtn.style.display="block")
      .catch(err => console.log("Không phát được nhạc:", err));

    enterFullscreen();
    startPopups(150);
    document.removeEventListener("click", startExperience);
  });

  // Bật/tắt nhạc
  let playing = true;
  musicBtn.addEventListener("click", () => {
    if (playing) {
      audio.pause(); musicBtn.textContent="▶️ Bật nhạc";
    } else {
      audio.play(); musicBtn.textContent="⏸ Tắt nhạc";
    }
    playing = !playing;
  });

  /* --- CODE VẼ TRÁI TIM --- */
  var settings={particles:{length:500,duration:2,velocity:100,effect:-0.75,size:30}};
  var Point=function(x,y){this.x=(x||0);this.y=(y||0);}
  Point.prototype.clone=function(){return new Point(this.x,this.y);}
  Point.prototype.length=function(len){if(len===undefined)return Math.sqrt(this.x*this.x+this.y*this.y);this.normalize();this.x*=len;this.y*=len;return this;}
  Point.prototype.normalize=function(){var l=this.length();this.x/=l;this.y/=l;return this;}
  var Particle=function(){this.position=new Point();this.velocity=new Point();this.acceleration=new Point();this.age=0;}
  Particle.prototype.initialize=function(x,y,dx,dy){this.position.x=x;this.position.y=y;this.velocity.x=dx;this.velocity.y=dy;this.acceleration.x=dx*settings.particles.effect;this.acceleration.y=dy*settings.particles.effect;this.age=0;}
  Particle.prototype.update=function(dt){this.position.x+=this.velocity.x*dt;this.position.y+=this.velocity.y*dt;this.velocity.x+=this.acceleration.x*dt;this.velocity.y+=this.acceleration.y*dt;this.age+=dt;}
  Particle.prototype.draw=function(c,img){function ease(t){return (--t)*t*t+1;}var s=img.width*ease(this.age/settings.particles.duration);c.globalAlpha=1-this.age/settings.particles.duration;c.drawImage(img,this.position.x-s/2,this.position.y-s/2,s,s);}
  var ParticlePool=function(l){var p=new Array(l);for(var i=0;i<l;i++)p[i]=new Particle();var firstActive=0,firstFree=0,duration=settings.particles.duration;
    this.add=function(x,y,dx,dy){p[firstFree].initialize(x,y,dx,dy);firstFree++;if(firstFree==p.length)firstFree=0;if(firstActive==firstFree)firstActive++;if(firstActive==p.length)firstActive=0;}
    this.update=function(dt){var i;if(firstActive<firstFree){for(i=firstActive;i<firstFree;i++)p[i].update(dt);}if(firstFree<firstActive){for(i=firstActive;i<p.length;i++)p[i].update(dt);for(i=0;i<firstFree;i++)p[i].update(dt);}while(p[firstActive].age>=duration&&firstActive!=firstFree){firstActive++;if(firstActive==p.length)firstActive=0;}}
    this.draw=function(c,img){var i;if(firstActive<firstFree){for(i=firstActive;i<firstFree;i++)p[i].draw(c,img);}if(firstFree<firstActive){for(i=firstActive;i<p.length;i++)p[i].draw(c,img);for(i=0;i<firstFree;i++)p[i].draw(c,img);}}
  }
  function startHeart(){
    var canvas=document.getElementById('pinkboard');
    var ctx=canvas.getContext('2d'),particles=new ParticlePool(settings.particles.length),particleRate=settings.particles.length/settings.particles.duration,time;
    function pointOnHeart(t){return new Point(160*Math.pow(Math.sin(t),3),130*Math.cos(t)-50*Math.cos(2*t)-20*Math.cos(3*t)-10*Math.cos(4*t)+25);}
    var image=(function(){var c=document.createElement('canvas'),ctx=c.getContext('2d');c.width=settings.particles.size;c.height=settings.particles.size;
      function to(t){var p=pointOnHeart(t);p.x=settings.particles.size/2+p.x*settings.particles.size/350;p.y=settings.particles.size/2-p.y*settings.particles.size/350;return p;}
      ctx.beginPath();var t=-Math.PI,point=to(t);ctx.moveTo(point.x,point.y);while(t<Math.PI){t+=0.01;point=to(t);ctx.lineTo(point.x,point.y);}ctx.closePath();ctx.fillStyle='#e80c29';ctx.fill();var img=new Image();img.src=c.toDataURL();return img;})();
    function render(){requestAnimationFrame(render);var newTime=new Date().getTime()/1000,dt=newTime-(time||newTime);time=newTime;ctx.clearRect(0,0,canvas.width,canvas.height);var amount=particleRate*dt;for(var i=0;i<amount;i++){var pos=pointOnHeart(Math.PI-2*Math.PI*Math.random());var dir=pos.clone().length(settings.particles.velocity);particles.add(canvas.width/2+pos.x,canvas.height/2-pos.y,dir.x,-dir.y);}particles.update(dt);particles.draw(ctx,image);}
    function onResize(){canvas.width=canvas.clientWidth;canvas.height=canvas.clientHeight;}
    window.onresize=onResize;setTimeout(function(){onResize();render();},10);
  }
</script>
</body>
</html>
