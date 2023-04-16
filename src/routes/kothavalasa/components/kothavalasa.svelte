<nav class="navbar bg-[#050a2f]">
    <div class="content">
        <div id="logo" class="flex justify-between items-center">
            <a href="index.html" class="text-2xl font-[Popp] cursor-pointer">
                <img src="/logo.png" class="h-14 mt-[13%] inline" alt="">
            </a>
            <div id="logo-name">
                <a href="#head"><p class="text-2xl text-white font-bold">PROPERTIES & DEVELOPERS</p>
                <p id="home" class="text-xl text-white font-extralight">A HOME CHANGES EVERYTHING</p></a>
            </div>
            
        </div>
      <ul id="nav-icons" class="menu-list">
        <div class="icon cancel-btn">
          <i class="fa-sharp fa-solid fa-xmark"></i>
        </div>
        <li id="a">
            <a href="#head">HOME</a>
        </li>
        <li id="a">
            <a href="#about">ABOUT</a>
        </li>
        <li id="a">
            <a href="#locations">LOCATIONS</a>
        </li>
        <li id="a">
            <a href="#map">CONTACT US</a>
        </li>
        <li>
            <a id="book" href="#map" class="bg-yellow-500 text-white font-[Poppins] rounded hover:bg-[#fff] hover:text-black transition-all duration-500">BOOK NOW</a>
        </li>
      </ul>
      <div class="icon menu-btn">
        <i class="fa-solid fa-bars"></i>
      </div>
    </div>
</nav>







<section id="imgs" class=" h-[120vh]">
    
    <div class="container">
        <h1 id="head-text" class="text-[#050a2f] text-8xl text-center leading-[200%] font-bold">KOTHAVALASA</h1>
        <div class="wrapper">
            <img src="6.jpg" alt="">
            <img src="7.jpg" alt="">
            <img src="8.jpg" alt="">
            <img src="9.jpg" alt="">
            <img src="10.jpg" alt="">
            <img src="11.jpg" alt="">
            <img src="12.jpg" alt="">
        </div>
    </div>

</section>


<section id="sri-features" class="h-[100vh]">
    <div>
        <h1 id="head-text" class="text-[#050a2f] text-8xl leading-[300%] text-center mt-0 font-bold">FEATURES</h1> 
    </div>
    <div id="features" class="text-[#050a2f] text-center text-2xl leading-[230%] font-bold">
        <ul>
            <li>We are a full-service real estate company committed to helping</li>
            <li>We are a full-service real estate company committed to helping</li>
            <li>We are a full-service real estate company committed to helping</li>
            <li>We are a full-service real estate company committed to helping</li>
            <li>We are a full-service real estate company committed to helping</li>
        </ul>
    </div>
</section>



<style>
           
           *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
#features ul li{
    letter-spacing: 2px;
}
.menu-list #book{
    padding: 8px 20px;
    border-radius: 5px;
}
.container{
    width: 140vmin;
    position: absolute;
    transform: translate(-50%,-50%);
    top: 60%;
    left: 50%;
    overflow: hidden;
    border: 10px solid #ffffff;
    border-radius: 8px;
    box-shadow: 10px 25px 30px rgba(30,30,200,0.3);
}
.wrapper{
    width: 100%;
    display: flex;
    animation: slide 15s infinite;
}
@keyframes slide{
    0%{
        transform: translateX(0);
    }
    25%{
        transform: translateX(0);
    }
    30%{
        transform: translateX(-100%);
    }
    50%{
        transform: translateX(-100%);
    }
    55%{
        transform: translateX(-200%);
    }
    75%{
        transform: translateX(-200%);
    }
    80%{
        transform: translateX(-300%);
    }
    100%{
        transform: translateX(-300%);
    }
}
img{
    width: 100%;
}
@media (max-width:640px){
    .container{
        width: 90vmin;
    }
}
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,900&display=swap'); 
    @import url('https://fonts.googleapis.com/css2?family=Anton&display=swap');

