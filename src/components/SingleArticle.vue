<script >
export default {
    data() {
        return {
            
            }
        },
    props :{
        singleComics : {
            type : Object , 
            required : true
        }
    },
}
</script>

<template>
    <article >
        <img :src="singleComics.thumb" :alt="singleComics.series">
        <h4>
            {{ singleComics.series }}
        </h4>
    </article>
</template>

<style lang="scss" scoped>
    article{
                width: calc((100% / 6) - 2rem);
                margin-right: 2rem;
                margin-bottom: .5rem;
                img{
                    width: 100%;
                    height: 80%;
                    margin-bottom: .5rem;
                }
                h4{
                    font-size: smaller;
                    text-transform: uppercase;
                }
            }
</style>