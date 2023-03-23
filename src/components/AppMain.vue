<script>
export default{
    name: 'AppMain',
    data(){
        return{
           mainList:[
            {
                image:'/buy-comics-digital-comics.png',
                title:'DIGITAL COMICS'
            },
            {
                image:'/buy-comics-merchandise.png',
                title:'DC MERCHANDISE'
            },
            {
                image:'/buy-comics-subscriptions.png',
                title:'SUBSCRIPTION'
            },
            {
                image:'/buy-comics-shop-locator.png',
                
                title:'COMIC SHOP LOCATOR'
            },
            {
                image:'/buy-dc-power-visa.svg',
                title:'DC POWER VISA'
            }
           ]
        }
    }
}
</script>

<template>
    <main>
        <!-- CONTENUTO -->
    <div class="main-one">
   <span> --> CONTENT GOES HERE </span>
    </div>
    <!-- LINK -->
    <div class="main-two">
        <ul>
            <li v-for="items in mainList">
                <img :src="items.image" alt="image">
                <span>{{items.title}}</span>
            </li>
            
        </ul>
    </div>

    </main>
    
</template>

<style lang="scss" scoped>
@use '../styles/variable.scss';

div .main-one{
    background-color: black;
    padding: 60px;
    span{
        color: white;
    }
}
div .main-two{
    background-color: variable.$primary-color;
    padding: 60px;
    ul{
        display: flex;
        justify-content: center;
    }
    li{
        display: flex;
        justify-content: center;
        align-items: center;
        list-style: none;
        color: variable.$third-color;
        padding: 10px;
        img{
            height: 40px;
            margin-right: 5px;
        }
    }
}
</style>