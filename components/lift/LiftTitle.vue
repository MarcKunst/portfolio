<template>
    <div id="title">
        <div class="title-text">
            <div class="title-text-name">
                <h1>LIFT</h1>
                <div class="underline"></div>
            </div>
            <div class="title-text-sub">
                <h2>“Creating a social app for people with a disability."</h2>
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
    display: flex;
    flex-direction: column;
}

.title-text-name, .title-text-sub{
    align-self: center;

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
    max-width: 80%;
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

@media (max-width: 768px) {

    .title-text {
    padding-left: 0rem;
    }

    h1 {
        font-size: 2.5rem;
        padding-left: 0.25rem;
    }

    .underline {
        width: 6rem;
        height: 1px;
        margin: -0.4rem 0 0.8rem;
    }

    h2 {
        font-size: 1rem;
        width: 100%;
        padding: 0 2rem;
    }
}

</style>