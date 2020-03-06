Reminder

Press minus + shift + s and return to chop/fold long lines!

Show folder content: ls -la

https://youtu.be/ia0kWn2FAgc

*************************************************************************
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.4.1/css/bootstrap.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.min.css">
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/owl-carousel/1.3.3/owl.carousel.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/owl-carousel/1.3.3/owl.carousel.css">
<title>Title</title>
</head>
<body>
        <div id="wrapper">
            <div id="slider-area" class="owl-carousel">
                <div style="background-image: url(abc.jpg);"></div>
                <div style="background-image: url(abc.jpg);"></div>
                <div style="background-image: url(abc.jpg);"></div>
            </div>
        </div>   
        <div class="slider-text">
            <h2>Welcome to the website</h2>
            <p>abcd</p>
            <a href="#a">ddd</a>
        </div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.4.1/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/owl-carousel/1.3.3/owl.carousel.min.js"></script>
<script>
    $('.owl-carousel').owlCarousel({
    items:1,
    loop:true,
    autoplay:true,
    responsive:{
        0:{
            items:1
        },
        600:{
            items:1
        },
        1000:{
            items:1 
        }
    }
}) 
</script>
</body>
</html>
###############################################################################################################################
body{
    margin: 0;
    padding: 0;
}
#wrapper{
    position: relative;
    height: 100vh;
}
#slider-area{
    position: absolute;
    height: 100vh;
    width: 100%;
    top: 0;
    left: 0;

}
#slider-area .owl-item div{
    height: 100vh;
    width: 100%;
    background-repeat: no-repeat;
    -webkit-background-size:cover;
    background-size: cover;
    background-position: 50% 50%;

}
.slider-text{
    position: absolute;
    left:30%;
    z-index: 10;
    top: 40%;
    text-align: center;
}
.slider-text h2{
    text-transform: uppercase;
    font-size: 40px;
    color:#fff;
}
.slider-text p{
    font-size: 10px;
    color:#fff;
}
.slider-text a{
    text-decoration: none;
    text-transform: uppercase;
    background: tomato;
    padding: 15px 25px;
    display: inline-block;
    -webkit-border-radius:25px;
    -moz-border-radius:25px;
    border-radius: 25px;
    color:#fff;
}
