<footer id="footer" class="footer-distributed">

        <div id="container" class="flex gap-16">
            <div id="logo-text" class="footer-left">
                <img src="logo.png" alt="">
                <p id="logo-name" class="text-center text-white text-2xl font-bold">PROPERTIES & DEVELOPERS</p>
                <p id="home" class="text-center text-white leading-3 text-xl font-thin">A HOME CHANGES EVERYTHING</p>
                
            </div>
            
                <div class="text-lg">
                    <h1 class="text-white font-bold text-2xl">CONTACT US</h1>
                    <p class="text-white font-light leading-10"><span class="font-bold text-white">MAIL:  </span><a href="">kkproperties.d@gmail.com</a></p>
                    <p class="text-white font-light"><span class="font-bold text-white">PHONE: </span>+91 7386665670</p>
                </div>
                <div id="locations" class="leading-10">
                    <h1 class="text-white font-bold text-2xl">LOCATIONS</h1>
                    <a href="" class="a1"><p class="text-white font-normal">SRIKAKULAM</p></a>
                    <a href="" class="a2"><p class="text-white font-normal">KOTHAVALASA</p></a>
                    <a href="" class="a3"><p class="text-white font-normal">BOGHAPURAM</p></a>
                    <a href=""><p class="text-white font-normal">THAGARAPUVALASA</p></a>
                </div>
                <div>
                    <h1 class="text-white font-bold text-2xl">FOLLOW US</h1>
                    <div id="social-icons" class="flex">
                        <div>
                            <a href="https://www.instagram.com/kkproperties_developers/"><img src="insta.png" alt=""></a>
                        </div>
                        <div>
                            <a href="https://twitter.com/kk_Properties_"><img src="twitter.png" alt=""></a>
                        </div>
                        <div>
                            <a href=""><img src="facebook.png" alt=""></a>
                        </div>
                    </div>
                </div>
        </div>
        
    </footer>

    <style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,900&display=swap'); 


footer p,h1{
    font-family: 'Poppins', sans-serif;
}
#locations a{
    position: relative;
			text-decoration: none;
			color: white; /* change color as desired */
		
}
#locations a::after{

    content: "";
			position: absolute;
			left: 0;
			bottom: -2px; /* adjust distance from text as desired */
			height: 2px;
			width: 0;
			background-color: white; /* change color as desired */
			transition: width 0.2s ease;
}
#locations .a1:hover::after{
    width: 65%;
}
#locations .a2:hover::after{
    width: 75%;
}
#locations .a3:hover::after{
    width: 75%;
}
#locations a:hover::after{
    width: 100%;
}
#home{
    letter-spacing: 1px;
}

body {
    font-family: 'Poppins', sans-serif;
}

html {
    background-color: #eaf0f2;
}

header {
    text-align: center;
    padding-top: 100px;
    margin-bottom: 300px;
    font-size: 35px;
}

header h2 {
    color: #f0525f;
}

header span {
    color: #eaa03f;
}

/* The footer is fixed to the bottom of the page */

footer {
    
    bottom: 0;
}
#social-icons a img{
    transition: 0.3s ease-in-out;
}
#social-icons a img:hover{
    transform: scale(1.3);
    transition: 0.3s ease-in-out;
}

@media (max-height:800px) {
    footer {
        position: static;
    }
    header {
        padding-top: 40px;
    }
}

.footer-distributed {
    background-color: #050a2f;
    box-sizing: border-box;
    width: 100%;
    text-align: left;
    font: bold 16px sans-serif;
    padding: 50px 50px 60px 50px;
}

.footer-distributed .footer-left, .footer-distributed .footer-center, .footer-distributed .footer-right {
    display: inline-block;
    vertical-align: top;
}

/* Footer left */

.footer-distributed .footer-left {
    width: 30%;
}

.footer-distributed h3 {
    color: #ffffff;
    font: normal 36px 'Cookie', cursive;
    margin: 0;
}


.footer-distributed h3 span {
    color: #e0ac1c;
}

/* Footer links */

.footer-distributed .footer-links {
    color: #ffffff;
    margin: 20px 0 12px;
}

.footer-distributed .footer-links a {
    display: inline-block;
    line-height: 1.8;
    text-decoration: none;
    color: inherit;
}

.footer-distributed .footer-company-name {
    color: #8f9296;
    font-size: 14px;
    font-weight: normal;
    margin: 0;
}

/* Footer Center */

.footer-distributed .footer-center {
    width: 35%;
}

.footer-distributed .footer-center i {
    background-color: #33383b;
    color: #ffffff;
    font-size: 25px;
    width: 38px;
    height: 38px;
    border-radius: 50%;
    text-align: center;
    line-height: 42px;
    margin: 10px 15px;
    vertical-align: middle;
}

.footer-distributed .footer-center i.fa-envelope {
    font-size: 17px;
    line-height: 38px;
}

.footer-distributed .footer-center p {
    display: inline-block;
    color: #ffffff;
    vertical-align: middle;
    margin: 0;
}

.footer-distributed .footer-center p span {
    display: block;
    font-weight: normal;
    font-size: 14px;
    line-height: 2;
}

.footer-distributed .footer-center p a {
    color: #e0ac1c;
    text-decoration: none;
    ;
}

/* Footer Right */

.footer-distributed .footer-right {
    width: 30%;
}

.footer-distributed .footer-company-about {
    line-height: 20px;
    color: #92999f;
    font-size: 13px;
    font-weight: normal;
    margin: 0;
}

.footer-distributed .footer-company-about span {
    display: block;
    color: #ffffff;
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 20px;
}

.footer-distributed .footer-icons {
    margin-top: 25px;
}

.footer-distributed .footer-icons a {
    display: inline-block;
    width: 35px;
    height: 35px;
    cursor: pointer;
    background-color: #33383b;
    border-radius: 2px;
    font-size: 20px;
    color: #ffffff;
    text-align: center;
    line-height: 35px;
    margin-right: 3px;
    margin-bottom: 5px;
}

.footer-distributed .footer-icons a:hover {
    background-color: #3F71EA;
}

.footer-links a:hover {
    color: #3F71EA;
}

@media (max-width: 1166px) {
    #container{
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
        align-items: center;
    }
}     
@media (max-width:1120px){
    #logo-text p{
        font-size: 19px;
    }
} 
@media (max-width:1073px){
    #logo-text p{
        font-size: 16px;
    }
} 
@media (max-width:933px){
    #logo-text p{
        font-size: 15px;
    }
} 
@media (max-width:885px){
    #logo-text p{
        font-size: 14px;
    }
}  
@media (max-width:839px){
    #logo-text p{
        font-size: 12px;
    }
}  
@media (max-width:745px){
    #logo-text p{
        font-size: 10px;
    }
}  
@media (max-width:652px){
    #logo-text p{
        font-size: 9px;
    }
} 
@media (max-width:501px){
    #logo-text  #logo-name{
        font-size: 8px;
    }
} 

        

        
    </style>