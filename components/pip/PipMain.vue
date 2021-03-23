<template>
    <section id="pingping-container">
        <section id="role">
            <article>
                <h3>MY ROLE</h3>
                <div class="role-line"></div>
                <p>I am the lead designer of this project. I do user tests, Im researching accessibility patterns, and design the app.</p>
            </article>
            <article>
                <h3>TOOLS I USED</h3>
                <div class="tools-line"></div>
                    <ul>
                        <li>Figma</li>
                        <li>Invision Studio</li>
                        <li>Trello</li>
                    </ul>
            </article>
        </section>

        <h3>THE ASSIGNMENT</h3>
        <div class="assignment-line"></div>
        <section id="assignment">
            <article>
                <p>During my internship at the IVLab at the Municipality of Amsterdam I got involved in the project.</p>
                <br>
                <p>The purpose of the assignment is to develop a new digital PIP. PIP stands for a personal integration and participation process.</p>
            </article>
            <article>
                <p>In this app immigrants can find everything related to their integration process. The immigrant forms his own trajectory together with their manager.</p>
                <br>
                <p>The app will be used by people of different native languages. Some of the users are also low literate. As a result, there is a great focus on accessibility while designing the app.
                </p>
            </article>
        </section>
        <section id="core-feature">
            <article>
                <h3 class="feature-headers">CLARITY</h3>
                <div class="core-line xshort"></div>
                <p>The integration process takes three years. That is why it is important for the user to know how he or she is doing. With the overview screen, the user can see where he / she stands in the process.</p>
                <br>
                <p>On the events screen, the user can see which important events will soon take place in their process.</p>
            </article>
            <img class="screen-img" src="../../assets/images/Overview_location.jpg" alt="image of the overview screen">
            <img class="screen-img" src="../../assets/images/Events_header_open.jpg" alt="image of the event screen">
        </section>
        <section id="helping">
                <article>
                <h3 class="feature-headers">PROVIDING INFORMATION</h3>
                <div class="core-line"></div>
                <p>Finding the user of any event information. The information is presented in various ways. The user can watch a video, read the text or have the text read aloud.</p>
                <br>
                <p>It is also possible to create a checklist for each event. Here the user can keep track of his / her tasks.</p>
            </article>
            <img class="screen-img" src="../../assets/images/Event_detail_screen.jpg" alt="How to sign up for a bank account">
            <img class="screen-img" src="../../assets/images/checklist.jpg" alt="tips">
        </section>
        <section id="button-wrapper">
            <a id="view-project-button" href="https://www.figma.com/file/0RyuJDS8Cp1RpvW1UakAv8/Persoonlijke-PIP-prototype?node-id=175%3A0" target="blank">
                View Figma Designs
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
    border-radius: 8px;
    
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

.xshort {
    width: 6rem;
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

@media (max-width: 768px) {
    #role {
        grid-template-columns: 1fr;
    }

    #assignment {
    grid-template-columns: 1fr;
    }
}

</style>