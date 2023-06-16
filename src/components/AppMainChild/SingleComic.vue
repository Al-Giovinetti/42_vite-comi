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
    border: 1px red;
    width: calc(100% / 5);
    margin-bottom: 2rem;
}
    div.img-box{
        height: 250px;
        width: 150px;
        margin: auto;

        img{
            height: 100%;
            width: 100%;
            display: block;
            object-fit: cover;
        }
    }

    p{
        text-align: center;
        padding: 1.5rem;
    }


</style>