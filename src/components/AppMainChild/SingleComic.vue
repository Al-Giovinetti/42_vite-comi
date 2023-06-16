<template>
    <div>
        <img :src="comicInfo.thumb" alt="">
    </div>
    <p>{{ comicInfo.series }}</p>
    

</template>

<script>
export default{
    name:"SingleComic",
    props:{
        comicInfo : String
    }

}

</script>

<style lang="scss">

</style>