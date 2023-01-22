<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ],
        }
    }
}
</script>
<template>
    <!-- Header -->
    <header>
        <div class="container navbar">
            <div class="nav-left">
                <figure>
                    <img src="../assets/img/dc-logo.png" alt="Logo">
                </figure>
            </div>
            <div class="nav-right">
                <ul>
                    <li v-for="link in links" :key="link.text" :class="{ 'active': link.current }">
                        <a :href="link.url"> {{ link.text }} </a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>


<style lang="scss" scoped>
header {
    height: 80px;
    background-color: white;
    font-family: "Open Sans Condensed", sans-serif;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;

    .nav-left {
        flex-basis: 40%;

        figure {
            margin: 10px 0;

            img {
                max-width: 50%;
                display: block;
            }
        }
    }

    .nav-right {
        flex-basis: 60%;
        height: 100%;

        ul {
            display: flex;
            justify-content: space-around;
            align-items: center;

            li {
                padding: 27px;

                &.active {
                    color: rgb(2, 130, 249);
                    border-bottom: 4px solid rgb(2, 130, 249);
                }
            }
        }

        a {
            color: black;
            font-weight: bold;
        }
    }
}
</style>