# parksite.com

<html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
        <title>national park</title>
        <script src="scripts/mountainData.js"></script>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <nav>
                <h3>Nature Explore</h3>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="national.html">national</a></li>
                    <li><a href="moun.html">mountain</a></li>
                </ul>
                <i class="bi bi-three-dots"></i>
            </nav>
            <div class="content">
                <div class="cont">
                    <h1>national park</h1>
                    <p>welcome to national park</p>
                    <button>search</button>
                </div>
                <div class="park_bx">
                <div class="search_bx">
                    <div class="card">
                        <h4>loction <i class="bi bi-caret-down-fill"></i></h4>
                        <input type="text" placeholder="enter destination">
                    </div>
                    <div class="card">
                        <h4>Date <i class="bi bi-caret-down-fill"></i></h4>
                        <input type="date">
                    </div>
                    <div class="card">
                        <h4>people <i class="bi bi-caret-down-fill"></i></h4>
                        <input type="number" placeholder="amount of people">
                    </div>
                    <input type="button" value="explore">20px
                </div>
                <div class="trevel_bx">
                    <h4>upcoming national park to trevel</h4>
                    <div class="cards">
                        <div class="card">
                            <h3>Yellowstone National Park</h3> 
                            <!-- new -->
                            <img src="images/imgbox1.webp" alt="" srcset="">
                            <div class="btn_park">
                                <a href="">read</a>
                                <h5>califonia</h5>
                            </div>
                        </div>
                        <!-- new -->
                        <div class="card">
                            <h3>Arctic National Park</h3> 
                            <img src="images/img5.jpeg" alt="" srcset="">
                            <div class="btn_park">
                                <a href="">read</a>
                                <h5>Alaska</h5>
                            </div>
                        </div>
                            <div class="card">
                                <h3>Tenaya Lake</h3> 
                                <img src="images/img4.jpeg" alt="" srcset="">
                                <div class="btn_park">
                                    <a href="">read</a>
                                    <h5>califonia</h5>
                                </div>
                            </div>
                        <div class="card">
                            <h3>Gros Morne National Park</h3> 
                            <img src="images/img6.jpeg" alt="" srcset="">
                            <div class="btn_park">
                                <a href="">read</a>
                                <h5>Canada</h5>
                            </div>
                        </div>
                    </div>    
                </div>
            </div>
            </div>
        </header>
        <div class="offers">
            <h1>Best tour package offer for your adventure</h1>
            <p>chose your destination</p>
            <div class="cards">
                <div class="card">
                    <h3>River</h3>
                    <div class="img_text">
                        <img src="images/img7.png" alt="" srcset="">
                        <h4></h4>
                    </div>
                </div>
                <div class="card">
                    <h3>Mountains</h3>
                    <div class="img_text">
                        <img src="images/img8.jpeg" alt="" srcset="">
                        <h4></h4>
                    </div>
                </div>
                <div class="card">
                    <h3>Safari</h3>
                    <div class="img_text">
                        <img src="images/img9.webp" alt="" srcset="">
                        <h4></h4>
                    </div>
                </div>
                <div class="card">
                    <h3>iceland</h3>
                    <div class="img_text">
                        <img src="images/img10.webp" alt="" srcset="">
                        <h4></h4>
                    </div>
                </div>
                <!--  -->
                <!-- <div class="card"></div> -->
                <!-- <div class="card"></div> -->
                <!-- <div class="card"> -->
                    
                </div>
            </div>
        </div>
        
    </body>
    <script>
        console.log(mountainsArray)
        //array of object into html select option //
    </script>
</html>

