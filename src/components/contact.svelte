<section id="map" class="h-[100vh] mt-[10%]">
    <div>
        <h1 id="head-text" class="text-[#050a2f] text-6xl font-bold text-center">CONTACT US</h1>
    </div>
    <div id="map-container" class="flex justify-center gap-[15%] items-center mt-[3%]">
        <div class="flex flex-col">
            <div>
                <h1 class="text-3xl text-[#050a2f] font-bold">MAIL :<a href="mailto:kkproperties.d@gmail.com"><span class="font-normal">kkproperties.d@gmail.com</span></a></h1>
            </div>
            <div>
                <h1 class="text-3xl text-[#050a2f] font-bold">PHONE :<span class="font-normal">+91 7386665670</span></h1>
            </div>
        </div>
        <div>
            <p id="line" class="text-[#050a2f] text-lg font-bold">
            
            </p>
        </div>
        <div class="max-w-lg rounded-2xl">
            <iframe class="w-[100%]" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15194.30587161778!2d83.3320324!3d17.8115914!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a395befa9dda303%3A0x5781c56a5df412!2sBaba%20Institute%20of%20Technology%20%26%20Sciences!5e0!3m2!1sen!2sin!4v1681032004119!5m2!1sen!2sin" width="600" height="450" style="border:0;" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </div>
</section>

<style>
    #line{
        border-left: 5px solid #050a2f;
        height: 400px;
    }
    @media (max-width:1110px){
        #map-container{
            display: flex;
            flex-direction: column;
        }
        #line{
            display: none;
        }
        #map{
            height: 110vh;
        }
        #map-container h1{
            font-size: 18px;
        }
    }
    
    @media (max-width:925px){
        #head-text{
            font-size: 40px;
        }
    }
    @media (max-width:600px){
        #map{
            margin-top: 25%;
        }
    }
</style>