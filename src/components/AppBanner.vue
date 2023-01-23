<script>
export default {
    name: 'AppBanner'
}
</script>


<template>
    <section id="banner">
        <ul class="container">
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital">
                <p>Digital Comics</p>
            </li>
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="buy-comics-merchandise">
                <p>DC MERCHANDISE </p>
            </li>
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="buy-comics-subscriptions">
                <p>SUBSCRIPTION</p>
            </li>
            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="buy-comics-shop-locator">
                <p>COMIC SHOP LOCATOR</p>
            </li>
            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="buy-power-visa">
                <p>DC POWER VISA </p>
            </li>
        </ul>
    </section>
</template>


<style lang="scss" scoped>
#banner {
    background-color: dodgerblue;
    color: white;
    height: 100px;
    font-family: "Open Sans Condensed", sans-serif;

    ul {
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;

        li {
            padding: 10px 20px;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    }

    img {
        max-height: 50%;
        margin-right: 10px;
    }
}
</style>