<template>
    <div class="card">
        <div class="img-box">
            <img :src="comicInfo.thumb" alt="">
        </div>
        <p> {{ comicInfo.series }} </p>
    </div>
</template>

<script>
export default{
    name:"SingleComic",
    props:{
        comicInfo : String
    }

}

</script>

<style lang="scss" scoped>
div.card{
    width: calc(100% / 6 - 1rem);
    margin: 0 0.5rem 1.5rem
}
    div.img-box{
        height: 300px;
        width: 100%;

        img{
            height: 100%;
            width: 100%;
            display: block;
            object-fit: contain;
        }
    }

    p{
        padding-top: 1.5rem;
        color: white;
    }


</style>