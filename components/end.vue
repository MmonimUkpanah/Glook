<template>
<div class="one">
    <div class="hundred">
        <div class="two">
            <img src="~/assets/title.png" class="img-responsive ">
            <div >
                <p>Glook is an amazing agency where you’ll  get the best salon and spa services which is unique.</p>
            <div >
                 <a href=""><img src="~/assets/facebook.png" class="img-responsive " height="30"></a>
            <a href=""><img src="~/assets/twitter.png" class="img-responsive "  height="30"></a>
            <a href=""><img src="~/assets/youtube.png" class="img-responsive "  height="30"></a>
            </div>
            
            </div>
        </div>
        <div>
            <div style="margin-top: 8px">
                <p><strong>Quicklinks</strong> </p>
                <div >
                <a href="#">Home</a> <br>  
                <a href="#">Salons</a> <br>
                <a href="#">About Us</a> <br> 
                <a href="#">Contact Us</a> 
                </div>
                
            </div>
        </div>
        <div >
            <div>
                 <p><strong>Contact Us</strong></p>
                 <p>  +234 534 454 645 <br> Info@glookafrica.com  <br>Uyo, Akwa Ibom State Nigeria.</p>
            </div>
        </div>
        <div >
            <p><a href="">Terms and Conditions</a>
            <br><a href="">Faq</a></p>
        </div>
    
    </div>  
    <footer>
        <div class="three">
            <div>
            <p>All Right Reserved | GLOOK 2020</p>
        </div>
        <div>
            <ul>
                <li>Privacy Policy </li>
                <li>Site Credit </li>
            </ul>
        </div>
        </div>
        
    </footer>  
    
</div>
    
</template>
<style scoped>
a{
    text-decoration: none;
    color: #FFFFFF !important;

}
.hundred{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-gap: 2rem;
    color: #FFFFFF;
    padding: 40px 10px;
    margin-left: 200px;
    margin-right: 200px;

}
.one{
    background: #212121;
}
.two{
    margin-right:35px;
}
li{
    display: inline;
    margin-right: 20px;
    
}
.n9{
    margin-top: 10px;
}
.n8{
    margin-top: 60px;
}
footer{
    background: #000000;
    color: #FFFFFF;
    padding:20px 0px;
    
}
.three{
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 35rem;
    margin-left: 200px;
    margin-right: 200px;
}







@media (max-width: 375px){
    .hundred{
        text-align: center;
        margin-left: 10px;
        margin-right: 10px;
        grid-template-columns: 2fr;
    }
    .three{
        text-align: center;
        margin-left: 10px;
        margin-right: 10px;
        grid-template-columns: 2fr;
        grid-gap: 1rem;
    }
    .two{
    margin-right:0px;
}
}



@media(min-width: 376px) and (max-width: 500px){
    .hundred{
        text-align: center;
        margin-left: 10px;
        margin-right: 10px;
        grid-template-columns: 2fr;
    }
    .three{
        text-align: center;
        margin-left: 10px;
        margin-right: 10px;
        grid-template-columns: 2fr;
        grid-gap: 1rem;
    }
    .two{
    margin-right:0px;
}
}



@media(min-width: 501px) and (max-width: 768px){
    .hundred{
        text-align: center;
        margin-left: 10px;
        margin-right: 10px;
        grid-template-columns: 2fr 2fr;
    }
    .three{
        text-align: center;
        margin-left: 10px;
        margin-right: 10px;
        grid-template-columns:2fr 2fr;
        grid-gap: 1rem;
    }
    .two{
    margin-right:0px;
}

}



@media(min-width: 769px) and (max-width: 1200px){
    .hundred{
        text-align: center;
        margin-left: 10px;
        margin-right: 10px;
        grid-template-columns: 2fr 2fr;
    }
    .three{
        text-align: center;
        margin-left: 10px;
        margin-right: 10px;
        grid-template-columns:2fr 2fr;
        grid-gap: 1rem;
    }
    .two{
    margin-right:0px;
}
}

</style>