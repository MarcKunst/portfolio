<template>
    <section id="snippets-container">
        <nuxt-link class="snippets-article" to="/animation">
            <article id="sprite-animation">
                <h3>SPRITE ANIMATION</h3>
                <div class="underline sprite-animation-line"></div>
                <p class="job-desc">Design | Animation</p>
            </article>
        </nuxt-link>
        <nuxt-link class="snippets-article" to="/datavis">
            <article id="data-vis">
                <h3>DATA VISUALIZATION</h3>
                <div class="underline data-vis-line"></div>
                <p class="job-desc">Functional programming</p>
            </article>
        </nuxt-link>
        <nuxt-link class="snippets-article" to="/modeling">
            <article id="modeling">
                <h3>3D SCENE</h3>
                <div class="underline modeling-line"></div>
                <p class="job-desc">3D modeling</p>
            </article>
        </nuxt-link>
        <nuxt-link class="snippets-article" to="/boardgame">
            <article id="boardgame">
                <h3>BOARDGAME</h3>
                <div class="underline boardgame-line"></div>
                <p class="job-desc">UX Design | Makerslab</p>
            </article>
        </nuxt-link>
    </section>
</template>

<script>


export default {
    
}
</script>

<style scoped>

#snippets-container {
    width: 100%;
    height: 100%;
    display: grid;
    row-gap: 2.5rem;
    grid-template-columns: repeat( auto-fit, minmax(15rem, 1fr) );
    column-gap: 2.5rem;
    align-items: center;
}

.snippets-article {
    text-decoration: none;
}

.snippets-article:hover > article {
    box-shadow: 0rem 0.7rem 1rem 0rem rgb(105, 105, 105);
}

article {
    height: 20rem;
    padding: 2rem;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    box-shadow: 0rem 0.5rem 1rem 0rem rgb(163, 163, 163);
    transition: box-shadow 300ms;
}

h3 {
    font-family: Didot;
    font-style: italic;
    font-size: 1.4rem;
    font-weight: 100;
    padding-left: 0.15rem;
    color: #fdfdfd;
    width: 100%;
}

.job-desc {
    font-family: 'Montserrat', sans-serif;
    font-size: 0.9rem;
    letter-spacing: 1px;
    font-weight: 500;
    color: #fdfdfd;
    padding-bottom: 1rem;
}

.info {
    font-family: 'Montserrat', sans-serif;
    font-size: 0.8rem;
    letter-spacing: 1px;
    font-weight: 400;
    color: #fdfdfd;
    text-align: justify;
}

#sprite-animation {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.575)
    ),
    url(../../assets/images/animation-thumb.png);
    background-size: cover;
    background-position: bottom;
    background-repeat: no-repeat;
}

#data-vis {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.89)
    ),
    url(../../assets/images/data-vis-thumb.png);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

#modeling {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),url(../../assets/images/3d-monster.png);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

#boardgame {
    background: 
    linear-gradient(
    rgba(0, 0, 0, 0), 
    rgba(15, 15, 15, 0.795)
    ),url(../../assets/images/boardgame-thumb.png);
    background-position: bottom;
    background-size: cover;
    background-repeat: no-repeat;
}

.underline {
    height: 1px;
    width: 19rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem;
}

.sprite-animation-line {
    width: 6rem;
}

.data-vis-line {
    width: 10rem;
}

.modeling-line {
    width: 5rem;
}

.boardgame-line {
    width: 8rem;
}

</style>