nav{
    position: fixed;
    width: 100%;
    top: 0px;
}


    #home{
    letter-spacing: 1.5px;
}
#nav-icons #a a{
    position: relative;
			text-decoration: none;
			color: white; /* change color as desired */
}
#nav-icons #a a::after{
    content: "";
			position: absolute;
			left: 0;
			bottom: -8px; /* adjust distance from text as desired */
			height: 3px;
			width: 0;
			background-color: #d89e37; /* change color as desired */
			transition: width 0.2s ease;
}
#nav-icons #a a:hover::after{
    width: 100%;
}
    
    #nav-icons a{
        overflow: hidden;
        transition: 1s;
    }
    #nav-icons .black a{
        background: #000;
    }
    @media screen and (max-width:3000px) and (min-width:1800px){
        
    }
    @media screen and (max-width:1250px){
        
    }
    @media screen and (max-width:1070px){
        #nav-icons a{
            font-size: 15px;
        }
        
    }
    @media screen and (max-width:967px){
        #logo-name a p{
            font-size: 15.7px;
        }
    }
    @media screen and (max-width:960px){
        #features{
            font-size: 20px;
        }
    }
    @media screen and (max-width:951px){
        #logo-name a p{
            font-size: 13px;
        }
    }
    @media screen and (max-width:920px) and (min-width:768px){
        #logo-name a p{
            font-size: 10.3px;
        }
        #nav-icons a{
            font-size: 10.3px;
        }
        
    }
    @media screen and (max-width:850px){
        #logo-img a img{
            width: 10vw;
        }
    }
    @media screen and (max-width:830px){
        #features{
            font-size: 15px;
        }
    }
    @media screen and (max-width:750px){
        #logo-img a img{
            width: 12vw;
        }
    }
    @media screen and (max-width:768px){
        
        #logo-name{
            display: none;
        }
        #logo a img{
            margin-top: 0px;
        }
    }
    @media screen and (max-width:676px){
        #logo-img a img{
            width: 15vw;
        }
        #features{
            font-size: 13px;
        }
    }
    @media screen and (max-width:615px){
        #nav-icons{
            display: none;
        }
        
    }
    @media (max-width:590px){
        #head-text{
            font-size: 50px;
        }
    }
    @media screen and (max-width:560px){
        #logo-img a img{
            width: 25vw;
        }
    }
    @media (max-width:435px){
        #head-text{
            font-size: 40px;
        }
    }
    @media (max-width:585px){
        #features{
            font-size: 10px;
        }
        .container{
            top: 40%;
        }
        #imgs{
            height: 70vh;
        }
        #sri-features{
            height: 70vh;
        }
    }
    @media (max-width:470px){
        #features{
            font-size: 9px;
        }
    }
   
    @media screen and (max-width:350px){
        #logo-name a p{
            font-size: 10px;
        }
    }
    @media screen and (max-width:330px){
        #logo-name a p{
            font-size: 10px;
        }
        
    }
    .navbar{
    /* background-color: rgb(14, 14, 14); */
    position: fixed;
    width: 100%;
    z-index: 5;
    /* background: #1b1b1b; */
    transition: all 0.5s ease-in-out;   
}
.content{
    max-width: 1450px;
    
    margin: auto;
    /* padding: 0px 30px; */
    display: flex;
    justify-content: space-between;
    height: 13vh;
    align-items: center;
}
.menu-list{
    display: flex;
}
.navbar .logo a{
    color: aliceblue;
    font-size: 30px;
}
.menu-list li a{
    color: aliceblue;
    font-size: 20px;
    margin-left: 25px;
    transition: all 0.4s ease-in-out;
}
.menu-list li a:hover{
    color: black;
}
.icon{
    color: #fff;
    cursor: pointer;
    font-size: 20px;
    display: none;
}
.icon.cancel-btn{
   position: absolute;
   right: 30px;
   top: 20px;
}
</style>