<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
        <meta name="description" content="" />
        <meta name="author" content="" />
        <title>心領神會 服務平台</title>
        <link rel="icon" type="image/x-icon" href="assets/caticon.ico" />
        <!-- Font Awesome icons (free version)-->
        <script src="https://use.fontawesome.com/releases/v5.15.3/js/all.js" crossorigin="anonymous"></script>
        <!-- Google fonts-->
        <link href="https://fonts.googleapis.com/css?family=Lora:400,700,400italic,700italic" rel="stylesheet" type="text/css" />
        <link href="https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800" rel="stylesheet" type="text/css" />
        <!-- Core theme CSS (includes Bootstrap)-->
        <link href="css/styles.css" rel="stylesheet" />
        <link rel="stylesheet" type="text/css" href="css/button.css">
    </head>
    <body style="background-color:#d8d1c4;">
        <div class="wrapper">
            <!-- Navigation-->
            <nav class="navbar navbar-expand-lg navbar-dark navbg "id="mainNav" >
                <div class="container">
                    <a class="navbar-brand" href="index.html">
                        <img src="assets/img/logo1.jpg" alt="Logo" style="width:200px;">
                    </a>
                    <button style="color: black;" class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                    Menu
                    <i class="fas fa-bars"></i>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarResponsive" >
                        <ul class="navbar-nav ms-auto py-4 py-lg-0">
                            <li class="nav-item "><a class="nav-link px-lg-3 py-3 py-lg-4 navbara" href="
                            game.html"  style="font-size:20px;">遊戲列表</a></li>
                            <li class="nav-item "><a class="nav-link px-lg-3 py-3 py-lg-4 navbara" href="price.html"  style="font-size:20px;">價格方案</a></li>
                            <li class="nav-item "><a class="nav-link px-lg-3 py-3 py-lg-4 navbara" href="about.html"  style="font-size:20px;">關於我們</a></li>
                            <li class="nav-item "><button type="button" class="btn nav-link px-lg-3 py-3 py-lg-4 navbara" data-bs-toggle="modal" data-bs-target="#exampleModal" style="font-size:20px;">登入</button></li>
                            <li class="nav-item "><button type="button" class="btn nav-link px-lg-3 py-3 py-lg-4 navbara" data-bs-toggle="modal" data-bs-target="#exampleModal1" style="font-size:20px;">註冊</button></li>
                        </ul>
                    </div>
                </div>
            </nav>
            <!-- 登入 -->
            <div class="modal fade " id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                <div class="modal-dialog ">
                    <div class="modal-content back">
                        <div class="modal-body">
                            <form class="form1 bgform">
                                <img src="assets/img/sign.PNG" class="rounded mx-auto d-block imgsign" alt="...">
                                <br>
                                <div class="row">
                                    <label for="input1" class="col-4"><img src="assets/img/2.PNG" class="float-left imgicon" alt="...">信箱</label>
                                    <input type="text" class="form-control input1 col-8" id="input1">
                                </div>
                                <br>
                                <div class="row">
                                    <label for="input2" class="col-4"><img src="assets/img/3.PNG" class="float-left imgicon" alt="...">密碼</label>
                                    <input type="password" class="form-control input1 col-8" id="input2">
                                </div>
                                <center><button type="button" class="btn btnback back"><img src="assets/img/6.PNG" class="float-left imgicon" alt="...">登入</button></center>
                            </form>
                        </div>
                        
                    </div>
                </div>
            </div>
            <!-- 註冊 -->
            <div class="modal fade " id="exampleModal1" tabindex="-1" aria-labelledby="exampleModal1Label" aria-hidden="true">
            <div class="modal-dialog ">
                <div class="modal-content back">
                    <div class="modal-body">
                        <form class="form1 bgform">
                            <div class="row">
                                <label for="ainput1" class="col-4"><img src="assets/img/1.PNG" class="float-left imgicon" alt="...">店名</label>
                                <input type="text" class="form-control input1 col-8" id="ainput1">
                            </div>
                            <br>
                            <div class="row">
                                <label for="ainput2" class="col-4"><img src="assets/img/2.PNG" class="float-left imgicon" alt="...">信箱</label>
                                <input type="text" class="form-control input1 col-8" id="ainput2">
                            </div>
                            <br>
                            <div class="row">
                                <label for="ainput3" class="col-4"><img src="assets/img/3.PNG" class="float-left imgicon" alt="...">密碼</label>
                                <input type="text" class="form-control input1 col-8" id="ainput3">
                            </div>
                            <br>
                            <div class="row">
                                <label for="ainput4" class="col-4"><img src="assets/img/4.PNG" class="float-left imgicon" alt="...">手機</label>
                                <input type="text" class="form-control input1 col-8" id="ainput4">
                            </div>
                            <br>
                            <div class="row">
                                <label for="ainput5" class="col-4"><img src="assets/img/5.PNG" class="float-left imgicon" alt="...">地址</label>
                                <input type="text" class="form-control input1 col-8" id="ainput5">
                            </div>
                            <center><button type="button" class="btn btnback back"><img src="assets/img/6.PNG" class="float-left imgicon" alt="..."> 註冊</button></center>
                        </form>
                    </div>
                    
                </div>
            </div>
        </div>
        <!-- 註冊結束 -->
            <!-- Page Header-->
            <header class="masthead" style="background-image: url('assets/img/banner.jpg')">
                <div class="container position-relative px-4 px-lg-5">
                    <div class="row gx-4 gx-lg-5 justify-content-center">
                        <div class="col-md-10 col-lg-8 col-xl-7">
                            <div class="site-heading">
                                <h1>心領神會</h1>
                                <span class="subheading">Just want to keep a cat</span>
                            </div>
                        </div>
                    </div>
                </div>
            </header>
            
            
            
            <div class="container">
                <div class="row">
                    
                    <div class="col-4 col-md-4">
                        <a href="servisemore.html"><div class="container1">
                            <img src="assets/img/服務列表/poster.png" alt="Avatar" class="img-index">
                            <div class="indexoverlay"><h4 style="padding-top:15%; color: #745E4D;">專屬貓咪猜謎海報</h4>
                                <p style="color:black; padding: 0% 10% 0% 10%;">依據貓咪的基本資料與特性進行客製化設計，提供客人在享用餐點、嚕貓外『認識』貓咪的機會。</p></div>
                            </div></a>
                        </div>
                        
                        <div class="col-4 col-md-4">
                            <a href="servisemore.html"><div class="container1">
                                <img src="assets/img/服務列表/introduction.png" alt="Avatar" class="img-index">
                                <div class="indexoverlay"><h4 style="padding-top:15%; color: #745E4D;">貓咪介紹網頁<br>(手機版)</h4>
                                    <p style="color:black; padding: 0% 10% 0% 10%;">藉由猜謎小遊戲的連結，進而了解店家的所有資訊，包括領養流程、未領養貓咪等等。</p></div>
                                </div></a>
                            </div>
                            <div class="col-4 col-md-4">
                                <a href="servisemore.html"><div class="container1">
                                    <img src="assets/img/服務列表/develop.png" alt="Avatar" class="img-index">
                                    <div class="indexoverlay"><h4 style="padding-top:15%; color: #745E4D;">客製化貓咪互動APP</h4>
                                        <p style="color:black; padding: 0% 10% 0% 10%;">針對店家的貓咪外型客製化的養成遊戲，克服了距離的問題，進而提高客人的回店率以及領養率。</p></div>
                                    </div></a>
                                </div>
                                
                            </div>
                        </div>
                        <br>
                        <p class="h6" style="color:#8C3839;margin: 0% 5%;">以上三種合成基本套件。第一次使用本平台的店家，請訂閱此套件。我們將為你打造運用CRM、Pipeline理論的客製服務</p><br>
                    </div>
                    
                    <footer class="border-top" style="background-color:#5b6a7b;">
                        <div class="container-fluid px-4 px-lg-5 " >
                            <div class="row gx-4 gx-lg-5 justify-content-center">
                                <div class="col-md-10 col-lg-8 col-xl-7">
                                    <ul class="list-inline text-center">
                                        <li class="list-inline-item">
                                            <a href="#!">
                                                <span class="fa-stack " style="font-size:30px;">
                                                    <i class="fas fa-circle fa-stack-2x"></i>
                                                    <i class="fab fa-facebook fa-stack-1x fa-inverse"></i>
                                                </span>
                                            </a>
                                        </li>
                                        <li class="list-inline-item">
                                            <a href="#!">
                                                <span class="fa-stack " style="font-size:30px;">
                                                    <i class="fas fa-circle fa-stack-2x"></i>
                                                    <i class="fab fa-instagram fa-stack-1x fa-inverse"></i>
                                                </span>
                                            </a>
                                        </li>
                                    </ul>
                                    <div class="small text-center">Copyright &copy;心領神會-服務平台</div>
                                </div>
                            </div>
                        </div>
                    </footer>
                    <!-- Bootstrap core JS-->
                    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"></script>
                    <!-- Core theme JS-->
                    <script src="js/scripts.js"></script>
                </body>
            </html>
