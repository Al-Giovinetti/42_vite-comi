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
    </main>

</template>

<style lang="scss" scoped>

main{
    padding: 0 0 2rem;
    background-color: black;
}

p{
    color: white;
    font-weight: bold;
    font-size: 1.5rem;
}

</style>