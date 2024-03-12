# HubLearn
HTML CODE:

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="sectionHome">
        <div class="bg-container">
            <h1 class="home-heading">Empower yourself</h1>
            <P class="home-paragraph">By learning new courses from worlds leading experts"</p>
            <div class="home-card d-flex flex-row ">
                <div class="card-1 text-center" onclick="display('sectionTechnology')">
                    <img src="https://assets.ccbp.in/frontend/static-website/articles-technology-icon-img.png" class="home-image"/>
                    <h1 class="card-heading">Technology</h1>
                </div>
                <div class="card-1" onclick="display('sectionScience')">
                    <img src="https://assets.ccbp.in/frontend/static-website/articles-science-icon-img.png" class="home-image"/>
                    <h1 class="card-heading">Science</h1>
                </div>
            </div>
            <div class="home-card d-flex flex-row">
                <div class="card-1" onclick="display('sectionHealth')">
                    <img src="https://assets.ccbp.in/frontend/static-website/articles-healthcare-icon-img.png" class="home-image"/>
                    <h1 class="card-heading">Health Care</h1>
                </div>
                <div class="card-1" onclick="display('sectionBusiness')">
                    <img src="https://assets.ccbp.in/frontend/static-website/articles-business-icon-img.png" class="home-image"/>
                    <h1 class="card-heading">Business</h1>
                </div>
            </div>
        </div>
    </div>
    <div id="sectionTechnology">
        <div class="bg-container">
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
            <h1 class="heading">List of Topics</h1>
            <ul class="unordered-list">
                <li class="list-item">Artifical Intelligence</li>
                <li class="list-item">Data Science</li>
                <li class="list-item">Machine Learning</li>
                <li class="list-item">Internet Of Things</li>
                <li class="list-item">Blockchain</li>
                <li class="list-item">Virtual Reality</li>
                <li class="list-item">Robotic Process Automation (RPA)</li>
            </ul>
            <div class="button-1 text-center">
                <button class="button" onclick="display('sectionHome')">Back</button>
            </div>
        </div>
    </div>
    <div id="sectionScience">
        <div class="bg-container">
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
            <h1 class="heading">List of Topics</h1>
            <ul class="unordered-list">
                <li class="list-item">Biology</li>
                <li class="list-item">Zoology</li>
                <li class="list-item">Cardiology</li>
                <li class="list-item">Chemistry</li>
                <li class="list-item">Bio Chemistry</li>
                <li class="list-item">Nano Science</li>
                <li class="list-item">Astronomy</li>
            </ul>
            <div class="button-1 text-center">
                <button class="button" onclick="display('sectionHome')">Back</button>
            </div>
        </div>
    </div>
    <div id="sectionHealth">
        <div class="bg-container">
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
            <h1 class="heading">List of Topics</h1>
            <ul class="unordered-list">
                <li class="list-item">Infrastructure Management</li>
                <li class="list-item">Latest in Health Care</li>
                <li class="list-item">Pharmaceuticals</li>
                <li class="list-item">COVID-19</li>
            </ul>
            <div class="button-1 text-center">
                <button class="button" onclick="display('sectionHome')">Back</button>
            </div>
        </div>
    </div>
    <div id="sectionBusiness">
        <div class="bg-container">
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
            <h1 class="heading">List of Topics</h1>
            <ul class="unordered-list">
                <li class="list-item">Business Models</li>
                <li class="list-item">21st Century Business Skills</li>
                <li class="list-item">Traditional Business Approaches</li>
                <li class="list-item">How to go from 0 to 1? The startup 101</li>
            </ul>
            <div class="button-1 text-center">
                <button class="button" onclick="display('sectionHome')">Back</button>
            </div>
        </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>

CSS CODE:

@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");
.bg-container {
    background-color: #225db0;
    height: 100vh;
    padding: 25px;
}
.home-heading {
    color: white;
    font-size: 30px;
    font-family: "roboto";
}
.home-paragraph {
    color: white;
    font-size: 15px;
    font-family: "roboto";
}
.card-1 {
    background-color: white;
    border-radius: 8px;
    height: 15vh;
    width: 50vw;
    text-align: center;
    margin: 8px;
}
.home-image {
    height: 8vh;
    margin-top: 8px;
}
.card-heading {
    color: #1f2933;
    font-size: 15px;
    font-family: "roboto";
}
.heading {
    color: white;
    font-size: 28px;
    font-family: "roboto";
    padding: 10px;
}
.unordered-list {
    color: white;
    font-size: 15px;
    font-family: "roboto";
}
.button {
    background-color:  #225db0;
    color: white;
    border-color: white;
}
.list-item {
    margin-bottom: 8px;
} 
