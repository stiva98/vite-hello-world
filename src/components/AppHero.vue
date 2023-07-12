<script>
    export default {

        data () {
            return {
                bonusImg: '../src/assets/Naruto.jpg',
                nameImg: 'Naruto'
            }
        }

    }

</script>





<template>
    <img :src="bonusImg" :alt="nameImg">
</template>




<style scoped>
img {
    width: 31.25rem;
    height: 15.625rem;
    object-fit: contain;
    margin: 1.25rem auto;
    display: block;
}
</style>