<section id="locations" class="h-[100vh] mt-[10%]">
    <div>
        <h1 id="name" class="text-[#050a2f] text-6xl text-center font-bold">LOCATIONS</h1>
    </div>
    <div id="cards" class="flex gap-5 justify-center mt-[5%]">
        <a href="/srikakulam">
            <div class="card" style="background-image: url(homebg.png); background-size: cover; background-position: 40%;">
            <div class="card-details">
              
            </div>            
          </div>
          <p class=" text-[#050a2f] text-center text-3xl font-bold">SRIKAKULAM</p>
        </a>
        <a href="/kothavalasa">
            <div class="card" style="background-image: url(homebg.png); background-size: cover; background-position: 40%;">
            <div class="card-details">
              
            </div>  
          </div>
          <p class=" text-[#050a2f] text-center text-3xl font-bold">KOTHAVALASA</p>
        </a>
        <a href="/bhogapuram">
            <div class="card" style="background-image: url(homebg.png); background-size: cover; background-position: 40%;">
            <div class="card-details">
              
            </div>  
          </div>
          <p class=" text-[#050a2f] text-center text-3xl font-bold">BOGHAPURAM</p>
        </a>
        <a href="thagarapuvalasa">
            <div class="card" style="background-image: url(homebg.png); background-size: cover; background-position: 40%;">
            <div class="card-details">
              
            </div>  
          </div>
          <p class=" text-[#050a2f] text-center text-3xl font-bold">THAGARAPUVALASA</p>
        </a>   
    </div>
</section>
<section id="head" style="background-image: url(/12.jpg); background-size: cover; height: 110vh; background-position: 50%; background-attachment: fixed;">
</section>

<style>
.card {
 width: 315px;
 height: 355px;
 border-radius: 50px;
 background: #f5f5f5;
 padding: 1.8rem;
 border: 2px solid #c3c6ce;
 transition: 0.5s ease-out;
 overflow: visible;
 cursor: pointer;
}

.card-details {
 color: black;
 height: 100%;
 gap: .5em;
 display: grid;
 place-content: center;
}



.text-body {
 color: rgb(134, 134, 134);
}

/*Text*/
.text-title {
 font-size: 1.5em;
 font-weight: bold;
}

/*Hover*/
.card:hover {
 border: 4px solid #050a2f;
 box-shadow: 0 4px 18px 0 rgba(0, 0, 0, 0.25);
 transform: scale(1.05);
}

.card:hover .card-button {
 transform: translate(-50%, 50%);
 opacity: 1;
}
#cards{
flex-wrap: wrap;
}
.card{
    flex: 1 0 335px 355px;
}
@media (max-width:1320px){
    #locations{
        height: 135vh;
    }
}
@media (max-width:1260px){
    #locations{
        height: 140vh;
    }
}
@media (max-width:1190px){
    #locations{
        height: 150vh;
    }
}
@media (max-width:650px){
    #locations{
        height: 280vh;
    }
}@media (max-width:360px){
    #name{
        font-size: 50px;
    }
}
</style>

