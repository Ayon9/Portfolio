<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <style>
        *{
    margin: 0;
    padding: 0;
    border: 0;
}
body{
    max-width: 90%;
    margin: 0 auto;
    background-color:#1c1c1d;
}
header{
    margin: 5px;
}
header nav ul{
    background-color: aquamarine;
    color: rgb(132, 17, 226);
    text-align: center;
}
nav ul li{
    list-style: none;
    display: inline-block;
    padding: 5px;
    margin: 5px;
    font-style: italic;
    font-size: bold;
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    word-spacing: 15px;
}
nav ul li a{
    text-decoration: none;
    color: rgb(0, 0, 0);
    font-size: 25px;
}
hr{
    border: 1px solid black;
}
nav ul li:hover{
    color: aqua;
    background-color: yellow;
    cursor: pointer;
}
.content{
    height: 900px;
    background-color: aqua;
    display: flex;
    justify-content: center;
    align-items: center;
    padding:10px;
}
.content p{
    font-style: italic;
    font-size: bold;
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    word-spacing: 15px;
}
.image{
    margin-top:15px;
    margin-left: 15px;
}
img{
    width:275px;
}
span{
     font-style: italic;
    font-size: bold;
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    word-spacing: 15px;
}
.listcontent{
    position: absolute;
    top: 900px;
}

    </style>
    <div class="main">
        <header>
            <nav>
                <ul>
                    <li><a href="about">about</a></li>
                    <li><a href="blog">blog</a></li>
                    <li><a href="publication">publication</a></li>
                    <li><a href="project">project</a></li>
                    <li><a href="reposotories">reposotories</a></li>
                    <li><a href="cv">cv</a></li>
                    <li><a href="teaching">teaching</a></li>
                    <li><a href="people">people</a></li>
                </ul>
            </nav>
        </header>
        <hr>
         <div class="content">
            <div class="container">
                <h1>your name</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam, saepe recusandae quibusdam cum quis itaque animi dolorem cumque omnis iusto blanditiis consectetur aliquid alias sequi excepturi provident, officiis exercitationem error. Iure et fugit exercitationem numquam iusto consequuntur repellendus ipsum laudantium assumenda, praesentium hic, repellat soluta amet facere mollitia similique aliquid?</p>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Repellat cum ab recusandae ipsum distinctio. Sed, id sequi sint sit dolorem cum vitae expedita praesentium nisi saepe eius unde at! Laudantium aspernatur a error repellendus quae dicta pariatur, eaque facilis corrupti sint eum placeat aperiam non reprehenderit! Quasi dicta id qui, voluptate saepe voluptas dolores, fugiat ipsam aspernatur, quas dolorum ut dolorem quae illum iure molestiae modi impedit magni quaerat atque? Velit soluta, reprehenderit ducimus veritatis fuga ratione, rerum, perspiciatis animi ipsa praesentium corrupti recusandae aspernatur nostrum illum officia! Eligendi eum ipsa ducimus magnam minima, totam doloremque dolor quis. Vero corrupti veritatis, neque odio est maxime? Animi blanditiis molestias ullam enim assumenda, ipsa iure! Provident sed itaque doloremque alias quibusdam culpa ad iure dolorem! Laudantium possimus veritatis vel ratione impedit vitae saepe dolore nam aperiam ipsa commodi ipsam error provident illum illo, vero iusto distinctio magnam quo. Rerum nemo quam ipsam?</p>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ratione veniam voluptatum praesentium eveniet, minima totam officia perferendis distinctio ducimus nihil temporibus, numquam eos et repellendus nemo quidem facilis sequi consequatur? Error placeat aut, delectus veniam eveniet nihil hic velit numquam modi, nobis, nisi culpa. Minima perferendis fugit vel magnam, in, commodi obcaecati reprehenderit sunt eum excepturi doloremque omnis, optio maxime sit voluptatum molestiae delectus cumque similique quod aspernatur veritatis? Perspiciatis debitis at qui enim omnis quidem nulla optio rerum corrupti cum? Repudiandae possimus eaque ex. Soluta atque saepe nulla? Numquam, dolore unde voluptas hic sunt laudantium corporis perspiciatis commodi porro officia nemo culpa autem accusantium praesentium quidem maxime quasi, sint non voluptatum? Unde sapiente consequatur accusantium libero cumque, eaque porro velit sed inventore delectus amet laudantium reiciendis quam praesentium minima tempora beatae, autem ipsa esse enim veritatis! Fugit consequuntur explicabo modi! Eum qui alias accusantium debitis autem perferendis officia dicta.</p>
            </div>
            <div class="image">
             <img src="./prof_pic-480-ezgif.com-webp-to-jpg-converter.jpg" alt="https://alshedivat.github.io/al-folio/assets/img/prof_pic-480.webp">
                    <span>555 your office number </span><br>
                     <span>123 your address street</span> <br>
                    <span>Your City, State 12345</span>
                </div>
                    <span>news</span>
        <span>Jan 15, 2016	A simple inline announcement with Markdown emoji! :sparkles: :smile:</span>
        <span>Nov 07, 2015	A long announcement with details</span>
        <span>Oct 22, 2015	A simple inline announcement.</span>
        <span>latest posts</span>
        <span>Mar 26, 2025	a post with plotly.js</span>
        <span>Dec 04, 2024	a post with image galleries</span>
        <span>May 14, 2024	Google Gemini updates: Flash 1.5, Gemma 2 and Project Astra </span>
                </div>
            </div>
</body>
</html>
