<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500&display=swap');
    *{
        font-family: 'Poppins', sans-serif;
        box-sizing: border-box;
        color: black;
        
    }
    body{
        background: linear-gradient(292.92deg, #E6E6E4 7.23%, #F0E8E2 97.74%);
        height: 2000px;
        }
    .header{
        position: relative;
        height: 100px;
        width: 100%;
        
    }
    .logo{
        position: absolute;
        left: 6%;
        bottom: 25px;
    }
    .nav{
        position: absolute;
        left: 40%;
        bottom: 59px;
    }
    .nav a{
        margin: 0 40px 0 0px;
        text-decoration: none;
    }
    .nav a:hover{
        border-bottom: solid 2.5px;
        transition: 0.1s;
    }
    
    .login{
        position: absolute;
        left: 90%;
        bottom: 59px;
    }
    .login a{
        text-decoration: none;
        padding: 7px 18px;
        border: 1.5px solid;
        border-radius: 4px;
    }
    .login a:hover{
        border: 1.5px solid;
        border-radius: 4px;
        background-color: rgb(58, 184, 58);
        transition: 0.5s;
       }
    
   
/******************** Banner*********** */
    .banner{
        
        position: relative;
    }

    .bannertext{
        padding-top: 100px;
        padding-left: 110px;
        margin-bottom: 50px;

    }
    .bannertext h2{
        font-size: 70px;
        
    }
    .bannertext p{
        color: #98a9a3;
    }
    .btnbanner a{
        background-color: rgb(119 195 119);
        text-decoration: none;
        border: 0.5px solid black;
        margin-left: 110px;
        padding: 18px;
        font-size: 20px;
        border: none;
        border-radius: 5px;

    }
    .btnbanner a:hover{
        background-color: #ffe6ea;
        transition: 0.5s;
    }
    
    .imgbanner1 img{
        border: 1px #d4d4d4 solid;
        border-radius:50%;
        width: 620px;
        height: 560px;
        position: absolute;
        left: 52%;
        bottom: -50px;
        z-index: -1;
    }
  
    .aside1logoicon{
        display: flex;
        max-width: 700px;
        margin: 60px 0px 120px 600px;
        justify-content: space-between;
    }
    .aside1logoicon img{
        width: 87.7px;
        height: 30px;
    }
    .aside1logoicon img:hover{
        box-shadow: 0 4px 8px 0 rgb(0 0 0 / 20%), 0 6px 20px 0 rgb(0 0 0 / 19%);
        
    }
    .aside2{
        text-align: center;
        font-size: 18px;
        line-height: 27px;
    }
    #text2{
     font-size: 32px;
     font-weight: 600;
     line-height: 48px;
 }





     .aside3{
        display: flex;
        max-width: 1400px;
        margin: 60px 2px 0px 160px;
        justify-content: space-between;
        column-gap: 100px;

    }
    .aside3 img:hover{
        box-shadow: 0 4px 8px 0 rgb(0 0 0 / 20%), 0 6px 20px 0 rgb(0 0 0 / 19%);
        border-radius: 20px 20px;
        transition: 0.5s;
    }
 

</style>
<body>
    <div class="wapper">
        <div class="header">
            <div class="logo">
                <h1>Shayna</h1>
            </div>
            <div class="nav">
                <a href="">Home</a>
                <a href="">Star</a>
                <a href="">Browse</a>
                <a href="">Pricing</a>
                <a href="">Story</a>
            </div>
            <div class="login">
                <a href="">Sign in</a>
            </div>
        </div>


        <div class="banner">
            <div class="bannertext">
                <h2>Learn UI Design <br> From The Read Expert</h2><br>
                <p>Stop wasting time browsing around and start learning <br> from our designers for your better career</p>
            </div>
            <div class="btnbanner">
                <a href="">Get Started</a>
            </div>
            <div class="bannerimg">
                <div class="imgbanner1">
                    <img src="../projectHTML/img/banner.jpg" alt="">
                </div>
            </div>
        </div>


        <div class="aside1">
            <div class="aside2text">
                <p>Trusted by Global Companies</p>
            </div>
            <div class="aside1logoicon">
                <div class="logoicon1">
                    <img src="../projectHTML/img/apple-111.png" alt="">
                </div>

                <div class="logoicon2">
                    <img src="../projectHTML/img/adobe.png" alt="">
                </div>

                <div class="logoicon3">
                    <img src="../projectHTML/img/slack.png" alt="">
                </div>

                <div class="logoicon4">
                    <img src="../projectHTML/img/spotify.png" alt="">
                </div>

                <div class="logoicon5">
                    <img src="../projectHTML/img/google.png" alt="">
                </div>
            </div>
        </div>
        <div class="aside2">
            <div class="aside2text">
                <p>Grow Today</p>
                <p id="text2">Star Your Career  </p>
                
            </div>
            
        </div>
        <div class="aside3">
            <div class="aside3items1">
                <img src="../projectHTML/img/Group 18.png" alt=""width="295px"height="450px">
                <p></p>
            </div>
            
            <div class="aside3items2">
                <img src="../projectHTML/img/Group 20.png" alt=""width="295px"height="450px">
                <p></p>
            </div>
            <div class="aside3items3">
                <img src="../projectHTML/img/Group 21.png" alt=""width="295px"height="450px">
                <p></p>
            </div>
            <div class="aside3items4">
                <img src="../projectHTML/img/Group 22.png" alt=""width="295px"height="450px">
                <p></p>
            </div>
        </div>


    </div>
</body>
</html>
