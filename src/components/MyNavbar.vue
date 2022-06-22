<template>
    <nav>
    <img src="../assets/img/dc-logo.png" alt="">
    <ul>
        <li v-for="(item, i) in listItem" :key="i">{{item.myListItem}}</li>
    </ul>
    </nav>
</template>

<script>
export default {
  name: 'MyNavbar',
    data() {
        return {
            
            listItem: [
                {
                    myListItem: 'CHARACTERS',
                },          
                {
                    myListItem: 'COMICS',
                },          
                {
                    myListItem: 'MOVIE',
                },            
                {
                    myListItem: 'TV',
                },            
                {
                    myListItem: 'GAMES',
                },            
                {
                    myListItem: 'COLLECTIBLES',
                },            
                {
                    myListItem: 'VIDEOS',
                },            
                {
                    myListItem: 'FANS',
                },            
                {
                    myListItem: 'NEWS',
                },            
                {
                    myListItem: 'SHOP',
                }
            ]
        }
    }
}
</script>

<style>

    nav img {
        height: 60px;
        margin: 1rem;
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