<section class="insights">

  <div class="insights-container">

    <!-- LEFT CONTENT -->
    <div class="insights-content">

      <p class="insights-label">Insights dashboard</p>

      <h2>
        Ship the agent. Then make it better.
        Without needing Mixpanel, Segment,
        or BI setups.
      </h2>

      <p class="insights-desc">
        From day one, you get built-in visibility into what your agent is
        doing — and how people are responding.
      </p>

      <ul class="insights-features">

        <li>Resolution rates, fallback frequency, retry counts, latency</li>

        <li>Tool usage breakdowns, prompt paths, knowledge base hits</li>

        <li>
          Conversation-level analytics: drop-off points,
          re-engagement, success outcomes
        </li>

        <li>Sentiment markers and feedback loops</li>

        <li>Exportable, filterable, and privacy-respectful</li>

      </ul>

      <p class="insights-note">
        You can’t improve what you can’t see.
        With us, you never ship blind.
      </p>

    </div>



    <!-- RIGHT IMAGE -->
    <div class="insights-image">

      <img src="/insights.png" alt="Insights dashboard"/>

    </div>

  </div>

</section>



<style>

/* SECTION */

.insights{
  padding:30px 32px;
  background:#0A0914;
}


/* CONTAINER */

.insights-container{

  max-width:1200px;
  margin:auto;

  display:grid;
  grid-template-columns:1fr 1fr;
  gap:90px;
  align-items:center;

}


/* LABEL */

.insights-label{
  color:#9B8CFF;
  font-size:14px;
  font-weight:500;
  margin-bottom:12px;
}


/* TITLE */

.insights-content h2{
  font-size:36px;
  line-height:1.25;
  font-weight:600;
  margin-bottom:18px;
  max-width:520px;
}


/* DESCRIPTION */

.insights-desc{
  color:#9EA3B3;
  font-size:15px;
  line-height:1.6;
  margin-bottom:26px;
  max-width:520px;
}


/* LIST */

.insights-features{
  list-style:none;
  padding:0;
  margin:0;

  display:flex;
  flex-direction:column;
  gap:14px;
}

.insights-features li{
  position:relative;
  padding-left:20px;
  font-size:14px;
  line-height:1.5;
  color:#C3C7D6;
}


/* STAR BULLET */

.insights-features li::before{
  content:"✦";
  position:absolute;
  left:0;
  color:#9B8CFF;
  font-size:14px;
}


/* NOTE */

.insights-note{
  margin-top:20px;
  font-size:14px;
  color:#8C90A6;
  max-width:520px;
}


/* IMAGE */

.insights-image{
  display:flex;
  justify-content:center;
}

.insights-image img{
  width:100%;
  max-width:560px;
}


/* TABLET */

@media (max-width:1024px){

.insights-container{
  grid-template-columns:1fr;
  gap:60px;
}

}


/* MOBILE */

@media (max-width:640px){

.insights{
  padding:90px 20px;
}

.insights-content h2{
  font-size:26px;
}

.insights-desc{
  font-size:14px;
}

.insights-features li{
  font-size:13px;
}

.insights-image img{
  max-width:420px;
}

}

</style>