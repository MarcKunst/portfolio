<template>
    <section id="contact-container">
        <article id="contact-text">
            <p class="medium">Thanks for scrolling all the way down. You can get in contact with me by mailing me or by becoming a connection on LinkedIn ;)</p>
        </article>
        <article>
            <h3>EMAIL</h3>
            <div class="underline short"></div>
            <p class="email">marckunst93@gmail.com</p>
            <br>
            <h3>SOCIAL</h3>
            <div class="underline middle"></div>
            <p><a href="https://www.linkedin.com/in/marc-kunst-917a4495" target="blank">LinkedIn</a></p>
        </article>
    </section>
</template>

<script>


export default {
    
}
</script>

<style scoped>

#contact-container {
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
    color: #fdfdfd;
}

.email {
    margin-bottom: 3rem;
}

h3 {
    font-family: Didot;
    font-style: italic;
    font-size: 1.5rem;
    font-weight: 100;
    padding-left: 0.15rem;
    color: #fdfdfd;
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

.middle {
    width: 7rem;
}

.short {
    width: 4rem;
}
a {
    text-decoration: none;
    color: #fdfdfd;
}

@media (max-width: 768px) {
    #contact-container {
    width: 100%;
    height: 100%;
    display: grid;
    grid-template-columns: 1fr;
    column-gap: 4rem;
    }
}

</style>