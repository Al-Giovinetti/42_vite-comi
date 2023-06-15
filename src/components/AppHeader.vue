<script>
export default{
    name: "AppHeader"
}

</script>

<template>
    <header>
        <div class="container">
            <div class="box-img">
                <img src="../assets/img/dc-logo.png" alt="DC logo">
            </div>
            <nav>
                <ul>
                    <li><a href="#">characters</a></li>
                    <li><a href="#">comics</a></li>
                    <li><a href="#">movies</a></li>
                    <li><a href="#">tv</a></li>
                    <li><a href="#">games</a></li>
                    <li><a href="#">collectibles</a></li>
                    <li><a href="#">videos</a></li>
                    <li><a href="#">fans</a></li>
                    <li><a href="#">news</a></li>
                    <li><a href="#">shop</a></li>
                </ul>
            </nav>

        </div>
    </header>
    

</template>

<style lang="scss">
header{
    background-color: red;
}

div.container{
    display: flex;
    justify-content: space-between;

        & ul{
            display: flex;
        };

        & li{
            border-bottom: 3px solid black;
            padding:0 0.5rem 2rem;
            margin: 0 0.5rem;
        }
}

div.box-img{
    padding: 0.5rem 0;

    img{
        height: 80px;
    }
}

nav{
    align-self: flex-end;
}

</style>