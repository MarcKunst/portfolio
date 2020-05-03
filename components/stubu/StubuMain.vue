<template>
    <section id="pingping-container">
        <section id="role">
            <article>
                <h3>MY ROLE</h3>
                <div class="role-line"></div>
                <p>For this project I was responsible for the development of the app and the creation of the data visualisties.</p>
            </article>
            <article>
                <h3>TOOLS I USED</h3>
                <div class="tools-line"></div>
                    <ul>
                        <li>Nuxt.js</li>
                        <li>Graph.js</li>
                        <li>VueX</li>
                    </ul>
            </article>
        </section>

        <h3>THE ASSIGNMENT</h3>
        <div class="assignment-line"></div>
        <section id="assignment">
            <article>
                <p>Nibud wanted to gain more insights from their dataset of all cost items in the Netherlands. We as students were free to decide for which target group we would make a product based on the dataset. We eventually chose students as the target group.</p>
            </article>
        </section>
        <section id="loan-feature">
            <article>
                <h3 class="feature-headers">DEBT INSIGHTS</h3>
                <div class="loan-line"></div>
                <p>The app consists of three features that are brought to the students in a narrative way.</p>
                <br>
                <p>First, the student can calculate his or her final study debt. This includes how much the student borrows per month. How long the student has been studying and how long the student plans to study.</p>
                <br>
                <p>Every answer in the questionair will be stored. I used VueX for the state management.</p>
                <br>
                <p>Ultimately, the student will see the expected study debt, along with the average student debt</p>
            </article>
            <img class="screen-img" src="../../assets/images/loan-1.png" alt="image of a questionair to determine loan.">
            <img class="screen-img" src="../../assets/images/loan-result.png" alt="result of student loan">
        </section>
        <section id="budget">
                <article>
                <h3 class="feature-headers">BUDGET CALCULATOR</h3>
                <div class="budget-line"></div>
                <p>The student is then given the opportunity to calculate his or her own budget. The student can see in a graph which income and expenditure are made.</p>
                <br>
                <p>The student also sees the average income and expenditure of other students in the Netherlands. This data is based on the Nibud dataset.</p>
            </article>
            <img class="screen-img" src="../../assets/images/budget.png" alt="budget form">
            <img class="screen-img" src="../../assets/images/budget-graph.png" alt="results of the budget form">
        </section>
        <section id="reward">
            <article>
                <h3 class="feature-headers">TESTIMONIALS</h3>
                <div class="loan-line"></div>
                <p>The last part of the app allows students to listen to personal stories from fellow students. In this example, students talk about their own experiences with their student debt.
                </p>
            </article>
            <img class="screen-img" src="../../assets/images/testimonials.png" alt="testimonials">
        </section>
        <section id="button-wrapper">
            <a id="view-project-button" href="https://stubu.netlify.app/" target="blank">
                View project
            </a>
            <a id="view-project-button" href="https://github.com/MarcKunst/nibud/wiki/State-management" target="blank">
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

#loan-feature {
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr));
    justify-items: center;
    column-gap: 4rem;
    row-gap: 4rem;
    margin-top: 8rem;
}

#budget {
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

.loan-line {
    height: 1px;
    width: 11rem;
    background-color: #DDA681;
    margin: 0rem 0 1rem; 
}

.budget-line {
    height: 1px;
    width: 16rem;
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
}

</style>