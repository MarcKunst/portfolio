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
        <section id="core-feature">
            <article>
                <h3 class="feature-headers">THE CORE FEATURE</h3>
                <div class="core-line"></div>
                <p>We came up with the idea to develop an app in which young people follow a route in which they get their affairs in order. Step by step, the young people are helped with applying for health insurance, care allowance and opening a bank account.</p>
                <br>
                <p>The route to be followed is not the same for everyone. That's why we added a short questionnaire at the beginning of the app. Based on the questionnaire, a personal route is created for the user.</p>
            </article>
            <img class="screen-img" src="../../assets/images/questionair.png" alt="image of pingping questionair">
            <img class="screen-img" src="../../assets/images/route.png" alt="image of personalized route">
        </section>
        <section id="helping">
                <article>
                <h3 class="feature-headers">HELPING THE USER</h3>
                <div class="core-line"></div>
                <p>Each step on the route has a detailed explanation of the subject. Also, with every step there is a video explaining how the user can complete this task.</p>
                <br>
                <p>We also gave tips on how to save money or to gain insight into their finances.</p>
            </article>
            <img class="screen-img" src="../../assets/images/bank account.png" alt="How to sign up for a bank account">
            <img class="screen-img" src="../../assets/images/tips.png" alt="tips">
        </section>
        <section id="reward">
            <article>
                <h3 class="feature-headers">THE REWARD SYSTEM</h3>
                <div class="core-line"></div>
                <p>We have added a reward system to ensure that the young people complete all the tasks on the route. The user receives points for every task that is performed. These points can be redeemed for real life rewards. For example, a day at the zoo.
                </p>
            </article>
            <img class="screen-img" src="../../assets/images/zoo.png" alt="zoo reward">
            <img class="screen-img" src="../../assets/images/reward.png" alt="earning credits">
        </section>
        <section id="button-wrapper">
            <a id="view-project-button" href="https://pingping.amsterdam.nl/" target="blank">
                View project
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
    grid-template-columns: 1fr 1fr;
    column-gap: 4rem;
}

#core-feature {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr));
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

#helping {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr));
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

#reward {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr));
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

.screen-img {
    width: 15rem;
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

.core-line {
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