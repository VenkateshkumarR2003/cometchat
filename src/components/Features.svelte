<section class="features">

  <div class="features-container">

    <!-- LEFT CONTENT -->
    <div class="content">

      <h2>
        <span class="line1">Everything you'd end up</span>
        <span class="gradient line2">already done.</span>
      </h2>

      <ul>

        <li>
          <span class="star">✦</span>
          <p>
            A complete frontend and system layer for AI agents.
            Plug in your LLM backend or build the brain with ours.
          </p>
        </li>

        <li>
          <span class="star">✦</span>
          <p>
            CometChat is the only full stack agent platform that combines
            logic, UI, moderation, notifications, and insights – without glue code.
          </p>
        </li>

        <li>
          <span class="star">✦</span>
          <p>
            Each of these is battle-tested, used and trusted in production by
            real companies, across real user scenarios.
          </p>
        </li>

      </ul>

    </div>


    <!-- RIGHT IMAGE -->
    <div class="image">

      <div class="glow"></div>

      <img src="/feature.png" alt="agent diagram"/>

    </div>

  </div>

</section>


<style>

/* SECTION */

.features{
  padding:60px 32px 120px;
  background:#0A0914;
}


/* CONTAINER */

.features-container{
  max-width:1200px;
  margin:auto;

  display:grid;
  grid-template-columns:1fr 1fr;
  gap:80px;
  align-items:center;
}


/* TITLE */

.content h2{
  font-family:"Satoshi", sans-serif;
  font-size:44px;
  font-weight:600;
  line-height:1.2;
  margin-bottom:28px;
}

/* FORCE PERFECT LINE BREAK */

.line1,
.line2{
  display:block;
}


/* GRADIENT TEXT */

.gradient{
  background:linear-gradient(
    90deg,
    #9B8CFF,
    #C4B5FD,
    #B8A9FF,
    #8B7CFF
  );

  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
}


/* LIST */

.content ul{
  list-style:none;
  padding:0;
  margin:0;

  display:flex;
  flex-direction:column;
  gap:20px;

  max-width:520px;
}


/* LIST ITEM */

.content li{
  display:grid;
  grid-template-columns:20px 1fr;
  gap:10px;
}


/* STAR */

.star{
  font-size:18px;
  color:#9B8CFF;
  margin-top:3px;
}


/* TEXT */

.content li p{
  font-family:"Satoshi", sans-serif;
  font-size:14px;
  line-height:1.6;
  letter-spacing:0.02em;
  color:#A7A9BE;
}


/* IMAGE */

.image{
  position:relative;
  display:flex;
  justify-content:center;
  align-items:center;
}


/* GLOW EFFECT */

.glow{
  position:absolute;
  width:420px;
  height:420px;

  background:radial-gradient(
    circle,
    rgba(124,92,255,0.35),
    transparent 70%
  );

  filter:blur(80px);
  z-index:0;
}


/* IMAGE STYLE */

.image img{
  position:relative;
  z-index:2;
  width:100%;
  max-width:640px;
}



/* TABLET */

@media (max-width:1024px){

.features-container{
  grid-template-columns:1fr;
  gap:60px;
}

/* TEXT FIRST */
.content{
  order:1;
}

/* IMAGE SECOND */
.image{
  order:2;
}

.content h2{
  font-size:36px;
}

}


/* MOBILE */

@media (max-width:640px){

.features{
  padding:70px 20px;
}

.content h2{
  font-size:28px;
  line-height:1.3;
}

.content ul{
  max-width:100%;
}

.content li p{
  font-size:13px;
}

.image img{
  max-width:360px;
}

.glow{
  width:280px;
  height:280px;
}

}

</style>