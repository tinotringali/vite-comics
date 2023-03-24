<script>

export default{
    name:'AppHeader',
    data() {
        return {
            menuList: [
                {
                    name:'CHARACTERS',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'COMICS',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'MOVIES',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'TV',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'GAMES',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'COLLECTIBLES',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'VIDEOS',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'FANS',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'NEWS',
                    link:'#',
                    target:'_self'
                },
                {
                    name:'SHOP',
                    link:'#',
                    target:'_self'
                },

            ]
        }
    }
}

</script>

<template>
    <header>
        <img src="img/dc-logo.png" alt="logo">
        <nav>
            <ul>
                <li v-for="menu in menuList">
                    <a :href="menu.link" :target="menu.target">{{ menu.name }}</a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
    header{
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 20px;
    }

    img{
        width: 60px;
    }

    ul{
        list-style: none;
        display: flex;
    }

    li{
        a{
            margin-right: .9375rem;
            font-size: 10px;
            text-decoration: none;
            color: #1c1c1c;
            font-weight:bolder;

            &:hover{
                color: #0282f9;
            }
        }
    }
</style>
