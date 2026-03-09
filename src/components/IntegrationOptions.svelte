<section class="integration">

<div class="container">

<p class="tag">Chat integration options</p>

<h2>Your launch, your way. Done right.</h2>

<p class="subtitle">
Start with what gets you to production fastest — or matches your needs the best.
Swap it out or level it up later.
</p>


<div class="options">

<!-- CARD 1 -->
<div class="option">

<div class="icon">
<img src="/integration1.png">
</div>

<h3>Chat Builder</h3>

<ul>
<li>Visual interface for styling and configuring chat</li>
<li>Drop into any web or mobile app with a single snippet</li>
<li>Integrates with auth, analytics, and third-party tools</li>
<li>Great for prototypes, pilots, or teams with limited resources</li>
</ul>

<a href="/">Try Builder</a>

</div>


<!-- CARD 2 -->
<div class="option">

<div class="icon">
<img src="/integration2.png">
</div>

<h3>UI Kits</h3>

<ul>
<li>Available for all popular frameworks</li>
<li>Theming, layout, and logic hooks exposed</li>
<li>Save time on structure, focus on experience</li>
<li>Ideal for teams who want speed and polish</li>
</ul>

<a href="/">Try Builder</a>

</div>


<!-- CARD 3 -->
<div class="option">

<div class="icon">
<img src="/integration3.png">
</div>

<h3>SDKs & APIs</h3>

<ul>
<li>Available for all popular frameworks</li>
<li>Theming, layout, and logic hooks exposed</li>
<li>Save time on structure, focus on experience</li>
<li>Ideal for teams who want speed and polish</li>
</ul>

<a href="/">Try Builder</a>

</div>

</div>

</div>

</section>


<style>

.integration{
padding:120px 20px;
background:#0A0914;
color:white;
}

.container{
max-width:1200px;
margin:auto;
text-align:center;
}

.tag{
color:#8B7FFF;
font-size:14px;
margin-bottom:16px;
}

h2{
font-size:36px;
font-weight:600;
margin-bottom:16px;
}

.subtitle{
max-width:620px;
margin:auto;
color:#a7a9c0;
font-size:15px;
line-height:1.6;
margin-bottom:70px;
}



/* GRID */

.options{
display:grid;
grid-template-columns:repeat(3,1fr);
border-top:1px solid rgba(255,255,255,0.08);
border-bottom:1px solid rgba(255,255,255,0.08);
}



/* CARD */

.option{

padding:40px;

text-align:left;

border-right:1px solid rgba(255,255,255,0.08);

min-height:340px;

display:flex;
flex-direction:column;

gap:10px;

background:
radial-gradient(circle at top left,
rgba(124,108,255,0.35) 0%,
rgba(124,108,255,0.15) 35%,
rgba(10,9,20,1) 70%);

transition:0.3s;

}

.option:last-child{
border-right:none;
}

.option:last-child{
border-right:none;
}

.option li::before{

content:"✦";

position:absolute;
left:0;

color:#8B7FFF;

font-size:12px;

}

/* ICON */

.icon{

width:48px;
height:48px;

border-radius:12px;

display:flex;
align-items:center;
justify-content:center;

background:rgba(124,108,255,0.08);

border:1px solid rgba(124,108,255,0.25);

margin-bottom:18px;

}

.icon img{
width:26px;
}



/* TEXT */

.option h3{
font-size:20px;
margin-bottom:16px;
}

.option ul{
list-style:none;
padding:0;
margin-bottom:20px;
}

.option li{

font-size:14px;
color:#a9abc4;

margin-bottom:10px;

position:relative;
padding-left:18px;

}

/* STAR BULLETS */

.option li::before{

content:"✦";

position:absolute;
left:0;

color:#8B7FFF;

font-size:12px;

}



/* LINK */

.option a{
color:#8B7FFF;
font-size:14px;
text-decoration:none;
}



/* RESPONSIVE */

@media(max-width:900px){

.options{
grid-template-columns:1fr 1fr;
}

.option:nth-child(2){
border-right:none;
}

.option:nth-child(3){
border-top:1px solid rgba(255,255,255,0.08);
}

}


@media(max-width:600px){

.options{
grid-template-columns:1fr;
}

.option{
border-right:none;
border-top:1px solid rgba(255,255,255,0.08);
}

.option:first-child{
border-top:none;
}

h2{
font-size:28px;
}

}


</style>