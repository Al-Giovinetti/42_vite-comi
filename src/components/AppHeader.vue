<script>
export default{
    name: "AppHeader",
    data() {
        return {
            ActiveIndex:0,
            categories:
            [
                "characters",
                "comics",
                "movies",
                "tv",
                "games",
                "collectibles",
                "videos",
                "fans",
                "news",
                "shop"
            ]
        }
    },
    methods:{
        changeActiveIndex(index){
            this.ActiveIndex = index
        }
    }    
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
                    <li v-for="(category) in categories">
                        {{ category }}
                    </li>
                </ul>
            </nav>

        </div>
    </header>
    

</template>

<style lang="scss" scoped>
header{
    background-color: white
}

div.container{
    height: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;

        ul{
            display: flex;
        };

        li{
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