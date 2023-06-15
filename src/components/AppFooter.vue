<script>
export default{

    name:"AppFooter"
}
</script>

<template>
    <footer>
        <div class="jumbotrone footer-top">
            <div class="container">
                <div class="column">
                    <h3>dc comics</h3>
                    <ul>
                        <li>aaaaa</li>
                    </ul>
                    <h3>shop</h3>
                    <ul>
                        <li>aaaaa</li>
                    </ul>
                </div>
                <div class="column">
                    <h3>dc</h3>
                    <ul>
                        <li>aaaaaa</li>
                    </ul>
                </div>
                <div class="column">
                    <h3>Sites</h3>
                    <ul>
                        <li>aaaa</li>
                    </ul>
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
    background-color: grey;
}

div.jumbotrone{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
}

div.footer-top>.container{
    display: flex;
    color: white;
    padding: 1.5rem 0;

    & .column{
       padding-right: 1.5rem;
    }
}

div.footer-bottom>.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 0;
}

div.box-other-app{
    display: flex;
    align-items: center;

    & *{
        padding: 0 0.5rem;
    }
}




</style>