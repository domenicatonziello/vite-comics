<script>
export default {
    name: 'AppMain'
}
</script>


<template>
    <main>
        <!-- main-top -->
        <section class="main-top">
            <h3 class="container"> --> Content goes here -- </h3>
        </section>
        <!-- main bottom -->
        <section class="main-bottom">
            <ul class="container">
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital">
                    <p>Digital Comics</p>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital">
                    <p>Digital Comics</p>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital">
                    <p>Digital Comics</p>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital">
                    <p>Digital Comics</p>
                </li>
                <li>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital">
                    <p>Digital Comics</p>
                </li>
            </ul>
        </section>
    </main>
</template>


<style scoped>
.main-top {
    background-color: black;
    color: white;
    height: 100px;
    line-height: 100px;
    vertical-align: middle;
}

.main-bottom {
    background-color: dodgerblue;
    color: white;
    height: 100px;
    font-family: "Open Sans Condensed", sans-serif;
}

.main-bottom ul {
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.main-bottom li {
    padding: 10px 20px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.main-bottom img {
    max-height: 50%;
    margin-right: 10px;
}
</style>