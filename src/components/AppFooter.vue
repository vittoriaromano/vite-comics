<script>
export default{
    name: 'AppFooter'
}
</script>

<template>
    <footer>
        <div class="footer-uno">
            <div>
                <h4>DC COMICS</h4>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    
                </ul>

                <h4>SHOP</h4>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                </ul>
            </div>
            <div>
                <h4>DC</h4>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    
                </ul>
            </div>
            <div>
                <h4>SITES</h4>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>News</li>
                    
                </ul>
            </div>
        </div>
        
        <div class="footer-due">
            <button>SIGN-UP NOW!</button>
            <ul>
                <li>FOLLOW US</li>
                <li><img src="/footer-facebook.png" alt="facebook"></li>
                <li><img src="/footer-twitter.png" alt="twitter"></li>
                <li><img src="/footer-youtube.png" alt="youtube"></li>
                <li><img src="/footer-pinterest.png" alt="pinterest"></li>
                <li><img src="/footer-periscope.png" alt="periscope"></li>
            </ul>
            
        </div>
    </footer>
    
</template>

<style lang="scss" scoped>
@use '../styles/variable.scss';

ul{
        padding: 0;
        list-style: none;
   
    li{
        font-size: 14px;
        color: grey;
        align-items: center; 
    }
}
.footer-uno{
   background-image: url('/footer-bg.jpg');
   padding: 60px;
   color: variable.$third-color;
   display: flex;
   justify-content: baseline;
   align-items: normal;
   padding-left: 10%;
   div{
    margin-right: 60px;
   }
}
.footer-due{
    background-color: variable.$secondary-color;
    padding: 30px;
    padding-left: 10%;
    padding-right: 10%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    ul{
        display: flex;
        align-items: center;
    }
    li{
        color: variable.$primary-color;
        margin: 10px;
    }
    button{
        padding: 15px;
        background-color: transparent;
        border: 2px solid variable.$primary-color;
        color: variable.$third-color;
        &:hover{
            color:variable.$primary-color;
            background-color: variable.$third-color;
        }
    }
}

</style>