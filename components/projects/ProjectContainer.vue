<template>
    <section id="project-container">
        <article></article>
        <article></article>
        <article></article>
        <article></article>
        <article></article>
        <article></article>
    </section>
</template>

<script>


export default {
    
}
</script>

<style scoped>

#project-container {
    width: 100%;
    height: 100%;
    display: grid;
    row-gap: 2.5rem;
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 2.5rem;
}

article {
    background-color: #DDA681;
}
</style>