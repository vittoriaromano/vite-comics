<script>
export default{
    name: 'AppMain',
    data(){
        return{
           mainList:[
            {
                image:'/buy-dc-power-visa.svg',
                title:'DIGITAL COMICS'
            },
            {
                image:'/buy-dc-power-visa.svg',
                title:'DIGITAL COMICS'
            },
            {
                image:'/buy-dc-power-visa.svg',
                title:'DIGITAL COMICS'
            },
            {
                image:'/buy-dc-power-visa.svg',
                title:'DIGITAL COMICS'
            },
            {
                image:'/buy-dc-power-visa.svg',
                title:'DIGITAL COMICS'
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
    }
    li{
        display: flex;
        gap: 5px;
        list-style: none;
        color: white;
        padding: 10px;

        img{
            height: 20px;
        }
    }
}


</style>