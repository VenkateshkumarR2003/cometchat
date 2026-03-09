<section class="agent-section">

<div class="agent-container">



<div class="agent-text">

<h2>
Everything your agent<br>
needs to go from<br>
prototype to product –<br>
fixed.
</h2>

<p>
Modular when you want control. All-in-one when
you just need to launch.
</p>

</div>




<div class="agent-image">

<img src="/agent-comparison.png" alt="agent features">

</div>

</div>

</section>


<style>

/* SECTION */

.agent-section{
background:#0A0914;
padding:10px 20px;
color:white;
}


/* CONTAINER */

.agent-container{
max-width:1200px;
margin:auto;

display:grid;
grid-template-columns:520px 1fr;
gap:40px;

align-items:center;
}


/* TEXT */

.agent-text{
max-width:520px;
}


/* HEADING */

.agent-text h2{
font-size:40px;
line-height:1.2;
font-weight:600;
margin-bottom:16px;
}


/* PARAGRAPH */

.agent-text p{
color:#9da0c3;
font-size:16px;
max-width:420px;
line-height:1.6;
}


/* IMAGE */

.agent-image{
display:flex;
justify-content:center;
}

.agent-image img{
width:100%;
max-width:640px;
}



/* TABLET */

@media (max-width:900px){

.agent-container{
grid-template-columns:1fr;
gap:40px;
}

.agent-text{
order:1;
}

.agent-image{
order:2;
}

.agent-text h2{
font-size:32px;
}

.agent-image img{
max-width:480px;
}

}



/* MOBILE */

@media (max-width:600px){

.agent-section{
padding:60px 20px;
}

.agent-text h2{
font-size:26px;
line-height:1.35;
}

.agent-text p{
font-size:14px;
}

.agent-image img{
max-width:340px;
}

}

</style>