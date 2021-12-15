# urok99
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<header class="header">
    <nav>
        <div class="menu">
            <ul>
                <li class="f1">Microsoft</li>
                <li class="f1">Office</li>
                <li class="f1">Xbox</li>
                <li class="f1">Windows</li>
                <li class="f1">Поддержка</li>
            </ul>
            <a href="https://www.microsoft.com/ru-ru""><img class="logo" src="https://www.logaster.com/blog/wp-content/uploads/2020/03/1111.png" alt="ZARA" ></a>
        </div>
    </nav>
    
</header>
<body>
    <div class="Content">
        <ul>Статьи:
            <li><a href="https://cyberleninka.ru/article/c/mathematics">Математика</a></li>
            <li><a href="https://cyberleninka.ru/article/c/computer-and-information-sciences">Компьютерные и информационные науки</a></li>
            <li><a href="https://cyberleninka.ru/article/c/economics-and-business">Экономика и бизнес </a></li>
            <li><a href="https://cyberleninka.ru/article/c/mechanical-engineering">Механика и машиностроение</a></li>
        </ul>  
    </div>
    <div class="text">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat officia adipisci laboriosam doloribus maiores possimus deserunt distinctio corrupti, autem voluptates?</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi, quae? Inventore, totam dolorem fugit aliquam assumenda pariatur. Architecto ipsum eius nobis magni mollitia deleniti eligendi doloribus tempora perspiciatis eveniet at voluptates veritatis alias nemo quod fuga, vel sit officiis necessitatibus!</p>
    </div>
    <div class="img">
        <img src="https://tehnot.com/wp-content/uploads/2015/08/microsoft_black_1.jpg" alt="">
        <img src="http://www.capital.ua/uploads/news/2020/03/17/09f7a5e65cf28e101e41f9cb12709eda38c2442f.jpg" alt="">
        <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/i/0889c019-dfc3-4e24-85ff-d441c332e4bd/dbc2fzo-fc7b0c6d-1656-42b2-8493-291acb05dafa.png" alt="">
    </div>



    <Footer>
        <div id="social">
            <a href="https://www.facebook.com/" target="_blank"><img src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Facebook_colored_svg_copy-256.png" alt=""></a>
            <a href="https://www.instagram.com/?hl=ru" target="_blank"><img src="https://cdn2.iconfinder.com/data/icons/social-icons-33/128/Instagram-256.png" alt=""></a>
            <a href="https://vk.com/" target="_blank"><img src="https://cdn2.iconfinder.com/data/icons/social-media-applications/64/social_media_applications_32-vk-256.png" alt=""></a>
            <h4 id="prava">Все права защищены &copy; </h4>
        </div>
        
    </Footer>
    
</body>
</html>
                          
                          
                          
                          CSS
 header{
    margin: 20px;
    padding: 10px;
    border: 2px solid blue;
    
}

body{
    border: 2px solid red;
    padding: 10px;

}

.text{
    padding-left: 30px;
}
.logo{
    width: 600px;
    height: 110px;
    margin: auto;
    padding: 10px;
    position: absolute;
    top: 40px;
    right: 20px;
    background: url(https://www.microsoft.com/ru-ru);
    
}
.f1{
    display: inline-block;
    padding: 30px;
}
.content{
    left: 100px;
}
.f1{
    left: 200px;
}




footer #social img{
    height: 30px;
    width: 30px;
    margin-right: 10px;
    right: 30px;
}
footer{
    border: 2px solid blue;
    background-color: skyblue
}
#prava{
    float: right;
    width: 13%;
    margin: 15px;
}

                          
                          
                          
