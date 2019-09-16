<template>
  <div class="app-cmp-wrapper">
<header id="header">
<HeaderBarTop />

<div class="container">
<nav class="navbar sticky-top navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="#">
  
     <img src="images/img/logo_sm1.png" alt="">
  </a>



  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link py-3" href="#">Home<span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link py-3 dropdown-toggle" id="navDropdownDomains" data-toggle="dropdown" href="#">Domains</a>
        <div class="dropdown-menu">
          <a class="dropdown-item" href="#">Domain Search</a>
          <a class="dropdown-item" href="#">Domain Setup Services</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link py-3" href="#">Hosting</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link py-3 dropdown-toggle" id="navDropdownMarketing" data-toggle="dropdown" href="#">Marketing</a>
      <div class="dropdown-menu">
        <a href="#" class="dropdown-item">Social Media</a>       
        <a href="#" class="dropdown-item">Email Marketing</a>
        <a href="#" class="dropdown-item">Postal Campaigns</a>
      </div>
      </li>
      <li class="nav-item">
        <a class="nav-link py-3" href="#">Web Design</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link py-3 dropdown-toggle" id="navDropdownSecurity" data-toggle="dropdown" href="#">CyberSecurity</a>
      <div class="dropdown-menu">
        <a href="#" class="dropdown-item">Purchase VPN</a>
        <a href="#" class="dropdown-item">HTTPS Certificate</a>
        </div>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link ml-4 pl-4 py-3 dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
         <span><i class="fa fa-user-circle"></i></span> My Account
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#"> <span><i class="fa fa-sign-in"></i></span> Login</a>          
          <a class="dropdown-item" href="#"> <span><i class="fa fa-user"></i></span> Register</a>
        </div>
      </li>
    </ul>
  </div>

</nav>
  </div>
</header>


  </div>
</template>

<script>
import HeaderBarTop from "@/components/HeaderBarTop";
export default {
  name: "HeaderNavbarAlt",
  components: {
    HeaderBarTop
  }
};
</script>

<style scoped>
.nav-link {
  padding-left: 0.5rem !important;
  padding-right: 0.5rem !important;
}


.container {
  width: 90% !important;
}
a.nav-link:focus {
    color: #970001;
}

.navbar-light .navbar-nav .nav-link:focus, 
.navbar-light .navbar-nav .nav-link:hover,
.nav-item .dropdown {
    background: #970001;
    color: #fff;
}

.nav-link {
  height: 60px;
  padding: 0px;
}

.navbar-brand {
  padding: 0px;
}

nav {
  padding-top: 0px;
  padding-bottom: 0px;
}
</style>