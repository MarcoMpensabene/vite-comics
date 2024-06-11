<script >
export default {
    data() {
        return {
            merchList : 
            [
                {
                    id: 1 ,
                    src : "../assets/img/buy-comics-digital-comics.png",
                    content : "Digital Comics",
                },
                {
                    id: 2 ,
                    src : "../assets/img/buy-comics-merchandise.png",
                    content : " DC Merchandise",
                },
                {
                    id: 3 ,
                    src : "../assets/img/buy-comics-subscriptions.png",
                    content : "Subscriptions",
                },
                {
                    id: 4 ,
                    src : "../assets/img/buy-comics-shop-locator.png",
                    content : "Comic Shop Locator",
                },
                {
                    id: 5 ,
                    src : "../assets/img/buy-dc-power-visa.svg",
                    content : "DC power Visa",
                },
            ]
            }
        },
        methods:{
            getImagePath : function (img) {
                return new URL(img , import.meta.url).href;
            }
        }
}
</script>

<template>
    <section>
        <div class="merch">
            <div v-for="item in merchList" :key="item.id">
                <img :src="getImagePath(item.src)" :alt="item.content">
                <p>{{ item.content }}</p>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    section{
        background-color: #0282f9;
        width: 100%;
        display: flex;
    }
    div.merch{
        width: 70%;
        display: flex;
        margin: 0 auto;
        justify-content: space-between;
        padding: 4rem;
        img{
            width: 40px;
            margin-right: 1rem;
        }
        div{
            display: flex;
            p{
                align-self: center;
                color: white;
                text-transform: uppercase;
            }
        }
    }
</style>