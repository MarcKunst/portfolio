<template>
    <div id="title">
        <div class="title-text">
            <div class="title-text-name">
                <h1>MARC KUNST</h1>
                <div class="underline"></div>
            </div>
            <div class="title-text-sub">
                <h2>Designer | Developer | Maker</h2>
            </div>
        </div>
        <img id="profile-pic" src="../../assets/images/marc_profile_purple.png" alt="photo of Marc Kunst" v-lazy-load>
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

}

.underline {
    height: 2px;
    width: 21rem;
    background-color: #DDA681;
    margin: -0.5rem 0 1rem;
}

h2 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 1.1rem;
    letter-spacing: 2px;
}

#profile-pic {
    width: 15rem;
    border-radius: 50%;
    box-shadow: 0rem 0.5rem 1rem 0rem rgb(122, 122, 122);
    margin: 0 0 0 -2rem;
}

@media (max-width: 768px) {

    #profile-pic {
    visibility: hidden;
    width: 0rem;
    }

    .title-text {
    padding-left: 0rem;
    }

    h1 {
        font-size: 2.5rem;
        padding-left: 0.25rem;
    }

    .underline {
        width: 14rem;
        height: 1px;
        margin: -0.4rem 0 0.8rem;
    }

    h2 {
        font-size: 1rem;
    }
}

</style>