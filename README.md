# Education-webpage-
This webpage is made by using the HTML and CSS
HTML part of the webpage.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ecobook</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" />
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <img src="images/logo.jpg" alt="">
        
        <div class="navigation">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">Course</a></li>
                <li><a href="#">Contact us </a></li>
            </ul>

        </div>



    </nav>
    <section id="home">
        <h2>Enhance Your Future With Ecobook</h2>
        <P>Education is a process of enrolling for studying various subjects related to arts and science stream. The courses offered depend on the age and mental ability of the student. Vocational education and adult education are also a part of the broad classification of the education system.</P>
        <div class="btn">
            <a class="blue" href="To register.html"> To Register</a>
            <a class="yellow" href="visit course.html">Visit course</a>


        </div>
    </section>
    <section id="features">
        <h1>Awesome Features</h1>
        <P>Replenish man have thing gathering lights yielding shall you</P>
        <div class="fea-base">
            <div class="fea-box">
                <i class="fa-sharp fa-solid fa-graduation-cap"></i>
            
            <h3> Scholarship facility</h3>
            <p>
                One make creepath,man bearing theire firmament won't great heaven 
            </p>
        </div>
        
        
            <div class="fea-box">
                <i class="fas fa-school"></i>
            
            <h3> Dell online course</h3>
            <p>
                One make creepath,man bearing theire firmament won't great heaven 
            </p>
        </div>
        
        
            <div class="fea-box">
                <i class="fas fa-certificate"></i>
            
            <h3>Global certificate </h3>
            <p>
                One make creepath,man bearing theire firmament won't great heaven 
            </p>
        </div>
    </section>
    <!--profiles-->
    <section id="experts">
        <h1>Community Experts</h1>
        <P>Replenish man have thing gathering lights yielding shall you</P>
        <div class="expert-box">
            <div class="profile">
                <img src="images/teacher 1.jpg" alt=""  width="60%"  height="60%">
                <h6>Sofia</h6>
                <p>python & algorithm Expert</p>
                <div class="pro-links">
                    <i class="fab fa-facebook"> </i>
                    <i class="fab fa-instagram"> </i>
                    <i class="fab fa-linkedin-in"> </i>


                    
                </div>
            </div>

            <div class="profile">
                <img src="images/teacher 2.jpg" alt="" width="60%"  height="60%">
               
                
                <h6>Elbert </h6>
                <p>HTML,CSS & javascrpit</p>
                <div class="pro-links">
                    <i class="fab fa-facebook"> </i>
                    <i class="fab fa-instagram"> </i>
                    <i class="fab fa-linkedin-in"> </i>


                    
                </div>
            </div>

            <div class="profile">
                <img src="images/teacher pic 3.jpg" alt=""   width="60%"  height="60%">
                <h6>jain  </h6>
                <p>Soft Skill</p>
                <div class="pro-links">
                    <i class="fab fa-facebook"> </i>
                    <i class="fab fa-instagram"> </i>
                    <i class="fab fa-linkedin-in"> </i>


                    
                </div>
            </div>
        </div>

    </section>
    <!--footer-->
    <div id="site-footer" >
        <footer>
            <div class="footer-col" >
            <h3>Top products</h3>
            <li>Manage reputation</li>
            <li>Power Tools</li>
            <li>Manage website</li>
            <li>Marketing Services</li>
        </div>
    
    
    
        <div class="footer-col">
            <h3>quick links</h3>
            <li>Research</li>
            <li>Experts</li>
            <li>managed website</li>
            <li>For compliment</li>
        </div>
    
    
    
        <div class="footer-col">
            <h3>features</h3>
            <li>Manage reputation</li>
            <li>power Tools</li>
            <li>managed website</li>
            <li>online Services</li>
        </div>
    
    
        <div class="footer-col">
            <h3>resources</h3>
            <li>guides</li>
            <li>Research</li>
            <li>Expert</li>
            <li>Marketing services</li>
        </div>
        <div class="footer-col">
            <h3>Newsletter</h3>
            <p>you can trust us. we only promo offers</p>
            <div class="subscribe">
                <input type="text" placeholder="Your Email address ">
                <a href="#" class="yellow">SUBSCRIBE</a>
            </div>
             
             
        </div>
        <div class="copyright">
            <p>copyright @2021 All right reserved | This template is made by dev kumar </p>
          
           </div>
           <div class="pro-links">
            <i class="fab fa-facebook"> </i>
            <i class="fab fa-instagram"> </i>
            <i class="fab fa-linkedin-in"> </i>
    
        </div>
    </footer>

    </div>    
</body>
</html>


CSS part of the webpage 
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap');
*{
    margin:0;
    padding:0;
    box-sizing: border-box;
}
body{
    font-family: 'Poppins',sans-serif;
    margin: 0%;
    
}

