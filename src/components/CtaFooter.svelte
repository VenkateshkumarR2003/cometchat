<section class="cta-footer">

<div class="cta-container">

<!-- LOGO -->
<div class="logo-box">
<img src="/Techicon.png" alt="">
</div>

<!-- ARC -->
<div class="arc">
<img src="/arc-glow.png" alt="">
</div>

<!-- TEXT -->
<h2>
You don’t need to build it<br>
all to ship it all
</h2>

<p class="cta-text">
Start with chat. Or go full stack. Build fast, scale securely,
and focus on what your agent does - not what it’s missing.
</p>

<!-- BUTTONS -->
<div class="cta-buttons">
<a class="btn-dark">Talk to us</a>
<a class="btn-purple">Try the Agent Builder</a>
</div>

</div>

</section>



<style>

.cta-footer{
position:relative;
padding:160px 20px 140px;
background:#0A0914;
text-align:center;
overflow:hidden;
}

.cta-container{
max-width:760px;
margin:auto;
position:relative;
}



/* LOGO */

.logo-box{
width:160px;
height:160px;

margin:0 auto;

display:flex;
align-items:center;
justify-content:center;

border-radius:24px;

background:#12122a;

border:1px solid rgba(255,255,255,0.08);

box-shadow:
0 0 80px rgba(140,120,255,0.55),
0 0 160px rgba(140,120,255,0.25);

position:relative;
z-index:1;
}

.logo-box img{
width:72px;
}



/* ARC IMAGE */

.arc{
position:absolute;

top:120px;
left:50%;
transform:translateX(-50%);

width:1000px;

z-index:2;
pointer-events:none;
}

.arc img{
width:100%;
display:block;
}



/* TEXT */

.cta-container h2{
font-size:42px;
font-weight:600;
line-height:1.2;
margin-top:160px;
margin-bottom:16px;
}



/* DESCRIPTION */

.cta-text{
color:#9EA3B3;
font-size:16px;
line-height:1.6;
margin-bottom:28px;
}



/* BUTTONS */

.cta-buttons{
display:flex;
justify-content:center;
gap:16px;
flex-wrap:wrap;
}



/* BUTTON STYLES */

.btn-dark{
background:#12122a;
padding:10px 18px;
border-radius:10px;
font-size:14px;
border:1px solid rgba(255,255,255,0.1);
color:white;
}

.btn-purple{
background:#7B61FF;
padding:10px 18px;
border-radius:10px;
font-size:14px;
color:white;
}



/* MOBILE */

@media(max-width:640px){

.cta-footer{
padding:120px 20px 90px;
}

.logo-box{
width:120px;
height:120px;
}

.logo-box img{
width:54px;
}

.arc{
top:90px;
width:600px;
}

.cta-container h2{
font-size:28px;
margin-top:120px;
}

.cta-text{
font-size:14px;
}

}

</style>