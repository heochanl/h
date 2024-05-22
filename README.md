<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog Page</title>
    <style>
    body {
        background-color: rgb(53, 177, 218);
        font-family: Arial, 'Trebuchet MS', 'sans-serif';
        margin: 0px;
    }
    
    header {
        border: 1px solid rgb(138, 150, 160);
        color: #efe5d0;
        margin: 0px;
        text-align: center;
        padding: 5px;
    }
    
    h1 {
        margin: 0px;
    }
    
    section#main {
        float: left;
        width: 70%;
        height: 200px;
        background-color: rgb(253, 58, 211);
    }
    
    nav {
        float: left;
        width: 30%;
        height: 200px;
    }
    
    footer {
        background-color: rgb(13, 200, 182);
        color: whitesmoke;
        text-align: center;
        padding: 10px;
        margin: 0px 0px 0px 0px;
        font-size: 90%;
        clear: both;
    }
</style>
    <header>My Blog Page</header>
    <nav>
        <h1>Links</h1>
        <ul>
            <li><a href="index.html">HOME</a></li>
            <li><a href="1.html">1</a></li>
            <li><a href="2.html">2</a></li>
            <li><a href="3.hmtl">3</a></li>
        </ul>
        <figure>
            <img width="85" height="85" src="man.png.jpg" alt="홍길동"/>
            <figcaption>홍길동</figcaption>
        </figure>
    </nav>
    <section id="main">
        <article>
            <h1>Semantic Tags</h1>
            <p>
                시맨틱 요소(Semantic elements)들은 브라우저에게 요소의 의미나 목적을 명확하게 알려주는 요소이다.
            </p>
        </article>
        <article>
            <h1>div와 span</h1>
            <p>div은 "divide"의 약자로서 페이지를 논리적인 섹션으로 분리하는데 사용되는 태그이다. span요소는 인라인 요소로서 텍스트를 위한 컨테이너로 사용할 수 있다.</p>
        </article>
    </section>
    <footer>Copyright (c) 2023 Hong</footer>
</body>
</html>
