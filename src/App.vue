<script>
import AppHeader from "./components/AppHeader.vue";
import AppMainContent from "./components/AppMainContent.vue"
import AppFooter from "./components/AppFooter.vue"
export default {
    components :{
        AppHeader ,
        AppMainContent ,
        AppFooter,
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
    <AppFooter />
</template>

<style lang="scss">
@use './style/general.scss';
</style>
