<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- <link rel="stylesheet" href="bootstrap.css"> -->
    <!-- <link rel="stylesheet" href="style.css"> -->
    <style>

     .backGround{
         background-color: rgb(39, 39, 39);
         color: aliceblue;
     }
     .Home{
         margin-left: 0;
         padding: 0;
         min-height: 750px;
         background-image: -webkit-gradient(liner, left  top,     left bottom, from(rgba(49, 49, 49, 0.   199)));
         background-image: linear-gradient(180deg, rgba  (82,  79, 255, 0.13),rgba(0, 0, 2, 0.74)),url (wallOut.png);
         /* background-position: 0px 0px, 100% 50%; */
         background-size: auto, cover;
         background-attachment: scroll, scroll;
         object-fit: cover;
         -o-object-fit: cover;
     }
     .navigationBar table{
         padding-left: 0;
         margin-left: 0;
         width: 100%;
         background-color: rgba(0, 0, 0, 0.144);
     }
     .navTabs{
         font-family: Comic Sans MS;
     }
     .pink{
         color: rgb(255, 0, 179);
     }
     a{
         text-decoration: none;
         color: aliceblue;
     }
     a:hover{
         text-decoration: none;
         color: aliceblue;
     }
     .navigationBar .logo{
         padding-left: 5%;
         font-family: Bauhaus 93;
     }
     .btnSubscrybe button{
         background-color: rgb(255, 0, 179);
         color: aliceblue;
         border: none;
         border-radius: 1rem;
         padding-left: 15px;
         padding-right: 15px;
         margin-top: 5px;
         margin-bottom: 5px;
         font-family: Comic Sans MS;
     }
     .homeTxt{
         margin-left: 3%;
         margin-top: 20%;
         height: 600px;
    
         /* background-color: aqua; */
         /* font-size: xx-large; */
     }
     .helloMyName{
         font-size: x-small;
         margin-bottom: 0px;
         padding-bottom: 0px;
    
     }
     .name{
         font-size: xx-large;
         margin-top: 0px;
         padding-top: 0px;
         font-family: Adobe Gothic Std;
     }
     .iAmWeb{
         font-family: Adobe Gothic Std;
         font-size: smaller;
         margin-top: 0;
         padding-top: 0;
     }
     .lblLstart{
         position: relative;
     }
     .tbLstart{
         border-style: solid;
         padding: 5px;
         border-radius: 1rem;
         width: 16rem;
         border-color: aliceblue;
    
     }
     .lStart{
         position: absolute;
         top: 0;
         right: 0;
         bottom: 0;
         background-color: rgb(255, 0, 179);
         color: aliceblue;
         border-radius: 1rem;
         padding: 5px;
         width: 6rem;
         border-left: none;
         border-style: solid;
         border-color: aliceblue;
    
     }
     .dark_black{
         background-color: rgb(24, 24, 24);
    
     }
     .myImg{
         width: 70%;
         margin: 10%;
    
     }
     .aboutMe{
         /* margin: 5%; */
         margin-top: 10%;
     }
     .aboutMeTxt{
         font-family: Viner Hand ITC;
     }
     .developer{
        
     }
     .mySelf{
        
     }
     .mySelfBTN{
         padding-left: 20px;
         padding-right: 20px;
         padding-top: 5px;
         padding-bottom: 9px;
         /* margin: 10px; */
         margin-left: 15px;
         margin-right: 15px;
         margin-bottom: 15px;
         border: none;
         border-radius: 1rem;
         background-color: rgb(255, 0, 179);
         color: aliceblue;
     }
     .servisecTitle{
         font-family: Lucida Handwriting;
    
     }
     .servicesBtn{
         padding: 2px;
         background-color: rgb(27, 26, 26);
         border: none;
         border-radius: 1rem;
         color: aliceblue;
         padding-top: 10px;
         /* padding-bottom: 50%; */
    
     }
     .servicesBtn iframe{
         width: 60px;
         padding-bottom: 0;
         /* background-color: blueviolet; */
         /* background-color: aqua; */
         margin-bottom: none;
         padding-bottom: none;
     }
     .txtPata{
         padding: 15px;
     }
     .iconsFinal{
         width: 50px;
         height: 50px;
         margin: 3%;
         padding: 3%;
     }
     /* -----------desktop------------ */
     @media screen and (min-width:800px){
         .navigationBar{
             font-size: larger;
         }
         .navigationBar .logo{
             padding-left: 5%;
             font-size: xx-large;
             padding-right: 0px;
         }
     }
     /* -------------tablet----------- */
     @media screen and (max-width:800px){
         .navigationBar .logo{
             font-size: x-large;
             padding-left: 0;
         }
     }
     /* ------------mobile------------ */
    
     @media screen and (max-width:500px){
         .navigationBar .logo{
             padding-left: 0;
         }
    
     }






    </style>

