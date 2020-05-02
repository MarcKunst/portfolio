<template>
    <section id="pingping-container">
        <section id="role">
            <article>
                <h3>TOOLS I USED</h3>
                <div class="tools-line"></div>
                    <ul>
                        <li>Javascript</li>
                        <li>3D.js</li>
                        <li>SPARQL</li>
                        <li>HTML 5</li>
                        <li>CSS 3</li>
                    </ul>
            </article>
        </section>

        <h3>THE ASSIGNMENT</h3>
        <div class="assignment-line"></div>
        <section id="assignment">
            <article>
                <p>I made a data visualization of the dataset of the ethnology museum in Leiden. The visualization shows how many weapons from East Asia are in the museum's collection. The weapons can then be viewed per country and are presented in a pie chart.</p>
                <br>
                <p>For me, this data visualization was a training in functional programming and working with D3.</p>
            </article>
        </section>
        <section id="concept-part-1">
            <img class="screen-img" src="../../assets/images/datavis-fullscreen.png" alt="data visualization">
        </section>
        <section id="button-wrapper">
            <a id="view-project-button" href="https://github.com/MarcKunst/frontend-data" target="blank">
                Go to Github
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
    grid-template-columns: 1fr;
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
}

#view-project-button:hover {
    background-color: rgb(202, 141, 100);
}

</style>