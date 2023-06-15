<script>
export default{

    name:"AppFooter"
}
</script>

<template>
    <footer>
        <div class="jumbotrone">
            <div class="footer-top">
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
</style>