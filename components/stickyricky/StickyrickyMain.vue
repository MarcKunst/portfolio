<template>
    <section id="pingping-container">
        <section id="role">
            <article>
                <h3>MY ROLE</h3>
                <div class="role-line"></div>
                <p>within five weeks I design and developed everything myself except for the music.</p>
            </article>
            <article>
                <h3>TOOLS I USED</h3>
                <div class="tools-line"></div>
                    <ul>
                        <li>Sketch</li>
                        <li>Unity</li>
                        <li>Anima 2D</li>
                        <li>WebGL</li>
                        <li>C#</li>
                    </ul>
            </article>
        </section>

        <h3>THE ASSIGNMENT</h3>
        <div class="assignment-line"></div>
        <section id="assignment">
            <article>
                <p>During my minor Applied Game Design I developed a 2D platformer called Sticky Ricky. This is the first digital game I ever made and also my first introduction in Unity.</p>
            </article>
        </section>
        <section id="concept-part-1">
            <article>
                <h3 class="feature-headers">THE CONCEPT</h3>
                <div class="concept-part-1-line"></div>
                <p>Sticky Ricky is a 2D platformer made for a younger target group (from 8 years old). In which you play a little purple blob called Ricky. As the name suggests, ricky sticks to everything. It can slip against walls and hang on its head. The goal of Sticky Ricky is to reach the end of all levels. But when the player is looking for more challenge, the player must collect all the special berries and pollen.</p>
            </article>
            <img class="screen-img" src="../../assets/images/first_level_sketch.jpg" alt="first level sketch">
        </section>
        <section id="concept-part-2">
                <article>
                <h3 class="feature-headers">DESIGN</h3>
                <div class="concept-part-2-line"></div>
                <p>There was a lot that needed to be design for this game. I worked on the storytelling, level design, character animations and sound design to name a few. If you are interested in my complete design process from start to finish. Please read my <a href="https://www.notion.so/Blog-0993f03674d24eea9ea32ed00edb2675">blog</a> where I describe every step in full detail.</p>
            </article>
            <img class="screen-img" src="../../assets/images/sticky-design.png" alt="sticky ricky design">
        </section>
        <section id="concept-part-3">
            <article>
                <h3 class="feature-headers">DEVELOPMENT</h3>
                <div class="concept-part-3-line"></div>
                <p>This was my first time developing a game in Unity. During this project I learned a lot about game physics and how to structure a game. This was also my first time writing C#. Luckily for me I was used to Javascript and C# has a lot of similar features.
                </p>
            </article>
            <img class="screen-img" src="../../assets/images/sticky-development.png" alt="skeleton animation">
        </section>
        <section id="button-wrapper">
            <a id="view-project-button" href="https://marc-kunst.itch.io/sticky-ricky" target="blank">
                Play game
            </a>
            <a id="view-project-button" href="https://www.notion.so/Blog-0993f03674d24eea9ea32ed00edb2675" target="blank">
                Go to blog
            </a>
        </section>
    </section>
</template>

<script>


export default {
    
}
</script>

<style scoped>

#pingping-container {
    height: 100%;
    margin: 4rem;
    
}

#role {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 4rem;
    margin-bottom: 3rem;
}

#assignment {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr;
    column-gap: 4rem;
}

#concept-part-1 {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

#concept-part-2 {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

#concept-part-3 {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

.screen-img {
    width: 100%;
    box-shadow: 0rem 0.5rem 1rem 0rem rgb(163, 163, 163);
    
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

.feature-headers {
    padding-top: 0rem;
}

.role-line {
    height: 1px;
    width: 6rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem;
}

.tools-line {
    height: 1px;
    width: 10rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem;
}

.assignment-line {
    height: 1px;
    width: 15rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem; 
}

.concept-part-1-line {
    height: 1px;
    width: 11rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem; 
}

.concept-part-2-line {
    height: 1px;
    width: 6rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem; 
}

.concept-part-3-line {
    height: 1px;
    width: 9rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem; 
}

.medium {
    font-weight: 500;
    font-size: 1.1rem;
}

.short {
    width: 10rem;
}

ul {
    padding: 0;
    list-style: none;
}

#button-wrapper {
    display: flex;
    justify-content: center;
    margin-top: 5rem;
}

#view-project-button {
    width: 15rem;
    height: 4rem;
    background-color: #DDA681;
    border: 2px solid #fdfdfd;
    text-decoration: none;
    text-align: center;
    line-height: 3.8rem;
    font-family: 'Montserrat', sans-serif;
    color: #fdfdfd;
    font-weight: 500;
    transition: background-color 200ms;
    margin: 0 1rem 0;
}

#view-project-button:hover {
    background-color: rgb(202, 141, 100);
}

@media (max-width: 768px) {
    #role {
        grid-template-columns: 1fr;
    }

    #assignment {
        grid-template-columns: 1fr;
    }

    #concept-part-1 {
        grid-template-columns: 1fr;
    }

    #concept-part-2 {
        grid-template-columns: 1fr;
    }

    #concept-part-3 {
        grid-template-columns: 1fr;
    }
}

</style>