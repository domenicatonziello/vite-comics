<script>
export default {
    name: 'AppHeader'
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
                    <li class="active"> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                    <li> <a href="#"> Link </a> </li>
                </ul>
            </div>
        </div>
    </header>
</template>


<style scoped>
header {
    height: 80px;
    background-color: white;
    font-family: "Open Sans Condensed", sans-serif;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.navbar .nav-left {
    flex-basis: 40%;
}

.nav-left figure {
    margin: 10px 0;
}

.nav-left img {
    max-width: 20%;
    display: block;
}

.navbar .nav-right {
    flex-basis: 60%;
    height: 100%;
}

.nav-right ul {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.nav-right li {
    padding: 27px;
}

.nav-right li.active {
    color: rgb(2, 130, 249);
    border-bottom: 4px solid rgb(2, 130, 249);
}

.nav-right a {
    color: black;
    font-weight: bold;
}
</style>