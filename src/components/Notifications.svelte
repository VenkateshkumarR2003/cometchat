<section class="notifications">

  <div class="notifications-container">

    <!-- LEFT CONTENT -->
    <div class="content">

      <p class="label">Multichannel notifications engine</p>

      <h2>
        Your agent is only helpful if people
        come back to talk to it.
      </h2>

      <p class="desc">
        Most agents get ghosted. Yours won’t.
      </p>

      <ul class="features">

        <li>Native push, email, and SMS support</li>

        <li>Retry logic, delivery throttling, and batching</li>

        <li>
          Trigger-based delivery rules — unread X mins,
          fallback triggered, user went silent
        </li>

        <li>Threaded email replies (yes, replies go back to chat!)</li>

        <li>Integrates with SendGrid, Twilio, or your custom providers</li>

        <li>User-level frequency + preference settings</li>

      </ul>

      <p class="note">
        Notifications aren’t a growth hack. They’re UX glue.
        And we built them so you wouldn’t have to.
      </p>

    </div>


    <!-- RIGHT IMAGE -->
    <div class="diagram">
      <img src="/notification.png" alt="notification diagram">
    </div>

  </div>

</section>



<style>

.notifications{
  padding:140px 32px;
  background:#0A0914;
}


/* MAIN CONTAINER */

.notifications-container{

  max-width:1200px;
  margin:auto;

  display:grid;
  grid-template-columns:520px 1fr;
  gap:80px;

  align-items:center;
}


/* LABEL */

.label{
  color:#9B8CFF;
  font-size:14px;
  font-weight:500;
  margin-bottom:10px;
}


/* TITLE */

.content h2{
  font-size:36px;
  line-height:1.25;
  font-weight:600;
  margin-bottom:12px;
  max-width:520px;
}


/* DESCRIPTION */

.desc{
  color:#9EA3B3;
  font-size:15px;
  margin-bottom:22px;
}


/* FEATURES LIST */

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
  line-height:1.5;
  color:#C3C7D6;
}


/* PURPLE STAR */

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
  max-width:520px;
}


/* DIAGRAM */

.diagram{
  display:flex;
  justify-content:flex-end;
}

.diagram img{
  width:100%;
  max-width:620px;
}



/* TABLET */

@media (max-width:1024px){

.notifications-container{
  grid-template-columns:1fr;
  gap:60px;
}

/* IMAGE FIRST LIKE FIGMA MOBILE */

.diagram{
  order:1;
  justify-content:center;
}

}



/* MOBILE */

@media (max-width:640px){

.notifications{
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

.diagram img{
  max-width:420px;
}

}

</style>