<section class="features">

<div class="features-container">

<!-- CARD 1 -->
<div class="feature-card">

<div class="feature-top">

<div class="feature-icon">
<img src="/brain.png" alt="">
</div>

<h3>BYOB - Bring Your Own (Agent) Brain</h3>

<ul>
<li>Use your existing LLM orchestration</li>
<li>Plug into CometChat’s UI, mod, notifications, and insights</li>
<li>Modular, protocol-compatible, and fast to implement</li>
</ul>

<a href="#">Learn more</a>

</div>

<div class="feature-visual">
<img src="/byob-diagram.png" alt="">
</div>

</div>



<!-- CARD 2 -->
<div class="feature-card">

<div class="feature-top">

<div class="feature-icon">
<img src="/gear.png" alt="">
</div>

<h3>Build Inside CometChat</h3>

<ul>
<li>Visual Agent Builder</li>
<li>Design prompt logic, memory, retries, tool use</li>
<li>Simulate and ship — all from a single canvas</li>
</ul>

<a href="#">Learn more</a>

</div>

<div class="feature-visual">
<img src="/builder-diagram.png" alt="">
</div>

</div>

</div>

</section>



<style>

.features{
padding:30px 32px;
background:#0A0914;
}


/* CONTAINER */

.features-container{

max-width:1200px;
margin:auto;

display:grid;
grid-template-columns:1fr 1fr;
gap:18px;

}


/* CARD */

.feature-card{

background:#0A0914;

border:1px solid rgba(255,255,255,0.08);

border-radius:22px;

padding:40px;

min-height:460px;

display:flex;
flex-direction:column;
justify-content:space-between;

position:relative;
overflow:hidden;
}



/* GRID BACKGROUND */

.feature-card::before{

content:"";
position:absolute;
inset:0;

background-image:
linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);

background-size:42px 42px;

opacity:0.3;
pointer-events:none;

}



/* TOP */

.feature-top{
position:relative;
z-index:2;
}



.feature-icon{

width:64px;
height:64px;

display:flex;
align-items:center;
justify-content:center;

margin-bottom:20px;

background:none;
border:none;
}


.feature-icon img{

width:46px;
height:auto;

object-fit:contain;

}



/* TITLE */

.feature-card h3{

font-size:22px;
font-weight:600;

margin-bottom:16px;
}



/* LIST */

.feature-card ul{

list-style:none;
padding:0;

margin-bottom:18px;
}

.feature-card li{

position:relative;
padding-left:18px;

margin-bottom:8px;

font-size:14px;

color:#B9BCD0;
}

.feature-card li::before{

content:"✦";

position:absolute;
left:0;

color:#8B7FFF;
font-size:12px;

}



/* LINK */

.feature-card a{

color:#8B7FFF;

font-size:14px;

text-decoration:none;
}



/* VISUAL AREA (IMPORTANT FIX) */

.feature-visual{

display:flex;
justify-content:center;
align-items:center;

height:220px;

margin-top:30px;

position:relative;
z-index:2;
}



/* IMAGE SIZE FIX */

.feature-visual img{

max-width:420px;
width:100%;
height:100%;

object-fit:contain;
}



/* TABLET */

@media(max-width:1024px){

.features-container{

grid-template-columns:1fr;
gap:28px;

}

.feature-card{
padding:36px;
}

.feature-visual{
height:200px;
}

}



/* MOBILE */

@media(max-width:640px){

.features{
padding:10px 20px;
}

.feature-card{
padding:28px;
}

.feature-card h3{
font-size:20px;
}

.feature-card li{
font-size:13px;
}

.feature-visual{
height:180px;
}

.feature-visual img{
max-width:320px;
}

}

</style>