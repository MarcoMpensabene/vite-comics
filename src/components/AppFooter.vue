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
                    SIGN 
                </button>
                <ul>
                    <li>
                        TEST
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
        padding: 2rem 0 2rem;
    }
    nav{
        background-color: #303030;
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
</style>