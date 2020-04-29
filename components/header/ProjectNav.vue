<template>
    <nav>
        <div id="logo-wrapper">
            <nuxt-link id="logo" to="/">MK</nuxt-link>
            <div class="underline"></div>
        </div>
        <nuxt-link to="/" id="back-button">
            <img src="../../assets/images/cross.svg" alt="back button">
        </nuxt-link>
        
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

#back-button {
     height: 1.2rem;
     margin-right: 4rem;
 }

#back-button>img {
      height: 100%;
  }

.underline {
    height: 1px;
    width: 2rem;
    background-color: #DDA681;
    margin: -0.4rem 0 0 4rem;
    transition: width 200ms;
}

</style>