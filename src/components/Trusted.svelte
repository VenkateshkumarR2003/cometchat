<section class="trusted">

  <div class="trusted-wrapper">

    <div class="trusted-box">

      <div class="logo-marquee">
        <div class="logo-track">

          <img src="/logos/haleon.png" alt="haleon">
          <img src="/logos/kahoot.png" alt="kahoot">
          <img src="/logos/shaadi.png" alt="shaadi">
          <img src="/logos/endeavor.png" alt="endeavor">
          <img src="/logos/nobroker.png" alt="nobroker">

          <!-- duplicate for seamless loop -->

          <img src="/logos/haleon.png" alt="haleon">
          <img src="/logos/kahoot.png" alt="kahoot">
          <img src="/logos/shaadi.png" alt="shaadi">
          <img src="/logos/endeavor.png" alt="endeavor">
          <img src="/logos/nobroker.png" alt="nobroker">

        </div>
      </div>

    </div>

  </div>

</section>

<style>

.trusted{
  background:#0A0914;
  padding:90px 0;
}

/* container */

.trusted-wrapper{
  max-width:1200px;
  margin:auto;
  padding:0 24px;
}

/* rectangle */

.trusted-box{
  position:relative;
  border-top:1px solid rgba(255,255,255,0.12);
  border-bottom:1px solid rgba(255,255,255,0.12);
  padding:40px 0; /* increased height */
  overflow:hidden;
}

/* side gradient fade */

.trusted-box::before,
.trusted-box::after{
  content:"";
  position:absolute;
  top:0;
  bottom:0;
  width:180px;
  z-index:2;
  pointer-events:none;
}

.trusted-box::before{
  left:0;
  background:linear-gradient(
    to right,
    #0A0914 0%,
    rgba(10,9,20,0.85) 50%,
    transparent
  );
}

.trusted-box::after{
  right:0;
  background:linear-gradient(
    to left,
    #0A0914 0%,
    rgba(10,9,20,0.85) 50%,
    transparent
  );
}

/* marquee */

.logo-marquee{
  overflow:hidden;
}

.logo-track{
  display:flex;
  align-items:center;
  gap:110px;
  width:max-content;
  animation:logoscroll 14s linear infinite; /* faster scroll */
}

/* logos */

.logo-track img{
  height:40px;
  opacity:.7;
  transition:opacity .3s ease;
}

.logo-track img:hover{
  opacity:1;
}

/* animation */

@keyframes logoscroll{

  0%{
    transform:translateX(0);
  }

  100%{
    transform:translateX(-50%);
  }

}

/* tablet */

@media(max-width:768px){

.logo-track{
  gap:60px;
}

.logo-track img{
  height:28px;
}

}

/* mobile */

@media(max-width:480px){

.trusted{
  padding:70px 0;
}

.logo-track{
  gap:40px;
}

.logo-track img{
  height:22px;
}

}

</style>