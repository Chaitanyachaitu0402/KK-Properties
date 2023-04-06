<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KK Properties & Developers</title>
</head>
<body>
    
    <!--Navbar-->

    <section id="head">
        <nav id="navbar" class="">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
              <div id="nav" class="flex items-center justify-between h-16">
                <div id="logo-img" class="flex items-center">
                  <a href="#" class="text-white text-xl font-bold">
                    <img class="w-[8vw]" src="logo.png" alt="">
                  </a>
                  <div id="logo-name" class="text-white">
                    <a href=""><p class="font-bold text-lg">PROPERTIES & DEVELOPERS</p></a>
                    <a href=""><p class="text-base">A HOME CHANGES EVERYTHING</p></a>
                </div>
                </div>
                <div class="hidden md:block">
                  <div id="nav-icons" class="ml-10 flex items-baseline">
                    <a href="#" class="px-5 py-2 rounded-md text-lg font-medium text-white hover:bg-gray-700">HOME</a>
                    <a href="#" class="px-5 py-2 rounded-md text-lg font-medium text-white hover:bg-gray-700">ABOUT</a>
                    <a href="#" class="px-5 py-2 rounded-md text-lg font-medium text-white hover:bg-gray-700">LOCATIONS</a>
                    <a href="#" class="px-5 py-2 rounded-md text-lg font-medium text-white hover:bg-gray-700">CONTACT US</a>
                    <a href="#" class="px-5 py-2 rounded-md text-lg font-medium text-white bg-[#d89e37]">BOOK NOW</a>
                </div>
                </div>
                <div class="-mr-2 flex md:hidden">
                  <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none focus:bg-gray-700 focus:text-white transition duration-150 ease-in-out" aria-label="Main menu" aria-expanded="false">
                    <svg class="h-6 w-6" stroke="currentColor" fill="none" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                  </button>
                </div>
              </div>
            </div>
          
            <div class="hidden md:hidden">
              <div class="px-2 pt-2 pb-3 sm:px-3">
                <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-white hover:bg-gray-700">Home</a>
                <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-white hover:bg-gray-700">About</a>
                <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-white hover:bg-gray-700">Contact</a>
              </div>
            </div>
          </nav>
          
          
          <!--Head Text-->

          <div id="head-text" class="text-9xl mt-[14%] ml-[10%]">
            <div>
                <h1 class="text-white"><span class="text-[#d89e37]">HOME</span> IS</h1>
                <h1 class="text-white">WHERE OUR</h1>
                <h1 class="text-white">STORY <span class="text-[#d89e37]">BEGINS</span>•••</h1>
            </div>
        </div>
    </section>
      
      

        
      
      
</body>
</html>


<style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,900&display=swap'); 
    @import url('https://fonts.googleapis.com/css2?family=Anton&display=swap');
    #head{
        background: url(homebg.png);
        background-size: cover;
        height: 100vh;
        background-position: 45%;
        background-color: black;
    }

    #navbar{
        font-family: 'Poppins', sans-serif;
    }
    #head-text{
        font-family: 'Anton', sans-serif;
    }
    @media screen and (max-width:3000px) and (min-width:1800px){
        #nav{
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }
        #head-text{
            font-size: 200px;
            margin-top: 20%;
        }
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
            margin-top: 25%;
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
            margin-top: 25%;
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
            margin-top: 40%;
        }
    }
    @media screen and (max-width:425px){
        #head-text{
            font-size: 75px;
            margin-top: 40%;
        }
    }
    @media screen and (max-width:370px){
        #head-text{
            font-size: 80px;
            margin-top: 25%;
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
            margin-top: 75%;
        }
    }
</style>