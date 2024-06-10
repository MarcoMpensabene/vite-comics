<script >
export default {
    data() {
        return {
            dcComicsLinks : [ "Characters" , "Comics" , "Movies" , "TV" , "Games" , "Videos" , "News"] , 
            shopLinks : [ " Shop DC" , "Shop DC Collectibles"] , 
            dcLinks : [ "Privacy policy(new)" , "Ad Choices" ,"Advertising" , "Jobs" , "Subscriptions","Talent Workshops" , "CPSC Certificates" , "Ratings" , "Shop Help" , "Contact Us"] , 
            sitesLinks : [ "MAD Magazine" ,"DC Kids" ,"DC Universe" ,"DC Power Visa"] 
        }
    }
}
</script>

<template>
    <footer>
        <section >
            <div>
                <h2>dc comics</h2>
                <ul>
                    <li v-for="(link , index) in dcComicsLinks" :key="index" >
                        <a href="">{{ link }}</a>
                    </li>
                </ul>
                <h2>shop</h2>
                <ul>
                    <li v-for="(link , index) in shopLinks" :key="index" >
                        <a href="">{{ link }}</a>
                    </li>
                </ul>
            </div>
            <div>
                <h2>dc</h2>
                <ul>
                    <li v-for="(link , index) in dcLinks" :key="index" >
                        <a href="">{{ link }}</a>
                    </li>
                </ul>
            </div>
            <div>
                <h2>sites</h2>
                <ul>
                    <li v-for="(link , index) in sitesLinks" :key="index" >
                        <a href="">{{ link }}</a>
                    </li>
                </ul>
            </div>
        </section>

        <nav>
            <div class="footer-nav">
                <button>
                    SIGN-UP NOW!
                </button>
                <ul class="icons">
                    <li >
                        <h2 id="follow">Follow Us</h2>
                    </li>
                    <li>
                        <img src="../assets/img/footer-facebook.png" alt="">
                    </li>
                    <li>
                        <img src="../assets/img/footer-twitter.png" alt="">
                    </li>
                    <li>
                        <img src="../assets/img/footer-youtube.png" alt="">
                    </li>
                    <li>
                        <img src="../assets/img/footer-pinterest.png" alt="">
                    </li>
                    <li>
                        <img src="../assets/img/footer-periscope.png" alt="">
                    </li>
                </ul>
            </div>
        </nav>
    </footer>
</template>

<style scoped>
    footer{
        background-image: url("../assets/img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
    }
    section div{
        margin-right: 5rem;
    }
    section{
        display: flex;
        width: 60%;
        margin: 0 auto;
        padding: 2rem 0 1.5rem;
    }
    div.footer-nav
    {
        display: flex;
        width: 60%;
        margin: 0 auto;
        padding: 2rem 0 1.5rem;
        justify-content: space-between;
    }
    nav{
        background-color: #303030;

    }
    button{
        border: #0080e5 solid 2px;
        color: white;
        background-color: transparent;
        padding: 1rem;
        align-self: center;
        font-weight: bold;
    }
    h2{
        color: white;
        text-transform: uppercase;
        margin-bottom: 1rem;
    }
    a{
        color: #778581;
        font-size: 11px;
    }
    ul{
        margin-bottom: 1rem;
    }
    .icons{
        display: flex;
        li{
            margin-left: 1rem;
            align-self: center;
        }
    }
    #follow{
        color: #0080e5;
        text-transform: uppercase;
        font-weight: bolder;
        padding-top: 0.7rem;
    }

</style>