<<<<<<< HEAD
=======
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="styleshhet" href="index.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="index.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-4 adiv"><a href="index.html">home</a></div>
                <div class="col-4 bdiv"><a href="notes.html">notes of all topics</a></div>
                    <div class="col-4 cdiv"><a href="questionpaper.html">old question paper</a></div>
                  </div>
 </div>
 <hr>
 <div class="box"> 
 <div id="slides"> 
     <div class="slide slide-1" > 
    <img src= "https://i.im.ge/2025/01/15/zBjSZq.1000016724.webp"> 
</div>
<div class="slide slide-2"> 
     <img src="https://i.im.ge/2025/01/21/HMzJ5y.1000005345.webp"> 
    </div>
<div class="slide slide-3"> 
    <img src= "https://i.im.ge/2025/01/21/HMzHfa.1000013746.webp">
</div>
</div>
</div>
<hr> 
<marquee direction="right" scrollamount="5"> 
    <a class="g" href="https://www.mediafire.com/file/0q6pe7bz9q9iujp/HBSE_Class_12_Physics_Preboard_2025.pdf/file">Preborad question paper of physics(12th)</a>
 </marquee>
</body>
<style>
    .box{
        height: 250px;
        width: 450px;
    }
     body{
        background-color: darkturquoise;
     }
    a{
        color: dimgrey;
    }
     a:hover{
        color: #000;
     }
    .row{
        background-color: gainsboro;      
    }
    .row:hover{
         background-color: yellow;
    }
    .slides{
        height: 450px;
        width: 450px;
        overflow: hidden;
        position: relative;
    }
    .slide{
        position: absolute;
        height: 250px;
        opacity: 0;
        animation: slide-show 12s infinite;
    }
    .slide-2{
        animation-delay: 8s;
    }
    .slide-3{
        animation-delay: 15s;
    }
    .slide img{
        width: 400px;
        height:250px;
        
    }
    @keyframes slide-show{
        0%{
            opacity: 0;
        }
        10%{
            opacity: 1;
        }
        20%,
        30%{
            opacity: 1;
            scale:1.03;
        }
        50%{
            opacity: 0;
        }
    }
     .g{
        background-color: #000;
        color: aquamarine;
     }
     .g:hover{
        background-color: aliceblue;
     }
</style>
</html>

>>>>>>> 0d6ffbefd18426f0179640b1e03407aefb468fa0
