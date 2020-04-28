<template>
    <nav>
        <span id="logo">MK</span>
        <ul>
            <li class="nav-item">
                <nuxt-link class="nav-item-link" to="#">PROJECTS</nuxt-link>
            </li>
            <li class="nav-item">
                <nuxt-link class="nav-item-link" to="/about">ABOUT</nuxt-link>
            </li>
            <li class="nav-item">
                <nuxt-link class="nav-item-link" to="#">CONTACT</nuxt-link>
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
 }

 #logo {
     color: #282828;
     margin: 0 4rem;
     font-family: Didot;
     font-style: italic;
     font-size: 2rem;
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
     
 }

.nav-item-link {
 color: #282828;
 text-decoration: none;
}

</style>