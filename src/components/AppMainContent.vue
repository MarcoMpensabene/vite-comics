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
        <div>
            <MainListArticle />
        </div>
    </main>
</template>

<style scoped>
main{
    div{
        color: white;
        width: 60%;
        margin: 0 auto;
    }
    section.jumbo-tron{
        background-image: url("../assets/img/jumbotron.jpg");
        height: 400px;
    }
}
</style>