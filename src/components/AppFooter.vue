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
            <div>
                <ul>
                    <li>FOLLOW US</li>
                    <li><img src="/footer-facebook.png" alt="facebook"></li>
                    <li><img src="/footer-twitter.png" alt="twitter"></li>
                    <li><img src="/footer-youtube.png" alt="youtube"></li>
                    <li><img src="/footer-pinterest.png" alt="pinterest"></li>
                    <li><img src="/footer-periscope.png" alt="periscope"></li>
                </ul>
            </div>
        </div>
    </footer>
    
</template>

<style lang="scss" scoped>

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
   color: white;
   display: flex;
   gap: 60px;
}
.footer-due{
    background-color: rgb(97, 97, 97);
    padding: 30px;
    margin: 0, auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    ul{
        display: flex;
        align-items: center;
    }
    li{
        color: blue;
        margin: 10px;
    }
    button{
        padding: 10px;
        background-color: transparent;
        border: 2px solid blue;
        color: white;
    }
}
</style>