<template>
    <nav>
    <img src="../assets/img/dc-logo.png" alt="">
    <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIE</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>






    </ul>
    </nav>
</template>

<script>
export default {
  name: 'MyNavbar',

}
</script>

<style>

    nav img {
        height: 60px;
    }

    nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    ul {
        display: flex;
    }

    li {
        list-style: none;
        padding: 1rem;
    }



</style>