<template>
    <footer>
        <ul>
            <li class="list-title">DC COMICS</li> 
            <li v-for="link in links" :key="link.text">
                {{link.text}}
            </li>
            <li class="list-title">SHOP</li> 
            <li v-for="link in links" :key="link.text">
                {{link.text}}
            </li>
        </ul>
        <ul>
            <li class="list-title">DC</li> 
            <li v-for="link in links" :key="link.text">
                {{link.text}}
            </li>
        </ul>
        <ul>
            <li class="list-title">SITES</li> 
            <li v-for="link in links" :key="link.text">
                {{link.text}}
            </li>
        </ul>
    </footer>
</template>

<script>
export default {
    data() {
        return {
            links: [
                {
                    text: 'characters',
                },
                {
                    text: 'movies',
                },
                {
                    text: 'comics',
                },
                {
                    text: 'tv',
                },
                {
                    text: 'games',
                },
                {
                    text: 'videos',
                },
                {
                    text: 'news',
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">

@import "../assets/style/variables.scss";

    footer {
        height: 400px;
        background-image: url('../assets/img/footer-bg.jpg');
        display: flex;
        ul {
            list-style: none;
            .list-title {
                color: #fff;
                padding: 10px 0;
            }
            li {
                text-transform: capitalize;
                color: $textFooterColor;
            }
        }
    }
</style>