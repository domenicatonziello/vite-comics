<script>
export default {
    name: 'AppFooter',
}
</script>

<template>
    <footer>
        <!-- footer top -->
        <section class="footer-top">
            <div class="container">
                <div class="col-left">
                    <!-- lista 1-->
                    <div>
                        <div>
                            <h3>DC COMICS </h3>
                            <ul>
                                <li>Charactes</li>
                                <li>Comics </li>
                                <li>Movies</li>
                                <li>Tv</li>
                                <li>Games</li>
                                <li>Video</li>
                                <li>News</li>
                            </ul>
                        </div>
                        <div>
                            <h3>SHOP</h3>
                            <ul>
                                <li>Shop DC </li>
                                <li>Shop DC Collectibles</li>
                            </ul>
                        </div>
                    </div>
                    <!-- lista 2 -->
                    <div>
                        <div>
                            <h3> DC</h3>
                            <ul>
                                <li>Terms Of Use </li>
                                <li>Privacy policy (New)</li>
                                <li>Ad Choise </li>
                                <li>Advertising</li>
                                <li>Jobs</li>
                                <li>Subscriptions</li>
                                <li>Talent Workshops</li>
                                <li>CPSC Certificates</li>
                                <li>Resings</li>
                                <li>Shop Help</li>
                                <li>Contact Us</li>
                            </ul>
                        </div>
                    </div>
                    <!-- lista 3 -->
                    <div>
                        <div>
                            <h3>SITES</h3>
                            <ul>
                                <li>DC</li>
                                <li>MAD Magazine</li>
                                <li>DC Kids</li>
                                <li>DC Universe</li>
                                <li>DC Power Visa</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-right">
                    <img src="../assets/img/dc-logo-bg.png" alt="dc-logo">
                </div>
            </div>
        </section>
        <!-- footer bottom -->
        <section class="footer-bottom">
            <div class="container">
                <div class="nav-left">
                    <button type="button"> SIGN-UP NOW!</button>
                </div>
                <div class="nav-right">
                    <h5> FOLLOW US </h5>
                    <a href="#"> <img src="../assets/img/footer-facebook.png" alt="Facebook"> </a>
                    <a href="#"> <img src="../assets/img/footer-twitter.png" alt="twitter"> </a>
                    <a href="#"> <img src="../assets/img/footer-youtube.png" alt="youtube"> </a>
                    <a href="#"> <img src="../assets/img/footer-pinterest.png" alt="pinterest"> </a>
                    <a href="#"> <img src="../assets/img/footer-periscope.png" alt=""> </a>
                </div>
            </div>
        </section>
    </footer>
</template>


<style lang="scss" scoped>
footer {
    height: calc(100vh - 280px);
    /* border: 3px dashed red; */
}

/* footer top */
.footer-top {
    height: calc(100% - 70px);
    background-image: url('../assets/img/footer-bg.jpg');

    .container {
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .col-left {
        height: 100%;
        flex-basis: 60%;
        display: flex;
        color: white;
        font-family: "Open Sans Condensed", sans-serif;

        &>* {
            padding: 15px 0;
            margin-right: 20px;
        }

        h3 {
            margin-bottom: 5px;
        }

        ul {
            margin-bottom: 10px;

            li {
                font-size: 13px;
                color: lightgray;
            }
        }
    }

    .col-right {
        height: 100%;
        flex-basis: 40%;

        img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    }

}

/* footer-bottom */
.footer-bottom {
    height: 70px;
    background-color: rgb(48, 48, 48);

    .container {
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    button {
        padding: 10px;
        cursor: pointer;
        background-color: rgb(48, 48, 48);
        color: white;
        font-weight: bold;
        border-color: dodgerblue;
    }

    .nav-right h5 {
        color: dodgerblue;
        display: inline;
    }

    img {
        padding: 10px;
        vertical-align: middle;
    }
}
</style>