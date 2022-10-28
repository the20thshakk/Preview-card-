## Table of contents

- [Overview](#overview)
- [Links](#links)
- [My process](#my-process)
[Built with](#built-with)
- [Author](#author)




## Overview

I built out this Stat Preview card and get it looking as close to the design as possible from frontendmentor.

This is just a challenge

### Links

- Live Site URL: https://

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

<!-- html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter&family=Roboto&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap" rel="stylesheet">
    <title>Stat Preview card</title>
</head>
<body>   
    <div class="mainbox">
        <div class="rightbox">
            <img src="png/image-header-desktop.jpg" alt="">
        </div>

        <div class="leftbox">
            <div class="textbox">
                <div class="text">
                    <h1>Get <span class="insight"> insight </span> that helps <br> your business grow.</h1>
                    <p>Discover the benefits of data analytics and make <br>  better decision regarding revenue, customer <br> experience, and overall efficiency.</p>
                </div>

                <div class="grid-60">
                    <div class="grid-20a">
                        <h1>10k+</h1>
                        <p>COMPAINES</p>
                    </div>
                    <div class="grid-20b">
                        <h1>314</h1>
                        <p>TEMPLATES</p>
                    </div>
                    <div class="grid-20c">
                        <h1>12M+</h1>
                        <p>QUERIES</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="purplebox"></div>


</body>
</html>


<!-- css -->

body{
    background-color: hsl(233, 47%, 7%);
    font-family: 'Inter', sans-serif;
    /* font-family: 'Lexend Deca', sans-serif; */
}

.mainbox{
    background-color: hsl(244, 38%, 16%);
    height: 380px;
    width: 950px;
    box-sizing: border-box;
    border-radius: 10px;
    position: relative;
    top: 130px;
    left: 205px;
}

.mainbox .rightbox{
    height: auto;
    width: 100%;
}

.mainbox .rightbox img{
    height: 380px;
    width: 475px;
    float: right;
    border-radius: 0px 10px 10px 0px;
}

.textbox{
    padding: 50px 10px 0px 60px;
}

.text h1{
    font-size: 32px;
    color: white;
}

.text h1 .insight{
    color: hsl(277, 64%, 61%);
}

.text p{
    font-size: 14px;
    color: hsla(0, 0%, 100%, 0.6);
    line-height: 22px;
    font-weight: 100;
}

.grid-60{
    display: flex;
    gap: 1.5cm;
    padding-top: 20px;
}

.grid-20a h1{
    font-size: 26px;
    color: white;
}

.grid-20a p{
    font-size: 11px;
    color: hsla(0, 0%, 100%, 0.6);
    top: 310px;
    position: absolute;
}

.grid-20b h1{
    font-size: 26px;
    color: white;
}

.grid-20b p{
    font-size: 11px;
    color: hsla(0, 0%, 100%, 0.6);
    top: 310px;
    position: absolute;
}

.grid-20c h1{
    font-size: 26px;
    color: white;
}

.grid-20c p{
    font-size: 11px;
    color: hsla(0, 0%, 100%, 0.6);
    top: 310px;
    position: absolute;
}

.purplebox{
    height: 380px;
    width: 475px;
    background-color: hsl(277, 64%, 61%);
    opacity: 60%;
    border-radius: 0px 10px 10px 0px;
    position: absolute;
    top: 138px;
    left: 688px;
}



/* responsive */

@media(max-width: 768px){
    .mainbox{
        background-color: hsl(244, 38%, 16%);
        height: 900px;
        width: 430px;
        box-sizing: border-box;
        border-radius: 10px;
        position: relative;
        top: 0px;
        left: 20px;
    }
    .mainbox .rightbox{
        height: auto;
        width: 100%;
    }
    
    .mainbox .rightbox img{
        height: 400px;
        width: 430px;
        border-radius: 10px 10px 0px 0px;
    }
    .purplebox{
        height: 400px;
        width: 430px;
        box-sizing: border-box;
        top: 8px;
        left: 28px;
        background-color: hsl(277, 64%, 61%);
        opacity: 60%;
        border-radius: 10px 10px 0px 0px;
        position: absolute;
    }
    
    
.textbox{
    padding: 430px 50px 0px 50px;
}

.text h1{
    font-size: 24px;
    color: white;
    text-align: center;
    padding-left: 20px;
}

.text h1 .insight{
    color: hsl(277, 64%, 61%);
}

.text p{
    font-size: 14px;
    color: hsla(0, 0%, 100%, 0.6);
    line-height: 22px;
    font-weight: 100;
    text-align: center;
    padding-left: 20px;
}

.grid-60{
    display: list-item;
    gap: 2cm;
}

.grid-20a h1{
    font-size: 26px;
    color: white;
    position: absolute;
    left: 190px;
}

.grid-20a p{
    font-size: 11px;
    color: hsla(0, 0%, 100%, 0.6);
    top: 660px;
    left: 190px;
    position: absolute;
}

.grid-20b h1{
    font-size: 26px;
    color: white;
    top: 680px;
    left: 190px;
    position: absolute;
}

.grid-20b p{
    font-size: 11px;
    color: hsla(0, 0%, 100%, 0.6);
    top: 720px;
    left: 190px;
    position: absolute;
}

.grid-20c h1{
    font-size: 26px;
    color: white;
    top: 740px;
    left: 190px;
    position: absolute;
}

.grid-20c p{
    font-size: 11px;
    color: hsla(0, 0%, 100%, 0.6);
    top: 780px;
    left: 190px;
    position: absolute;
}




}




## Author

- Email - [adeyemimeshack@gmail.com]
- Frontend Mentor - [@the20thshakk](https://https://www.frontendmentor.io/profile/the20thshakk)
- Twitter - [@the20thshakk]
