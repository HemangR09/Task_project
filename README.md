# Task_project
<!DOCTYPE html>
<html lang="en">
<head>
    <title>WEB</title>
  <style>
    /*-------navber css-----*/
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    background-color: #f3f2f1;
}
.container{
    max-width: 1440px;
    margin:auto;
}
.navbar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 20px;
}
ul,li{
    display: inline-block;
}
li{
    margin-left: 20px;
}
.menu ul li a{
    padding: 10px 0px;
    text-decoration: none;
    color: black;
    font-size: 18px;
    font-weight: 700;
    transition: all o.3s;
}
.navbar .logo a{
    text-decoration: none;
    color: black;
    font-size: 30px;
    font-weight: 900;
    letter-spacing: 2px;
}
.menu li:hover a{
    color: orangered;
    border-bottom:3px solid orangered ;
}
/* .header{
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    z-index: 99;
} */
/*-------navber css end------*/
/* ---------home css---------- */
img{
    position:absolute;
    height: 670px;
    width:1440px;
}
.tham{
    position: relative;
    width:500px;
    padding-left: 200px;
    padding-top: 200px;
}
.tham h1{
    color: #fff;
    font-size: 50px;
    font-weight: 800;
}
.tham p{
    color: #fff;
}
.tham button{
    width: 200px;
    padding: 10px;
    margin-top: 15px;
    background-image:linear-gradient(blue,purple);
    border: none;
    color: #fff;
    font-size: 15px;
}
/* -------home css ends------ */
.work{
    margin-top: 200px;
    text-align: center;
}
.work h1{
    font-size: 40px;
    word-spacing: 5px;
    color: blue;
    padding-top: 10px;
    padding-bottom: 15px;
}
.work p{
    text-align: center;
}
.list{
    margin-left: 300px;
}
.row{
    width: 100%;
    display: flex;
}
.col{
    margin: 30px;
}
.box{
    width:200px;
    height: 200px;
    background-color:skyblue;
    border-radius: 10px;
    overflow: hidden;
    opacity: 0.9;
}
.less{
    margin-left: 305px;
}
.less .col{
    margin: 30px;
}
.box-1{
    width: 350px;
    height:500px;
    background-color:;
    margin-left: 300px;
}
.box-1 h1{
    padding-top: 50px;
    padding-left: 60px;
    padding-bottom: 20px;
    color: blue;
}
.box-1 p{
    padding-top: 0px;
    padding-left: 60px;
    padding-bottom: 5px;
}
.less button{
    width: 120px;
    padding: 7px;
    margin-top: 15px;
    margin-left: 60px;
    font-weight: 700;
}
.get{
    width: 100%;
    height: 200px;
    background-image:linear-gradient(blue,pink);
    background-color: blue;
    text-align: center;
    padding-top: 30px;
    color: #fff;
    margin-bottom: 30px;
}
.get button{
    width: 100px;
    padding: 7px;
    margin-top: 10px;
    background-image:linear-gradient(blue,pink);
    color: #fff;
    border: #fff solid 2px;
}
  </style>
</head>
<body>
    <!-------------navbar --------->
    <div class="header">
        <div class="container">
            <div class="navbar">
                <div class="logo">
                    <a href="#">NETWORKM5</a>
                </div>
                <div class="menu">
                    <ul>
                        <li><a href="#">HOME</a></li>
                        <li><a href="#">PAGES</a></li>
                        <li><a href="#">PORTFOLIO</a></li>
                        <li><a href="#">SHOP</a></li>
                        <li><a href="#">BLOG</a></li>
                        <li><a href="#">---</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <!-- ------navbar end----- -->
     <!---------home start------ -->
     <div class="home">
        <div class="container">
            <img src="https://tse1.mm.bing.net/th?id=OIP.EoJvVpBnjpiJr1JjS1P8jAHaE7&pid=Api&P=0&h=180" alt="">
            <div class="tham">
                    <h1>We,re<br>Creating<br>Producuts</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque hic in a officia adipisci sint illo porro voluptatem quas. Magnam voluptatem mollitia sint quia repudiandae!</p>
                    <button>Sign In Now</button>
            </div>
        </div>
     </div>
     <!-------home end----- -->
     <!----------deatils start=------- -->
     <div class="deatils">
        <div class="container">
            <div class="work">
                <h1>HOW does it Work?</h1>
                <p>Lorem ipsum dolor sit amet. Lorem ipsum dolor sit.<br>Lorem ipsum dolor sit amet.</p>
            </div>
            <div class="list">
                <div class="row">
                    <div class="col">
                        <div class="box">
                            <h1>Task <br>Managem <br>ent</h1>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus magnam praesentium in deserunt porro ipsam nam quisquam saepe amet dolorem? Inventore excepturi, repellendus omnis ab, iusto veritatis deserunt magni, laborum quia libero laudantium facilis labore animi blanditiis voluptates ipsum doloribus!</p>
                        </div>  
                    </div>
                    <div class="col">
                        <div class="box">
                            <h1>Automatio <br>n</h1>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, omnis modi </p>
                        </div>
                    </div>
                    <div class="col">
                        <div class="box">
                            <h1>Budgeting <br>Tools</h1>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis quasi iste aspernatur voluptate nobis nisi!</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
     </div>
     <div class="lernmore">
        <div class="container">
            <div class="less">
                <div class="row">
                    <div class="col">
                        <img src="https://cdn.pixabay.com/photo/2015/12/04/14/05/code-1076536_1280.jpg" alt="" style="width: 350px; height:500px;">
                    </div>
                    <div class="col">
                        <div class="box-1">
                            <h1>The <br>Planning & <br>Scheduling</h1>
                            <p>Plan</p>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Illum, ad! Lorem ipsum dolor sit amet.</p>
                            <p>Track</p>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum, iste! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Animi, ducimus?</p>
                            <button>Learn more</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
     </div>
     <div class="end">
        <div class="container">
            <div class="get">
                <h1>Get Awesome Features & <br>Layouts <br>Try Now!</h1>
                <button>Get Started</button>
            </div>
        </div>
     </div>
</body>
</html>
