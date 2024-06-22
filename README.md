# frontenddevelopment 

#html
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionhome">
        <div class="bg-1">
            <div>
                <h1 class="heading-main">TODAY's NEWS</h1>
                <p class="para-main">The words behind the headlines. <br />leading experts</p>
            </div>
            <div class="d-flex flex-column">
                <div class="d-flex flex-row">
                    <div class="bg-images" onclick="display('sectiontechnology')">
                        <img class="bg-imagestyle" src="https://assets.ccbp.in/frontend/static-website/articles-technology-icon-img.png" />
                        <p>Entertainment</p>
                    </div>
                    <div class="bg-images" onclick="display('sectionscience')">
                        <img class="bg-imagestyle" src="https://assets.ccbp.in/frontend/static-website/articles-science-icon-img.png" />
                        <p>Science&Technology</p>
                    </div>
                </div>

                <div class="d-flex flex-row">
                    <div class="bg-images" onclick="display('sectionhealthcare')">
                        <img class="bg-imagestyle" src="https://assets.ccbp.in/frontend/static-website/articles-healthcare-icon-img.png" />
                        <p>health care</p>
                    </div>
                    <div class="bg-images" onclick="display('sectionbusiness')">
                        <img class="bg-imagestyle" src="https://assets.ccbp.in/frontend/static-website/articles-business-icon-img.png" />
                        <p>Bussiness</p>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div id="sectiontechnology">
        <div class="bg-1">
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-technology-c1-img.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-technology-c2-img.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-technology-c3-img.png" class="d-block w-100" alt="...">
                    </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>


            <h1 class="heading-main"> List of the topics</h1>
            <ul>
                <li class="para-main">Performance Art</li>
                <li class="para-main">Filmy Updates</li>
                <li class="para-main">What does Entertainment do?</li>
                <li class="para-main">Music Concerts</li>
            </ul>
            <div class="button-style">
                <button class="button" onclick="display('sectionhome')">Back </button>
            </div>

        </div>
    </div>

    <div id="sectionscience">
        <div class="bg-1">
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-science-c1-img.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-science-c2-img.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-science-c3-img.png" class="d-block w-100" alt="...">
                    </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>


            <h1 class="heading-main"> List of the topics</h1>
            <ul>
                <li class="para-main">Biological</li>
                <li class="para-main">Medical inventions</li>
                <li class="para-main">Geological</li>
                <li class="para-main">NASA inventions</li>
            </ul>
            <div class="button-style">
                <button class="button" onclick="display('sectionhome')">Back </button>
            </div>

        </div>
    </div>





    <div id="sectionhealthcare">
        <div class="bg-1">
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-healthcare-c1-img.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-healthcare-c2-img.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-healthcare-c3-img.png" class="d-block w-100" alt="...">
                    </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>


            <h1 class="heading-main"> List of the topics</h1>
            <ul>
                <li class="para-main">Daily Dose</li>
                <li class="para-main">covid updates</li>
                <li class="para-main">Health insurance</li>
                <li class="para-main">Medical Tourism</li>
            </ul>
            <div class="button-style">
                <button class="button" onclick="display('sectionhome')">Back </button>
            </div>

        </div>
    </div>


    <div id="sectionbusiness">
        <div class="bg-1">
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-business-c1-img.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-business-c2-img.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="https://assets.ccbp.in/frontend/static-website/articles-business-c3-img.png" class="d-block w-100" alt="...">
                    </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>


            <h1 class="heading-main"> List of the topics</h1>
            <ul>
                <li class="para-main">business models</li>
                <li class="para-main">21st century</li>
                <li class="para-main">traditional business approaches</li>
                <li class="para-main">how to go from 0 to 1?the sturtup 101</li>
            </ul>
            <div class="button-style">
                <button class="button" onclick="display('sectionhome')">Back </button>
            </div>

        </div>
    </div>



    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>



#css
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

.heading-main {
    color: #ffffff;
    font-size: 38px;
}

.bg-1 {
    background-color: #225db0;
    padding: 15px;
    height: 100vh;
    width: 100vw;
}

.para-main {
    color: #ffffff;
    font-size: 18px;
}

.bg-images {
    background-color: #ffffff;
    height: 110px;
    width: 180px;
    margin-right: 10px;
    margin-bottom: 10px;
    border-radius: 6px;
    text-align: center;
    padding: 10px;
}

.bg-imagestyle {
    height: 50px;
    width: 50px;
}

.button {
    color: #1f2933;
    background-color: #225db0;
}

.button-style {
    text-align: center
}
