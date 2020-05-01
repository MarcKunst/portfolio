<template>
    <div class="title-text-name">
        <div id="title-wrapper">
            <h1>SNIPPETS</h1>
            <div class="underline"></div>
        </div>
        <h2>These snippets are a mix of smaller and/or homemade projects</h2>
    </div>
</template>

<script>

export default {

}
</script>

<style scoped>

.title-text-name {
    justify-self: center;
    margin-bottom: 4rem;
    display: flex;
    flex-direction: column;
}

#title-wrapper {
    align-self: center;
}

h1 {
    font-family: Didot;
    font-style: italic;
    font-size: 2.5rem;
    font-weight: 100;
    padding-left: 0.25rem;
    padding-top: 3rem;

}

.underline {
    height: 2px;
    width: 11rem;
    background-color: #DDA681;
    margin: -0.3rem 0;

}

h2 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 1.1rem;
    letter-spacing: 2px;
    width: 30rem;
    text-align: center;
    margin-top: 2rem;
}

</style>