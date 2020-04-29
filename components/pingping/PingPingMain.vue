<template>
    <section id="pingping-container">
        <section id="role">
            <article>
                <h3>MY ROLE</h3>
                <div class="role-line"></div>
                <p>I worked on the concept, the designs and the user experience. I was also responsible for directing the project and the communication with the client.</p>
            </article>
            <article>
                <h3>TOOLS I USED</h3>
                <div class="tools-line"></div>
                    <ul>
                        <li>Sketch</li>
                        <li>Adobe Photoshop</li>
                        <li>Trello</li>
                    </ul>
            </article>
        </section>

        <h3>THE ASSIGNMENT</h3>
        <div class="assignment-line"></div>
        <section id="assignment">
            <article>
                <p>During my internship at Fleks I did an assignment for the municipality of Amsterdam. The municipality wanted to develop a product that helps young people to prevent early debts.</p>
                <br>
                <p>There are a lot of young people in Amsterdam who don't grow up in an ideal environment. This means that many young people are not helped with their first steps to become adults.</p>
            </article>
            <article>
                <p>For example, when they have to apply for health insurance. Our task is to develop a product that helps young people with these tasks.</p>
                <br>
                <p>During this project we worked closely with the municipality. At the start of the project, we came together to map out the complete problem. Then we brainstormed with the people of the municipality about potential solutions.
                </p>
            </article>
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
}

#assignment {
    width: 100%;
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
</style>