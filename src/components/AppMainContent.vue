<script >
import MainListArticle from "./MainListArticle.vue"
export default {
    components :{
        MainListArticle ,
    },
    data() {
        return {
            
            }
        }
}
</script>

<template>
    <main>
        <section class="jumbo-tron">
        </section>
        
        <MainListArticle />
        <div>
            <button>Load More</button>
        </div>
    </main>
</template>

<style lang="scss" scoped>
main{
    width: 100%;
    section.jumbo-tron{
        background-image: url("../assets/img/jumbotron.jpg");
        height: 400px;
        margin-bottom: 2rem;
    }
    div{
        width: 100%;
        margin-bottom: 2rem;
        button{
            margin: 0 auto;
            display:block;
            padding: .5rem 2rem .5rem;
            background-color: #0282f9;
            color: white;
            border: none;
            text-transform: uppercase;
            font-weight: bolder;
        }
    }
}
</style>