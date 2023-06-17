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
                        <h2>dc comics</h2>
                        <ul>
                            <li> <a href="#">Characters</a> </li>
                            <li> <a href="#">Comics</a> </li>
                            <li> <a href="#">Movies</a> </li>
                            <li> <a href="#">Tv</a> </li>
                            <li> <a href="#">Games</a> </li>
                            <li> <a href="#"> Videos</a> </li>
                            <li> <a href="#">News</a> </li>
                        </ul>
                        <h2>shop</h2>
                        <ul>
                            <li> <a href="#">Shop DC</a> </li>
                            <li> <a href="#">Shop DC Collectibles</a> </li>
                        </ul>
                    </div>
                    <div>
                        <h2>dc</h2>
                        <ul>
                            <li> <a href="#">Terms Of Use</a> </li>
                            <li> <a href="#">Privacy policy(New)</a> </li>
                            <li> <a href="#">Ad Choices</a> </li>
                            <li> <a href="#">Advertising</a> </li>
                            <li> <a href="#">Jobs</a> </li>
                            <li> <a href="#">Subscriptions</a> </li>
                            <li> <a href="#">Talent Workshops</a> </li>
                            <li> <a href="#">CPSC Certificates</a> </li>
                            <li> <a href="#">Ratings</a> </li>
                            <li> <a href="#">Shop Help</a> </li>
                            <li> <a href="#">Contact Us</a> </li> 
                        </ul>
                    </div>
                    <div>
                        <h2>Sites</h2>
                        <ul>
                            <li> <a href="#">DC</a> </li>
                            <li> <a href="#">MAD Magazine</a> </li>
                            <li> <a href="#">DC Kids</a> </li>
                            <li> <a href="#">DC Universe</a> </li>
                            <li> <a href="#">DC Power Visa</a> </li>
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

    >.container{
        display: flex;
        justify-content: space-between;
        height: 100%;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-position: right;
        background-repeat: no-repeat;
        background-size: 40%;
        
    }
}

div.footer-top .columns{
    display: flex;
    color: white;
    padding: 1.5rem 0;

    >div{
       padding-right: 1.5rem;
    }

    h2{
        padding-bottom: 0.5rem;
        text-transform: uppercase;
    }

    li{
        font-size: 0.8rem;
        padding-bottom: 0.5rem;
    }

    a{
        color: white;
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