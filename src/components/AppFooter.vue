<script>
export default{

    name:"AppFooter"
}
</script>

<template>
    <footer>
        <div class="jumbotrone footer-top">
            <div class="container">
                <div class="columns">
                    <div>
                        <h3>dc comics</h3>
                        <ul>
                            <li>aaaaa</li>
                        </ul>
                        <h3>shop</h3>
                        <ul>
                            <li>aaaaa</li>
                        </ul>
                    </div>
                    <div>
                        <h3>dc</h3>
                        <ul>
                            <li>aaaaaa</li>
                        </ul>
                    </div>
                    <div>
                        <h3>Sites</h3>
                        <ul>
                            <li>aaaa</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="container">
                <div class="box-button">
                    <button>sign-up</button>
                </div>
                <div class="box-other-app">
                    <span>follow us</span>
                    <img src="../assets/img/footer-facebook.png" alt="fb logo">
                    <img src="../assets/img/footer-twitter.png" alt="twitter logo">
                    <img src="../assets/img/footer-youtube.png" alt="you tube logo">
                    <img src="../assets/img/footer-pinterest.png" alt="pinterest logo">
                    <img src="../assets/img/footer-periscope.png" alt="periscope logo">
                </div>
            </div>            
        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer{
    background-color: #303030;
}

div.jumbotrone{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    height: 50vh;

    &>.container{
        display: flex;
        justify-content: space-between;
        height: 100%;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-position: right;
        background-repeat: no-repeat;
        
    }
}

div.footer-top .columns{
    display: flex;
    color: white;
    padding: 1.5rem 0;

    &>div{
       padding-right: 1.5rem;
    }
}

div.footer-bottom>.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.5rem 0;
}

div.box-other-app{
    display: flex;
    align-items: center;

    *{
        padding: 0 0.5rem;
    }
}


</style>