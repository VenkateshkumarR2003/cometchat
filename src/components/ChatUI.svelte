<section class="chat-ui">

  <div class="chat-container">

    <!-- LEFT CONTENT -->
    <div class="content">

      <p class="label">Production-ready chat UI</p>

      <h2>
        The UX layer your agent deserves.
        Built for LLM-native interactions,
        out of the box.
      </h2>

      <p class="desc">
        Forget cobbling together buttons and hoping users “get it”.
        Our chat layer is purpose-built for how agents think —
        and how humans expect them to respond.
      </p>

      <ul class="features">

        <li>Token streaming with dynamic “thinking…” states</li>
        <li>Retry/stop buttons with full control logic</li>
        <li>Memory pills, prompt banners, and agent selectors</li>
        <li>Structured tool replies with inline citations</li>
        <li>Slash commands, modals, and frontend triggers</li>
        <li>Low/No-code Chat Builder, or more control via UI Kits and SDKs</li>
        <li>
          Fully AG-UI protocol compatible – including tool call rendering,
          memory markers, and fallback patterns
        </li>

      </ul>

      <p class="note">
        It’s not just a pretty shell. It’s UX that teaches trust,
        guides behavior, and makes your agent feel alive.
      </p>

    </div>


    <!-- RIGHT IMAGE -->
    <div class="phones">
      <img src="/chat.png" alt="chat ui"/>
    </div>

  </div>

</section>



<style>

.chat-ui{
  padding:30px 32px;
  background:#0A0914;
}

/* CONTAINER */

.chat-container{
  max-width:1200px;
  margin:auto;

  display:grid;
  grid-template-columns:1fr 1fr;
  gap:80px;
  align-items:center;
}


/* LABEL */

.label{
  color:#9B8CFF;
  font-size:14px;
  margin-bottom:12px;
  font-weight:500;
}


/* TITLE */

.content h2{
  font-size:36px;
  line-height:1.25;
  font-weight:600;
  margin-bottom:18px;
  max-width:520px;
}


/* DESCRIPTION */

.desc{
  color:#9EA3B3;
  font-size:15px;
  line-height:1.6;
  margin-bottom:26px;
  max-width:520px;
}


/* LIST */

.features{
  list-style:none;
  padding:0;
  margin:0;

  display:flex;
  flex-direction:column;
  gap:14px;
}

.features li{
  position:relative;
  padding-left:20px;
  font-size:14px;
  color:#C2C5D3;
  line-height:1.5;
}


/* STAR */

.features li::before{
  content:"✦";
  position:absolute;
  left:0;
  color:#9B8CFF;
  font-size:14px;
}


/* NOTE */

.note{
  margin-top:18px;
  font-size:14px;
  color:#8C90A6;
  line-height:1.5;
  max-width:520px;
}


/* IMAGE */

.phones{
  display:flex;
  justify-content:center;
}

.phones img{
  width:100%;
  max-width:520px;
}



/* TABLET */

@media (max-width:1024px){

.chat-container{
  grid-template-columns:1fr;
  gap:60px;
}

/* TEXT FIRST */
.content{
  order:1;
}

/* IMAGE SECOND */
.phones{
  order:2;
}

}



/* MOBILE */

@media (max-width:640px){

.chat-ui{
  padding:90px 20px;
}

.content h2{
  font-size:28px;
}

.desc{
  font-size:14px;
}

.features li{
  font-size:13px;
}

}

</style>