<template>
    <nav>
        <a id="logo" href="#" v-scroll-to="'#header-section'">MK</a>
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

 #logo {
     color: #282828;
     margin: 0 4rem;
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

</style>