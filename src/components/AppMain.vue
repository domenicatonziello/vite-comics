<script>
import AppBanner from './AppBanner.vue';
import AppCard from './AppCard.vue';
export default {
    name: 'AppMain',
    components: { AppBanner, AppCard },
    props: {
        comics: Array
    }
}
</script>


<template>
    <main>
        <!-- Jumbotron -->
        <div class="jumbo"></div>
        <!-- main-top -->
        <section class="main-top">
            <div class="title"> Current Series </div>
            <div class="container">
                <app-card v-for="comic in comics" :key="comic.series" :comic="comic"></app-card>
            </div>
        </section>
        <!-- main bottom -->
        <app-banner></app-banner>
    </main>
</template>


<style lang="scss" scoped>
.jumbo {
    height: 300px;
    width: 100%;
    background-image: url("../assets/img/jumbotron.jpg");
    background-size: cover;
    background-position: top;
}

.main-top {
    background-color: black;
    color: white;
    min-height: 400px;

    position: relative;

    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        flex-wrap: wrap;
        padding: 30px 0;

    }

    .title {
        display: inline-block;
        background-color: dodgerblue;
        color: white;
        text-transform: uppercase;
        padding: 10px;
        font-weight: bold;
        position: relative;
        top: 0;
        left: 180px;
    }
}
</style>