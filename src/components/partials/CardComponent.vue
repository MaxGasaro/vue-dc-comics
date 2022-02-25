<template>
    <div class="col g-5">
        <img :src="comic.thumb">
        <div class="ms_title text-uppercase">{{comic.series}}</div>
    </div>
</template>

<script>
export default {
    name: 'CardComponent',
    props: {
        'comic': Object 
    }

}
</script>

<style scoped lang="scss">
img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    object-position: top;
    }
.ms_title {
    font-size: 0.8rem;
    color: #fff;
    }
</style>