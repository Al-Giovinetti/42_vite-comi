<script>
import MainContainer from './AppMainChild/MainContainer.vue';
export default{
    name: "AppMain",
    components:{
    MainContainer
}
}

</script>

<template>
    <main>
        <MainContainer class="container"/>
        <div class="shop">
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="buy1">
                <span>digital comics</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="buy2">
                <span>dc merchandise</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="buy3">
                <span>subscriptions</span>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="buy4">
                <span>comic shop locator</span>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="buy5">
                <span>dc power visa</span>
            </div>
        </div>
    </main>

</template>

<style lang="scss" scoped>

main{
    background-color: black;
}

.shop{
    background-color: blue;
    color: white;
    margin-top: 2rem;
    display: flex;
    justify-content: center;
    padding: 2rem 0;

    >div{
        display: flex;
        padding: 0 1rem;
    }

    img{
        height: 50px;
        display: block;
    }

    span{
        padding: 1rem;
        line-height: 100%;
        align-self: center;
        text-transform: uppercase;
        font-size: 0.8rem;
    }
}

</style>