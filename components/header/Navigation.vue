<template>
    <nav>
        <div id="logo-wrapper">
            <a id="logo" href="#" v-scroll-to="'#header-section'">MK</a>
            <div class="underline logo-line"></div>
        </div>
        <ul>
            <li class="nav-item">
                <a class="nav-item-link" href="#" v-scroll-to="'#project-section'">PROJECTS</a>
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
 nav {
     width: 100%;
     height: 5em;
     background-color: #fdfdfd;
     position: fixed;
     top: 0;
     display: flex;
     justify-content: space-between;
     align-items: center;
     z-index: 2;
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

 ul {
     list-style: none;
     display: flex;
     justify-content: flex-end;
     align-items: center;
     width: 20rem;
     height: 100%;
     right: 0;
     position: absolute;
     padding: 0 4rem;
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

</style>