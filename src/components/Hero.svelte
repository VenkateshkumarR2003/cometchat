<section class="hero">

  <div class="hero-container">

    <!-- LEFT CONTENT -->
    <div class="hero-left">

      <!-- BADGE -->
      <div class="badge-wrapper">

        <div class="badge-icon">
          <img src="/stars-01.png" alt="icon">
        </div>

        <div class="badge">
          Full Stack AI Agent Platform
        </div>

      </div>

      <!-- HEADING -->
      <h1>
        Ship the <span>agent.</span><br>
        Skip the <span>plumbing.</span>
      </h1>

      <!-- TEXT -->
      <p>
        Why are you still stitching together chat UIs, retries,
        moderation, notifications, and analytics — just to get
        your agent into users' hands?
      </p>

      <p>
        CometChat gives you the entire frontend + infra layer.
        Full stack. Modular. Production-ready.
      </p>

      <!-- BUTTONS -->
      <div class="buttons">
        <button class="demo">Schedule a Demo</button>
        <button class="builder">Try the Agent Builder</button>
      </div>

    </div>

    <!-- RIGHT IMAGE -->
    <div class="hero-right">
      <img src="/agent.png" alt="CometChat AI agent interface preview" class="phone-image" loading="lazy">
    </div>

  </div>

</section>

<style>

/* HERO */

.hero{
  background:#0A0914;
  padding-top:160px;
  padding-bottom:120px;
}

/* CONTAINER */

.hero-container{
  max-width:1200px;
  margin:0 auto;
  padding:0 32px;

  display:flex;
  align-items:flex-start;
  justify-content:space-between;
  gap:80px;
}

/* LEFT SIDE */

.hero-left{
  max-width:528px;
  display:flex;
  flex-direction:column;
  gap:28px;
}

/* BADGE */

.badge-wrapper{
  display:flex;
  align-items:center;
  gap:6px;
}

.badge-icon{
  width:32px;
  height:32px;

  display:flex;
  align-items:center;
  justify-content:center;

  border-radius:50%;
  background:linear-gradient(135deg,#E2DFFF,#7C6CFF);

  overflow:hidden;
}

.badge-icon img{
  width:100%;
  height:100%;
  object-fit:contain;
  transform:scale(1.2);
}

.badge{
  padding:8px 18px;
  font-size:15px;
  font-weight:500;

  border:1px solid rgba(255,255,255,0.25);
  border-radius:50px;

  background:rgba(255,255,255,0.02);

  background-image:linear-gradient(90deg,#E2DFFF,#7C6CFF);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
}

/* HEADING */

h1{
  font-size:60px;
  line-height:1.05;
  letter-spacing:-0.02em;
  margin:0;
  color:white;
}

h1 span{
  background:linear-gradient(90deg,#E2DFFF,#7C6CFF);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
}

/* TEXT */

p{
  color:#9CA0C8;
  font-size:18px;
  line-height:1.6;
  margin:0;
}

/* BUTTONS */

.buttons{
  display:flex;
  gap:12px;
  margin-top:10px;
  flex-wrap:nowrap;
}

button{
  font-size:15px;
  font-weight:600;
  padding:12px 18px;
  border-radius:10px;
  border:none;
  cursor:pointer;
  white-space:nowrap;
}

.demo{
  background:rgba(255,255,255,0.08);
  color:white;
  border:1px solid rgba(255,255,255,0.15);
}

.builder{
  background:linear-gradient(135deg,#7C6CFF,#6B5EFF);
  color:white;
}

/* RIGHT IMAGE */

.hero-right{
  width:575px;
  display:flex;
  justify-content:center;
}

.phone-image{
  width:100%;
  height:auto;
}

/* TABLET */

@media(max-width:1000px){

.hero-container{
  flex-direction:column;
  align-items:flex-start;
  gap:50px;
}

.hero-left{
  max-width:100%;
}

.hero-right{
  width:100%;
  display:flex;
  justify-content:center;
}

}

/* MOBILE */

@media(max-width:600px){

.hero{
  padding-top:120px;
  padding-bottom:80px;
}

.hero-container{
  gap:32px;
}

.hero-left{
  gap:20px;
}

h1{
  font-size:36px;
  line-height:1.15;
}

p{
  font-size:16px;
}

.hero-right{
  width:100%;
}

.phone-image{
  max-width:350px;
}

/* buttons only stack on very small screens */

}



</style>