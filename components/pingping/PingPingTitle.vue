<template>
    <div id="title">
        <div class="title-text">
            <div class="title-text-name">
                <h1>PING PING</h1>
                <div class="underline"></div>
            </div>
            <div class="title-text-sub">
                <h2>“Designing a product that helps young people stay out of debt."</h2>
            </div>
        </div>
    </div>

</template>

<script>

export default {

}
</script>

<style scoped>

#title {
    align-self: center;
    display: flex;
    justify-content: center;
    justify-items: center;
    flex-direction: row;

}

.title-text {
    padding-left: 2rem;
    z-index: 1;
}

h1 {
    font-family: Didot;
    font-style: italic;
    font-size: 3.8rem;
    font-weight: 100;
    padding-left: 0.5rem;
    padding-top: 3rem;
    justify-self: center;

}

.underline {
    height: 2px;
    width: 17rem;
    background-color: #DDA681;
    margin: -0.5rem 0 1rem;

}

h2 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 1.1rem;
    letter-spacing: 2px;
    width: 20rem;
    text-align: center;
    margin-top: 2rem;
}

</style>