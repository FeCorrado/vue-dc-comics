<template>
    <div class="boxbb">
        <div class="fumetti-box">
            <div v-for="(fumetto, index) in fumetti" :key="index" class="card">
                <div class="img-fumetto">
                    <img :src="fumetto.thumb" alt="">
                </div>
                <h5>{{fumetto.series}}</h5>
            </div>
        </div>
        <div class="load">LOAD MORE</div>
    </div>
</template>

<script>
export default {
    props: {
        fumetti: Array
    }
}
</script>

<style lang="scss">
@import '../style/comics.scss'
</style>