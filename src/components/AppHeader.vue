<script>
export default{
    name: 'AppHeader'
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
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Menu</a></li>
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