<script>
export default{
    name: 'AppHeader',
    data(){
        return{
            menulist:[
                {
                    name: 'CHARACTERS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'COMICS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'MOVIES',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'TV',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'GAMES',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'COLLECTIBLES',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'VIDEOS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'FANS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'NEWS',
                    link: '#',
                    target: '_self'
                },
                {
                    name: 'SHOP',
                    link: '#',
                    target: '_self'
                }
            ]
        }
    }
}
</script>

<template>
    <header>
        <!-- LOGO -->
        <div class="logo">
            <img src="/dc-logo.png" alt="logo dc">
        </div>
        <!-- MENU -->
        
            <nav>
                <ul>
                    <li v-for="menu in menulist">
                        <a :href="menu.link" target="menu.target">{{ menu.name }}</a>
                    </li>
                    
                </ul>
            </nav>
        
    </header>
</template>

<style lang="scss" scoped>
@use '../styles/variable.scss';

.logo{
    img {
        height: 60px;
    }
}
header{
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 30px;
}
nav{
    ul{
        margin: 0;
        list-style: none;
        display: flex;
    }
    li{
        a {
            text-decoration: none;
            font-size: 12px;
            display: inline-block;
            padding: 18px;
            color: black;

            &:hover {
               color: variable.$primary-color; 
            }
        }
    }
}
</style>