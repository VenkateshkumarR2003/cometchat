<section class="tech">

  <div class="tech-container">

    <div class="network">

      <!-- CONNECTION LINES -->
      <svg class="lines" viewBox="0 0 1200 360">

        <!-- TOP CENTER LINES -->
        <line x1="600" y1="0" x2="600" y2="140"/>

        
        <line x1="610" y1="0" x2="610" y2="140"/>
        <line x1="620" y1="0" x2="620" y2="140"/>

        <!-- LEFT CONNECTIONS -->
        <path d="M200 160 H420 L500 185 H560"/>
        <path d="M200 240 H420 L500 225 H560"/>

        <!-- RIGHT CONNECTIONS -->
        <path d="M640 185 H700 L780 160 H1000"/>
        <path d="M640 225 H700 L780 240 H1000"/>

      </svg>


      <!-- CENTER CHIP -->
      <div class="chip">
        <img src="/Techicon.png" alt="">
      </div>


      <!-- LEFT ICONS -->
      <div class="card left-top">
        <img src="/R-chat.png" alt="">
      </div>

      <div class="card left-bottom">
        <img src="/R-scissor.png" alt="">
      </div>


      <!-- RIGHT ICONS -->
      <div class="card right-top">
        <img src="/L-call.png" alt="">
      </div>

      <div class="card right-bottom">
        <img src="/L-bar.png" alt="">
      </div>

    </div>


    <div class="tech-title">

      <h2>
        Plug in your logic.<br>
        Or build it here.
      </h2>

      <p>
        Two paths. Same full-stack experience.
      </p>

    </div>

  </div>

</section>



<style>

.tech{
  padding:30px 20px;
  color:white;
}

.tech-container{
  max-width:1200px;
  margin:auto;
  text-align:center;
}


/* NETWORK */

.network{
  position:relative;
  height:360px;
  margin-bottom:40px;
}


/* CONNECTION LINES */

.lines{
  position:absolute;
  width:100%;
  height:100%;
  stroke:#ffffff20;
  stroke-width:1.6;
  fill:none;
  top:0;
  left:0;
  z-index:1;
}




/* CENTER CHIP */

.chip{
  position:absolute;

  left:50%;
  top:50%;

  transform:translate(-50%,-50%);

  width:130px;

  z-index:3;

  box-shadow:
  0 0 80px rgba(140,120,255,0.6),
  0 0 160px rgba(140,120,255,0.35);
}

.chip img{
  width:100%;
  display:block;
}


/* ICON CARDS */

.card{

  position:absolute;

  width:64px;
  height:64px;

  background:linear-gradient(145deg,#1a1b2e,#16213e);

  border-radius:14px;

  display:flex;
  align-items:center;
  justify-content:center;

  border:1px solid rgba(140,120,255,0.25);

  box-shadow:
  0 6px 20px rgba(0,0,0,0.35),
  inset 0 1px 0 rgba(255,255,255,0.08);

  z-index:2;

}


.card img{
  width:26px;
  height:26px;
  object-fit:contain;
}



/* POSITIONS */

.left-top{
  left:140px;
  top:140px;
}

.left-bottom{
  left:140px;
  top:240px;
}

.right-top{
  right:140px;
  top:140px;
}

.right-bottom{
  right:140px;
  top:240px;
}



/* TITLE */

.tech-title{
  margin-top:-20px;
}

.tech-title h2{
  font-size:44px;
  font-weight:600;
  line-height:1.2;
  margin:0 0 14px;
}

.tech-title p{
  color:#9EA3B3;
  font-size:16px;
  margin:0;
}



/* TABLET */

@media(max-width:900px){

.network{
  height:320px;
}

.card{
  width:56px;
  height:56px;
}

.card img{
  width:22px;
}

.tech-title h2{
  font-size:32px;
}

.left-top,.left-bottom{
  left:40px;
}

.right-top,.right-bottom{
  right:40px;
}

}



/* MOBILE */

@media(max-width:640px){

.network{
  height:260px;
}

.card{
  width:44px;
  height:44px;
}

.card img{
  width:18px;
}

.chip{
  width:80px;
}

.tech-title h2{
  font-size:26px;
}

.tech-title p{
  font-size:14px;
}

.left-top{
  left:20px;
  top:120px;
}

.left-bottom{
  left:20px;
  top:180px;
}

.right-top{
  right:20px;
  top:120px;
}

.right-bottom{
  right:20px;
  top:180px;
}

}

</style>