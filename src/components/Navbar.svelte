<script>
  let open = false;
  const toggle = () => (open = !open);
</script>

<nav class="navbar">
  <div class="nav-container">

    <!-- Logo -->
    <div class="logo">
      <span class="logo-light">comet</span><span class="logo-bold">chat</span>
    </div>

    <!-- Desktop menu -->
    <ul class="menu" class:show={open}>
      <li>Platform</li>
      <li>Solutions</li>
      <li>Developers</li>
      <li>Resources</li>
      <li>Pricing</li>
    </ul>

    <!-- Right side -->
    <div class="right-group">

      <span class="login">Log in</span>

      <button class="demo">Schedule a demo</button>

      <div class="hamburger" on:click={toggle}>
        ☰
      </div>

    </div>

  </div>
</nav>

<style>

/* NAVBAR */

.navbar{
  position:absolute;
  width:100%;
  top:0;
  left:0;
  z-index:10;
}

/* CONTAINER */

.nav-container{
  max-width:1440px;
  margin:auto;
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:16px 32px;
}

/* LOGO */

.logo{
  font-family:Inter, sans-serif;
  font-size:20px;
  letter-spacing:-0.3px;
}

.logo-light{
  font-weight:400;
  color:white;
}

.logo-bold{
  font-weight:700;
  color:white;
}

/* MENU */

.menu{
  display:flex;
  gap:36px;
  list-style:none;
  font-family:Inter, sans-serif;
  font-size:14px;
  font-weight:500;
  color:#C8C8E6;
}

.menu li{
  cursor:pointer;
  transition:color .2s ease;
}

.menu li:hover{
  color:white;
}

/* RIGHT GROUP */

.right-group{
  display:flex;
  align-items:center;
  gap:20px;
}

/* LOGIN */

.login{
  font-family:Inter, sans-serif;
  font-size:14px;
  color:#C8C8E6;
  cursor:pointer;
}

.login:hover{
  color:white;
}

/* DEMO BUTTON */

.demo{
  font-family:Inter, sans-serif;
  font-size:14px;
  font-weight:500;
  padding:10px 20px;
  border-radius:10px;
  border:none;
  cursor:pointer;

  background:linear-gradient(135deg,#8A7CFF,#6C5CFF);
  color:white;
  transition:opacity .2s ease;
}

.demo:hover{
  opacity:0.9;
}

/* HAMBURGER */

.hamburger{
  display:none;
  font-size:22px;
  color:white;
  cursor:pointer;
}

/* TABLET */

@media (max-width:1024px){

.menu{
  gap:24px;
}

}

/* MOBILE */

@media (max-width:768px){

/* Hide desktop menu */

.menu{
  display:none;
  flex-direction:column;
  position:absolute;
  top:64px;
  left:0;
  width:100%;
  background:#07071A;
  padding:20px 32px;
  gap:18px;
}

.menu.show{
  display:flex;
}

/* Hide demo button */

.demo{
  display:none;
}

/* Show hamburger */

.hamburger{
  display:block;
}

/* Keep login visible */

.login{
  display:block;
}

.nav-container{
  padding:14px 20px;
}

.logo{
  font-size:18px;
}

}

/* SMALL MOBILE */

@media (max-width:420px){

.logo{
  font-size:17px;
}

}

</style>
