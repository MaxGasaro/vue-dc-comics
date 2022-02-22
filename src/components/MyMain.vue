<template>
    <main>
        <h1>qua inseriamo il content!!</h1>
    </main>
</template>

<script>
export default {
    name: 'MyMain'
}
</script>

<style scoped lang="scss">

@import "../assets/style/variables.scss";

main {
    height: 200px;
    background-color: $mainColor;
    display: flex;
    align-items: center;
    h1 {
        color: $textColor;
    }
}

</style>