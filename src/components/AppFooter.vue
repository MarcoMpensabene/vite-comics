<script >

</script>

<template>
    <footer>
        <section >
            <div>
                <h2>Test</h2>
                <ul>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                </ul>
                <h2>TestTitle</h2>
                <ul>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>

                </ul>
            </div>
            <div>
                <h2>TestTitle</h2>
                <ul>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                </ul>
            </div>
            <div>
                <h2>TestTitle</h2>
                <ul>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
                    <li>Testli</li>
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
        margin-right: 4rem;
    }
    section,
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
    li{
        color: #778581;
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