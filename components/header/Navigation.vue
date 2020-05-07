<template>

  <nav class="navbar">
        <div id="logo-wrapper">
            <a id="logo" href="#" v-scroll-to="'#header-section'">MK</a>
            <div class="underline logo-line"></div>
    </div>
    <label class="navbar-toggle" id="js-navbar-toggle" for="chkToggle">
        <img class="menu-button" src="../../assets/images/menu.svg" alt="menu">
        </label>
    <input type="checkbox" id="chkToggle">
    <ul class="main-nav" id="js-menu">
      <li class="nav-item">
        <a class="nav-item-link" href="#" v-scroll-to="'#project-section'">PROJECTS</a>
        <div class="underline"></div>
      </li>
      <li class="nav-item">
        <a class="nav-item-link" href="#" v-scroll-to="'#snippets-section'">SNIPPETS</a>
        <div class="underline"></div>
      </li>
      <li class="nav-item">
        <a class="nav-item-link" href="#" v-scroll-to="'#about-section'">ABOUT</a>
        <div class="underline"></div>
      </li>
      <li class="nav-item">
        <a class="nav-item-link" href="#" v-scroll-to="'#contact-section'">CONTACT</a>
        <div class="underline"></div>
      </li>
    </ul>
  </nav>
</template>

<script>

export default {

}
</script>

<style scoped>

* {
    font-family: Didot;
    font-style: italic;
}

.navbar {
  font-size: 18px;
  background-color: #fdfdfd;
  padding-bottom: 10px;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 2;
}

.main-nav {
  list-style-type: none;
  display: none;
}


.nav-links {
  text-decoration: none;
}

.main-nav li {
  text-align: center;
  margin: 15px auto;
}

 #logo-wrapper {
      display: flex;
      flex-direction: column;
      align-content: space-around;
  }

 #logo-wrapper:hover > .underline {
     width: 3rem;
 }

 #logo {
     color: #282828;
     margin: 0 4.2rem;
     font-family: Didot;
     font-style: italic;
     font-size: 2rem;
     text-decoration: none;
 }

 .underline {
    height: 1px;
    width: 2rem;
    background-color: #DDA681;
    transition: width 200ms;
}

.navbar-toggle {
  position: absolute;
  top: 10px;
  right: 0px;
  cursor: pointer;
  color: rgba(255, 255, 255, 0.8);
  font-size: 24px;
}

.menu-button {
    width: 1.5rem;
    margin-right: 4rem
}

#chkToggle {
  visibility: visible;
  position: absolute;
  right: 4rem;
  top: 1rem;
  display: none;
}

#chkToggle:checked + ul.main-nav {
  display: block;
   display: flex;
    flex-direction: column;
}

 .nav-item {
     margin: 0 0 0 4rem;
     font-family: Didot;
     font-style: italic;
     display: flex;
     flex-direction: column;
     align-content: flex-start;
     
 }

 .nav-item:hover > .underline {
     width: 100%;
 }

.nav-item-link {
 color: #282828;
 text-decoration: none;
 font-size: 1rem;
}

.underline {
    height: 1px;
    width: 2rem;
    background-color: #DDA681;
    transition: width 200ms;
}

.logo-line {
    margin: -0.4rem 0 0 4rem;
} 

@media screen and (min-width: 768px) {
  .navbar {
    display: flex;
    justify-content: space-between;
    padding-bottom: 0;
    height: 70px;
    align-items: center;
  }


#chkToggle:checked + ul.main-nav {
  display: block;
   display: flex;
    flex-direction: row;
}

  #upper-nav {
      display: flex;
      flex-direction: row;
  }

  #chkToggle {
  visibility: hidden;
}

  #chkToggle:checked + ul.main-nav {
    display: flex;
  }

   .nav-item:hover > .underline {
     width: 100%;
 }

  .main-nav {
    display: flex;
    margin-right: 4rem;
    flex-direction: row;
    justify-content: space-between;
    width: 28rem;
  }

  .main-nav li {
    margin: 0;
  }

  .navbar-toggle {
    display: none;
  }

   .underline {
    height: 1px;
    width: 2rem;
    background-color: #DDA681;
    transition: width 200ms;
}
}

</style>