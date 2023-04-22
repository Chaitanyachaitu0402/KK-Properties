    
    
    
    <!--Navbar-->

    
        <section class="bg-[#050a2f]" id="head" style="background-image: url(/homebg.png); background-size: cover; height: 110vh; background-position: 50%; background-attachment: fixed;">
            <nav class="bg-[#050a2f] h-[13vh] p-5 md:flex md:items-center md:justify-between sticky">
              <div id="logo" class="flex justify-between items-center">
                    <a href="index.html" class="text-2xl font-[Popp] cursor-pointer">
                        <img src="/logo.png" class="h-14 mt-[13%] inline" alt="">
                    </a>  
                    <div id="logo-name">
                        <a href=""><p class="text-2xl text-white font-bold">PROPERTIES & DEVELOPERS</p>
                        <p id="home" class="text-xl leading-3 text-white font-extralight">A HOME CHANGES EVERYTHING</p></a>
                    </div>
                    
                </div>
                <ul id="nav-icons" class="md:flex md:items-center z-[-1] md:z-auto md:static absolute w-full left-0 md:w-auto md:py-0 py-0 md:pl-0 pl-7 md:opacity-100 opacity-0 top-[-400px] transition-all ease-in duration-500">
                    <li id="a" class="mx-4 my-6 md:my-0">   
                        <a href="#head" class="text-xl text-white duration-500">HOME</a>
                    </li>
                    <li id="a" class="mx-4 my-6 md:my-0">
                        <a href="#heading" class="text-xl text-white duration-500">ABOUT</a>
                    </li>
                    <li id="a" class="mx-4 my-6 md:my-0">
                        <a href="#locations" class="text-xl text-white duration-500">LOCATIONS</a>
                    </li>
                    <li id="a" class="mx-4 my-6 md:my-0">
                        <a href="#map" class="text-xl text-white duration-500">CONTACT US</a>
                    </li>
                    <li>
                        <a href="#map" class="px-6 py-2 mx-4 bg-yellow-500 text-white font-[Poppins] rounded hover:bg-[#fff] hover:text-black transition-all duration-500">BOOK NOW</a>
                    </li>
                </ul>
            </nav>
            <div id="head-text" class="text-9xl relative top-[34%] ml-[10%]">
                <div>
                    <h1 class="text-white"><span class="text-[#d89e37]">HOME</span> IS</h1>
                    <h1 class="text-white">WHERE OUR</h1>
                    <h1 class="text-white">STORY <span class="text-[#d89e37]">BEGINS</span>•••</h1>
                </div>
            </div>
        </section>
        
          
          
          <!--Head Text-->

          <section class="bg-[#050a2f] h-[100vh] items-center">
            <div class="bg-[#050a2f]">
                
            </div>
          </section>
        <section id="head" style="background-image: url(/h.jpg); background-size: cover; height: 110vh; background-position: 50%; background-attachment: fixed;">
        </section>
    
      


<style>
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
    #navbar{
        font-family: 'Poppins', sans-serif;
    }
    #head-text{
        font-family: 'Anton', sans-serif;
    }
    #nav-icons a{
        overflow: hidden;
        transition: 1s;
    }
    #nav-icons .black a{
        background: #000;
    }
    @media screen and (max-width:3000px) and (min-width:1800px){
        #nav{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }
        #head-text{
            font-size: 200px;
        }
    }
    @media screen and (max-width:1250px){
        #head-text{
            font-size: 100px;
        }
    }
    @media screen and (max-width:1070px){
        #nav-icons a{
            font-size: 15px;
        }
        #head-text{
            font-size: 100px;
        }
    }
    @media screen and (max-width:967px){
        #logo-name a p{
            font-size: 15.7px;
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
        #head-text{
            font-size: 90px;
            
        }
    }
    @media screen and (max-width:850px){
        #logo-img a img{
            width: 10vw;
        }
    }
    
    @media screen and (max-width:750px){
        #logo-img a img{
            width: 12vw;
        }
    }
    @media screen and (max-width:768px){
        #head-text{
            font-size: 90px;
        }
        #logo-name{
            display: none;
        }
        #logo a img{
            margin-top: 0px;
        }
    }
    @media screen and (max-width:675px){
        #logo-img a img{
            width: 15vw;
        }
    }
    @media screen and (max-width:560px){
        #logo-img a img{
            width: 25vw;
        }
    }
    @media screen and (max-width:470px){
        #head-text{
            font-size: 75px;
            
        }
    }
    @media screen and (max-width:425px){
        #head-text{
            font-size: 75px;
            top: 40%;
        }
    }
    @media screen and (max-width:370px){
        #head-text{
            font-size: 70px;
           top: 50%;
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
        #head-text{
            font-size: 60px;
        }
    }
</style>