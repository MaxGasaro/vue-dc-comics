<template>
    <header>
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="logo dc comics">
        </div>
        <nav>
            <ul class="navbar">
                <li class="active" v-for="link in links" :key="link.text">
                    {{link.text}}
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    data() {
        return {
            links: [
                {
                    text: 'CHARACTERS'
                },
                {
                    text: 'COMICS'
                },
                {
                    text: 'MOVIES'
                },
                {
                    text: 'TV'
                },
                {
                    text: 'GAMES'
                },
                {
                    text: 'COLLECTIBLES'
                },
                {
                    text: 'VIDEO'
                },
                {
                    text: 'FANS'
                },
                {
                    text: 'NEWS'
                },
                {
                    text: 'SHOP'
                }
            ]
        }
    },
}
</script>

<style scoped lang="scss">

@import '../assets/style/variables.scss';

header {
    height: 70px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    max-width: 1180px;
    .logo {
        height: 100%;
        img {
            height: 100%;
        }
    }
    
    nav {
        .navbar {
            list-style: none;
            li {
                display: inline-block;
                padding: 0 10px;
            }
        }
    }

}


</style>