/* global tags*/
h1 {
    font-size: 2.5rem;
    font-weight: 700;
    color:rgb(35,35,85);
}
span{
    font-size: 0.9rem;
    color: #595555;
}
h6{
    font-size:1.1rem;
    color:rgb(24,24,49)
}
nav {
    position: fixed;
    width: 100%;
    background-color: rgb(255, 255, 255);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding: 1vw 8vw;
    
    align-items: center;
    box-shadow: 2px 2px 10px rgba(0,0,0,0.15);
    

}
nav img{
    width:100px;
    cursor: pointer;
    padding-bottom: 10px;
    
    
    

}
nav .navigation ul{
    display:flex;
    justify-content: flex-end;
    align-items: center;
}
nav .navigation ul li{
    list-style: none;
    margin-left: 30px;
}
nav .navigation ul li a{
    transition: 0.3s ease;
    font-size: 16px;
    font-weight: 500;
    text-decoration: none;
    color:rgb(21,21,100)
    
    

}
nav .navigation ul li a:hover{
    color:rgb(246, 214, 8)

}
#home{
    background-image: linear-gradient(rgba(9,5,54,0.3),rgba(5,4,46,0.7)),url("images/pic1.jpg");
    width: 100%;
    height: 100vh;
    background-size: cover;
    background-position: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding-top: 40px;


}
#home h2{
    font-size: 2.2rem;
    letter-spacing: 1px;
    color:#fff
    
}
#home p{
    width:50%;
    font-size: 0.9rem;
    line-height: 25px;
    color:#fff
    
}
#home .btn{
    margin-top: 30px;


}
#home a{
    text-decoration: none;
    font-size: 0.9;
    padding: 13px 35px;
    background-color: #fff;
    font-weight: 600;
    border-radius: 5px;
}
#home a.blue{
    color:#fff;
    background-color: rgb(21,21,100);
    transition: 0.3s ease;

}
#home a.blue:hover{
    color:rgb(21,21,100);
    background-color: #fff;
    
}
#home a.yellow{
    color:#fff;
    background-color: #FDC93B;
    transition: 0.3s ease;

}
#home a.yellow:hover{
    color:rgb(21,21,100);
    background-color:#fff;
    
}
#features{
    padding: 5vw 8vw 0 8vw; 
    text-align: center;
}
#features .fea-base{
    
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    grid-gap: 1rem;
    margin-top: 50px;
    

}

#features .fea-box{
    background: #f9f9ff;
    text-align: start;
}
#features .fea-box i{
    font-size: 2.3rem;
    color: rgb(44,44,80);
}
#features .fea-box h3{
    font-size:1.2rem;
    padding: 13px 0 7px 0;
    font-weight:600;
    color:rgb(46 ,46,59)
    

}
#features .fea-box p{
    font-size:1rem;
    font-weight:600;
    color:rgb(70 ,70,87)
    

}


#course{
    padding: 8vw 8vw 0 8vw;
    text-align: center;
}
#course .course-box{
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    grid-gap: 1rem;
    margin-top: 50px;
    

}
#course .courses{
    text-align: start;
    background: #f9f9ff;
    height: 100%;
    position: relative;


}
#course .courses img{
    width: 100%;
    height: 60%;
    background-size: cover;
    background-position:center;


}
#course .courses .details{
    padding: 15px 15px 0 15px

}
#course .courses .details i{
    color:#fdc93b;
    font-size: .9rem;
}
#course .courses .cost{
    background-color:rgb(44,44,80);
    color:#fff;
    line-height:70px;
    width:70px;
    height: 70px;
    text-align:center;
    border-radius: 50%;
    position: absolute;
    right: 15px;
    bottom: 100px;
}
#experts{
    padding: 8vw 8vw 0 8vw;
    text-align: center;
}
#experts .expert-box{
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 2rem;
    margin-top: 50px;
    

}
#experts .expert-box .profile{
    background: #fafaf1;
    padding: 30px 10px;

}
.pro-links {
   margin-top: 10px;
}
.pro-links i{
    padding: 10px 13px;
    border: 1px solid rgb(21,21,100);
    cursor: pointer;
    transition: 0.3s ease;
}
.pro-links i:hover{
    background: rgb(21,21,100);
    color: #fff;
   
    border: 1px solid rgb(21,21,100);
    cursor: pointer;
}

/*footer*/
footer{
    padding:8vw ;
    background-color:#101c32 ;
    display:flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;
    width:100%;
    margin-left: 0%;
    border:1px solid black;
    height: 460px;
   

 
}
footer .footer-col{
    padding-bottom: 40px;
    margin: 0;
}
footer h3{
    color:rgb(241,240,245) ;
    font-weight: 600;
    padding-bottom: 20px;
}
footer li{
    list-style:none;
    color: #7b838a;
    padding: 10px 0;
    font-size: 15px;
    cursor: pointer;
    transition: o.3s ease;
}
footer li:hover{
    color: rgb(241,240,245);

}
footer P{
    color: #7b838a;
}
footer .subscribe{
    margin-top:20px ;
}
footer input{
    padding: 15px 12px;
    width: 220px;
    
    background: #334f6c;
    border: none;
    outline: none;
    color: #fff;

}
footer .subscribe a{
    text-decoration: none;
    font-size: 0.9;
    padding: 12px 15px;
    background-color: #fff;
    font-weight: 600;
   
}

footer .subscribe a.yellow{
    color:#2c2c2c;
    background-color: #FDC93B;
    transition: 0.3s ease;

}
footer .subscribe a.yellow:hover{
    color:rgb(21,21,100);
    background-color:#fff;
    
}


