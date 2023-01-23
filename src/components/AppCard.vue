<script>
import { objectToString } from '@vue/shared';

export default {
    name: 'AppCard',
    props: {
        comic: Object
    }
}
</script>

<template>
    <figure>
        <img :src="comic.thumb" :alt="comic.type">
        <figcaption> {{ comic.series }} </figcaption>
    </figure>
</template>

<style scoped lang="scss">
figure {
    width: 150px;
    height: 150px;
    margin-bottom: 50px;
    padding: 5px;

    img {
        height: 100%;
        width: 100%;
        object-fit: cover;
    }

    figcaption {
        text-transform: uppercase;
        font-size: 13px;
    }
}
</style>