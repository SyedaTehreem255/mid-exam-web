# mid-exam-web
mid exam web programming
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>meteor</title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
    <header>
      <h1>meteor</h1>
        <nav>
            <ul>
                <li><a href="#introduction">introduction</a></li>
                <li><a href="#what we do">what we do</a></li>
                <li><a href="#our portfolio">our portfolio</a></li>
                <li><a href="#our blog posts">our blog posts</a></li>
                <li><a href="#contact us"contact us></a></li>
            </ul>
        </nav>
    </header>
    <!--intro section-->
    <section>
        <div class="introduction">
            <div>
                <p>introduction to creative meteor</p>
                
                <button>discover now</button>
            </div>
        </div>
    </section>
    <!--main and sections ofwhat we do-->
    <main>
        
        <section>
        
            <div flex-container="what we do">
                <div class="easy customizations" > 
                <h3>easy customizations</h3>
                we can make your projects by ur own choice 
                </div>
                <div class="creative ideas">
                    <h3>creative ideas</h3>
                    every single person working here presents his ideas and best are chosen for u
                </div>
                <div class="good profit">
                    <h3>good profit</h3>
                    we provide u services which are best in profit
                </div>
                <div class="open to public"> 
                    <h3>open to public</h3>
                    our services and work bpoth are open to public nothing is hidden
                </div>
            </div>
       
      </section>
      <section>
       <div class=" our portfolio">
        <p>our portfolio has dispayed the best work of ourprojects</p>
        <img src="Pictures/download (1).jfif" alt="city">
        <img src="Pictures/download (3).jfif" alt="workspace">
        <img src="Pictures/download (4).jfif" alt="technology">
        <img src="Pictures/download.jfif" alt="nature">
       </div>
      </section>
    </main>


</div>
</body>
</html>
* { 
    background-color: darkgrey;
    margin: 10px;
    padding: 40px;
}
header h1 {
    background-color: skyblue;
    font: 100;
}
header nav ul {
    background-color: rgb(214, 132, 177);

}
header nav ul li {
    background-color: black;
}.introduction {
    background-color:rgb(206, 118, 132) ;
}
.flex-container{
    display: flex;
    text-align: center;
    flex-basis: auto ;
    grid-template-rows: auto;
    grid-template-columns: auto;

}
.flex-items{
    display: flexbox;
    flex: justify;
    
}
section {
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    font-size: medium;
}
.whatwedo {
background-color:rgb(204, 154, 166)
}
div {
    text-align: center;
    padding: auto;
    border: 10px;
    border-color: brown;
}
.ourportfolio {
    image-resolution: 20px
}
.ourportfolio p {
    text-align: justify;
    color: black;
}