</head>
<body>
    <div class=" backGround">
        <div class="Home" id="home">
            <div class="navigationBar">
                <table>
                    <tr>
                        <td class="logo">
                            <a href=""><b>Portfo<font class="pink">lio</font></b></a>
                        </td>
                        <td class="navTabs">
                            <a href="#home">Home</a>
                        </td>
                        <td class="navTabs">
                            <a href="#about_me">About us</a>
                        </td>
                        <td class="navTabs">
                            <a href="#Services">Services</a>
                        </td>
                        <td class="navTabs">
                            <a href="#Skills">Skills</a>
                        </td>
                        <td class="navTabs">
                            <a href="#Contact_Us">Contact Us</a>
                        </td>
                        <td class="btnSubscrybe">
                            <a href="https://www.youtube.com/c/BugAntProgrammer" target="_blank"><button>Subscrybe</button></a>
                            
                        </td>
                    </tr>
                </table>
            </div>
            <div class="homeTxt">
                <p>
                <font class="helloMyName" id="home">H e l l o , &nbsp;&nbsp; m y &nbsp;&nbsp; n a m e &nbsp;&nbsp; i s</font><br>
                <font class="name">Chappie </font><font class="name pink"> Ghost</font><br>
                <font class="iAmWeb">i'm a Student...</font><br/><br/><br/>
                <label for="" class="lblLstart">
                    <input type="text" class="tbLstart" placeholder="Ener Your Email">
                    <button class="lStart" onclick="window.alert('not finished this function')">Lets Start</button>
                </label>
                </p>
            </div>
        </div>
        
        <div class="abouth_me_aria dark_black">
            <hr>
            <div class="container">
                <div class="row">
                    <div class="col-md-6">
                        <img src="myImg.png" alt="" class="myImg">
                    </div>
                    <div class="col-md-6 aboutMe">
                        <h1 class="aboutMeTxt" id="about_me">About Me</h1>
                        <h4 class="developer">Developer <font class="pink">& Desaigner</font></h4>
                        <p class="mySelf"> 
                            I am a front-end web developer. but i'm beginer lavel student. i can <b>python, html, css, c#, arduino and editing </b> works. A responsive design makes your website accessible to all users, regardless of their device.

                            <br><br>
                            <ul>
                                <li>i'm 19 years old student. <i><a href="" title="yyyy/mm/dd">(2022/12/10)</a></i> </li>
                                <li>i live in sri lanka.</li>

                            </ul>
                        </p>
                        <!-- <button class="mySelfBTN"><b>Let's Talk</b></button> -->

                    </div>
                </div>
            </div><hr>
        </div>
        
        <div>
            <div class="container">
                <br><br>
                <center>
                    <h1 class="servisecTitle" id="Services">Our Services</h1>
                </center>
                <div class="row">
                    <div class="col-md-4">
                        <div class="servicesBtn">
                            <center>
                                <!-- <iframe src="affiliatetheme.svg" frameborder="0">f</iframe> -->
                            <iframe src="affiliatetheme.svg" frameborder="0" ></iframe>
                            <h1>Web Development</h1>
                            <p class="txtPata">
                                small web pages, web rapair, styling, font end development, loging form desaing and other works

                            </p>
                            <button class="mySelfBTN" onclick="window.alert('not finished this function \n _comming soon_')"> 
                                Read more
                            </button>
                                
                            </div>
                        </button>
                            </center>
                    </div>
                    <div class="col-md-4">
                        <div class="servicesBtn">
                            <center>
                                <!-- <iframe src="affiliatetheme.svg" frameborder="0">f</iframe> -->
                            <iframe src="accusoft.svg" frameborder="0" ></iframe>
                            <h1>softwera development</h1>
                            <p class="txtPata">
                                python or C# used small application or softweras or, c# font end development's 
                                <br><br>
                                i can python TK inter, ursina, py game.

                            </p>
                            <button class="mySelfBTN" onclick="window.alert('not finished this function \n _comming soon_')">
                                Read more
                            </button>
                            </center>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="servicesBtn">
                            <center>
                                <!-- <iframe src="affiliatetheme.svg" frameborder="0">f</iframe> -->
                            <iframe src="battle-net.svg" frameborder="0" id="Skills"></iframe>
                            <h1>video and photos</h1>
                            <p class="txtPata">
                                i can premer Pro and photoshop.
                                <br> <br>
                                color grading, birth day vedios, CV disaign, application disaign and other works..
                                

                            </p>
                            <button class="mySelfBTN" onclick="window.alert('not finished this function \n _comming soon_')">
                                Read more
                            </button>
                            </center>
                        </div>
                    </div>

                </div>
            </div>
            <br>
        </div>
        <div class="dark_black">
            <hr>
            <center>
                <br><br><br><br>
                <!-- <h3 id="Services">Let Me Get You  Beautiful Website</h3> -->
                <h3 id="Services">Wait for over the A/L exsam.</h3>
                <!-- <button class="mySelfBTN">Hire Me</button>   -->
                <br><br><br><br>
            </center>
            <hr>
        </div>
        
        <div class="">
            
            <center>
                <br><br><br><br>
                <h3>Shehan Rajapaksha</h3>
                <p>For more HTML, CSS and coding tutorial. please click on the <br> link below to subscribe to mu channel</p>
                  
                <div class="row">
                    
                    <div class="col-sm-3"></div>
                    <div class="col-sm-2">
                        <a href="https://www.facebook.com/profile.php?id=100081017291402" target="_blank">
                            <button class="mySelfBTN"><iframe src="facebook.svg" frameborder="0" class="iconsFinal"></iframe></button>
                        </a>
                        
                    </div>
                    <div class="col-sm-2">
                        <a href="https://twitter.com/shehanrajapaks9?t=9RW27BiEzE8CUuXAbKJ-lA&s=09" target="_blank">
                            <button class="mySelfBTN"><iframe src="twitter.svg" frameborder="0" class="iconsFinal"></iframe></button>
                        </a>
                        
                    </div>
                    <div class="col-sm-2">
                        <a href="https://wa.link/7fzg5b" target="_blank">
                            <button class="mySelfBTN"><iframe src="whatsapp.svg" frameborder="0" class="iconsFinal"></iframe></button>
                        </a>
                        
                    </div>
                    <div class="col-sm-3"></div>

                </div>
                <br><br><br><br>
            </center>
        </div>
        <hr>
    </div>




    <!-- <div class="container">
        <div class="one">
            hello
        </div>
        <div class="two">
            hello
        </div>
    </div> -->
    <style>

        


    </style>
    
    
</body>
</html>
