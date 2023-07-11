# SamplePersonalPortfolio
1st task of Web Development internship given by Bharat Intern.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atharv - Web Developer</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        *{
            margin: 0;
            padding: 0;
        }
body{
    background-color: rgb(3, 10, 42);
    color: white;
    font-family: 'Poppins', sans-serif;
}
nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 80px;
    background-color: rgb(1, 4, 17);
}
nav ul{
    display: flex;
    justify-content: center;
}
nav ul li{
    list-style: none;
    margin: 0 23px;
}
nav ul li a{
    text-decoration: none;
    color: white;
}
nav ul li a:hover{
    color: rgb(178, 178, 240);
    font-size: 1.011rem;
}
main hr{
    border: 0;
    background-color: rgb(110, 110, 155);
    height: 1px;
    margin: 60px 84px;
}
.left{
    font-size: 1.5rem;
}
.firstSection{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin: 130px 0;
}
.firstSection > div{
    width: 30%;
}
.leftSection{
    font-size: 2.5rem;
}
.leftSection .buttons{
    padding: 40px 0;
}
.leftSection .btn{
    padding: 12px;
    background-color: rgb(37, 37, 78);
    color: white;
    border: 2px solid white;
    border-radius: 6px;
    font-size: 20px;
    cursor: pointer;
}
.rightSection img{
    width: 80%;
}
.purple{
    color: rgb(179, 127, 228);
}
.text-gray{
    color: gray;
}
#element{
    color: rgb(179, 127, 228);
}
.secondSection{
    max-width: 80vw;
    margin: auto;
    height: 80vh;
}
.secondSection h1{
    font-size: 1.5rem;
}
.secondSection .box{
    background: white;
    width: 79vw;
    height: 2px;
    margin: 56px 0;
    display: flex;
}
.secondSection .vertical{
    height: 93px;
    width: 1px;
    background-color: white;
    margin: 0 100px;
}
.image-top{
    width: 23px;
    position: relative;
    top: -32px;
    left: -9px;
}
.vertical-title{
    position: relative;
    top: 75px;
    width: 150px;
    font-size: 14px;
}
.vertical-desc{
    position: relative;
    top: 86px;
    color: gray;
    width: 150px;
    font-size: 9px;
}
footer{
    background-color: rgb(30, 26, 34);
    }
.footer{
    display: flex;
    padding: 23px 122px;
    justify-content: space-evenly;
    }
.footer ul{
    list-style: none;
}
.footer > div{
    width: 223px;
}
footer .footer-rights{
    text-align: center;
    color: gray;
    padding: 12px 0;
}
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="left">Atharv's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi, My name is <span class="purple">Atharv</span>
                <div>and I am a passionate</div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download Resume</button>
                    <button class="btn">Visit Github</button>
                </div>
            </div>
            <div class="rightSection">
                <img src="bg.png" alt="">
            </div>
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work Experience</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="developer.png" alt="">
                    <div class="vertical-title">
                        HTML Developer (2021-2022) 
                    </div>
                    <div class="vertical-desc">
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Enim, obcaecati? Saepe qui optio tempora molestias sint obcaecati inventore consequuntur sapiente repellendus, repellat alias?
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="facebook.png" alt="">
                    <div class="vertical-title">
                        Node.js Developer-Facebook (2021-2022)
                    </div>
                    <div class="vertical-desc">
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Enim, obcaecati? Saepe qui optio tempora molestias sint obcaecati inventore consequuntur sapiente repellendus, repellat alias?
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="instagram.png" alt="">
                    <div class="vertical-title">
                        HTML Developer-Instagram (2021-2022) 
                    </div>
                    <div class="vertical-desc">
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Enim, obcaecati? Saepe qui optio tempora molestias sint obcaecati inventore consequuntur sapiente repellendus, repellat alias?
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="twitter.png" alt="">
                    <div class="vertical-title">
                        HTML Developer-Twitter (2021-2022) 
                    </div>
                    <div class="vertical-desc">
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Enim, obcaecati? Saepe qui optio tempora molestias sint obcaecati inventore consequuntur sapiente repellendus, repellat alias?
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="facebook.png" alt="">
                    <div class="vertical-title">
                        HTML Developer-Facebook(2021-2022) 
                    </div>
                    <div class="vertical-desc">
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Enim, obcaecati? Saepe qui optio tempora molestias sint obcaecati inventore consequuntur sapiente repellendus, repellat alias?
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="youtube.png" alt="">
                    <div class="vertical-title">
                        Software Developer-YouTube (2021-2022) 
                    </div>
                    <div class="vertical-desc">
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Enim, obcaecati? Saepe qui optio tempora molestias sint obcaecati inventore consequuntur sapiente repellendus, repellat alias?
                    </div>
                </div>
               
            </div>
        </section>
    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>Atharv's Developer Portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>services</li>
                    <li>Contact</li>
                </ul>
            </div>
            <div class="footer-third">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>services</li>
                    <li>Contact</li>
                </ul>
            </div>
            <div class="footer-fourth">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>services</li>
                    <li>Contact</li>
                </ul>
            </div>
        </div>
        <div class="footer-rights">
            Copyright &#169; atharvsportfolio.com | All rights reserved
        </div>
    </footer>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
          strings: ['Software Engineer', 'Web Developer'],
          typeSpeed: 50,
        });
      </script>
</body>
</html>
