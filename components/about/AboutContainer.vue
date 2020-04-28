<template>
    <section id="about-container">
        <article>
            <p class="medium">I'm Marc Kunst, I'm 26 years old and I love to make stuff.</p>
            <br>
            <p>I started as a nurse but soon noticed that I needed a job with more creativity. So I decided to become a designer. Through the years I learned to design, code and create all sorts of things. And I love it!</p>
        </article>
        <article>
            <p>In my free time I like to game, play guitar and recently I started to develop my own video game.</p>
            <br>
            <p>Currently I study Communication and Multimedia Design at the University of Applied Sciences. I'm in the middle of my minor Applied Game Design.
            </p>
        </article>
        <article>
            <h3>SOME OF THE TOOLS I USE</h3>
            <div class="underline"></div>
            <ul>
                <li>Sketch</li>
                <li>Nuxt.js</li>
                <li>Adobe CC</li>
                <li>Unity</li>
                <li>VS Code</li>
                <li>Aseprite</li>
            </ul>
        </article>
        <article>
            <h3>THINGS I LIKE</h3>
            <div class="underline"></div>
            <ul>
                <li>Nintendo</li>
                <li>Ginger beer</li>
                <li>Rubiks cube</li>
                <li>BBQ</li>
                <li>Robin Williams</li>
                <li>Domino day</li>
            </ul>
        </article>
    </section>
</template>

<script>


export default {
    
}
</script>

<style scoped>

#about-container {
    width: 100%;
    height: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 4rem;
}

article {
    font-family: 'Montserrat', sans-serif;
    font-size: 1rem;
    text-align: justify;
    letter-spacing: 1px;
}

h3 {
    font-family: Didot;
    font-style: italic;
    font-size: 1.5rem;
    font-weight: 100;
    padding-left: 0.15rem;
    padding-top: 3rem;
}

.underline {
    height: 1px;
    width: 19rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem;

}

.medium {
    font-weight: 500;
    font-size: 1.1rem;
}

ul {
    padding: 0;
    list-style: none;
}
</style>