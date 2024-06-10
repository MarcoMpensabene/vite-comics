<script >
export default {
    data() {
        return {
            listLink : [
                {
                    id: 1 ,
                    active : false ,
                    content : "character",
                    url : "#"
                },
                {
                    id: 2 ,
                    active : true ,
                    content : "comics",
                    url : "#"
                },
                {
                    id: 3 ,
                    active : false ,
                    content : "movies",
                    url : "#"
                },
                {
                    id: 4 ,
                    active : false ,
                    content : "tv",
                    url : "#" 
                },
                {
                    id: 5 ,
                    active : false ,
                    content : "games",
                    url : "#"
                },
                {
                    id: 6 ,
                    active : false ,
                    content : "collectibles",
                    url : "#"
                },
                {
                    id: 7 ,
                    active : false ,
                    content : "videos",
                    url :"#"
                },
                {
                    id: 8 ,
                    active : false ,
                    content : "fans",
                    url : "#"
                },
                {
                    id: 9 ,
                    active : false ,
                    content : "news",
                    url : "#"
                },
                {
                    id: 10 ,
                    active : false ,
                    content : "shop",
                    url : "#"
                }
            ]
        }
    }
}
</script>

<template>
    <header> 
        <nav>
        
        <div class="header-logo">
            <img src="../assets/img/dc-logo.png" alt="DC-Logo">
        </div>
        <ul>
            <li v-for="link in listLink" :key="link.id">
                <a href="link.url">{{ link.content }}</a>
            </li>
        </ul>
        </nav>
    </header>

</template>

<style scoped>
    nav{
        display: flex;
        width: 60%;
        margin: 0 auto;
        justify-content: space-between;
        padding: 1rem;
    }
    ul{
        display: flex;
        width: 60%;
        li{
            padding: 2rem 1rem 2rem;
            text-transform: uppercase;
            font-size: 13px;
            font-weight: bold;
        }
    }
    header{
        background-color: white;
    }
    img{
        width: 80%;
    }
</style>
