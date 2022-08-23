<template>
    <div class="hero">
        <section id="jumbotron">
            <p>Il mio primo jumbotron in Vue CLI!</p>
        </section>
    </div>
</template>

<script>
    export default {
        name: 'MyHero'
    }
</script>

<style lang="scss">
    #jumbotron {
        width: 100%;
        height: 600px;
        border: 1px solid black;
        background-image: url('https://www.chimerarevo.com/wp-content/uploads/2020/04/immagini-gratis.jpg');
        background-size: cover;
        background-position: center;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    p {
        font-size: 2rem;
        color: white;
        text-align: center;
    }
</style>