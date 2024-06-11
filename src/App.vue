<script>
import AppHeader from "./components/AppHeader.vue";
import AppMainContent from "./components/AppMainContent.vue"
import AppFooter from "./components/AppFooter.vue"
import AppMerch from "./components/AppMerch.vue"
export default {
    components :{
        AppHeader ,
        AppMainContent ,
        AppFooter,
        AppMerch
    },
    data() {
        return {
            
            }
        }
}
</script>

<template>
    <AppHeader />
    <AppMainContent />
    <AppMerch />
    <AppFooter />
    
</template>

<style lang="scss">
@use './style/general.scss';
</style>
