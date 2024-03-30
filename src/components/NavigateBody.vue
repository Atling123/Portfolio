
<template>
  <div class="line"></div>
  <div id="home"></div>
  <div class="portfolio-introduction ">
    <!-- <div class="container">
      <h2 class="section-title">Welcome to My Portfolio</h2>
    <div class="card bg-light p-3">
      <img class="card-img-top rounded" alt="Image" src="Latrel.png" >
    </div>
      <p class="introduction-text">
        Hello and welcome to my portfolio! My name is Latrell S. Ligan, and I am a passionate Information Technology student dedicated to exploring the ever-evolving world of technology. Throughout my academic journey in CORDOVA PUBLIC COLLEGE, I've delved deep into various aspects of IT, from programming and software development to network administration and cybersecurity.
      </p>
    </div> -->

    <div class="row justify-content-center">
          <div class="col-md-4">
              <div class="card bg-light p-3">
                  <img class="card-img-top rounded" alt="Image" src="Latrel.png">
              </div>
          </div>
          <div class="col-md-6">
              <h2 class="fw-bold mb-5 mt-5">Welcome to My Portforlio</h2>
              <div class="row">
                  <div class="col-md-12">
                      <h5>
                        Hello and welcome to my portfolio! My name is Latrell S. Ligan, and I am a passionate Information Technology student dedicated to exploring the ever-evolving world of technology. Throughout my academic journey in CORDOVA PUBLIC COLLEGE, I've delved deep into various aspects of IT, from programming and software development to network administration and cybersecurity.
                      </h5>
                  </div>
                  <div class="col-md-12 mt-4">
                      <h5>
                        I have honed my skills in various technologies, including but not limited to Laravel, Bootstrap, CSS, JavaScript, PHP, MySQL, HTML, and Vue.js. Through hands-on projects and continuous learning, I strive to stay abreast of the latest advancements in the IT landscape, ensuring that I am well-equipped to tackle any challenge that comes my way.                      </h5>
                  </div>
              </div>
          </div>
      </div>

  </div>

  <div class="line"></div>
  <div class="Socials">
       <h2 class="section-title">CHECK ME OUT IN MY SOCIALS</h2>
            <div class="row justify-content-evenly px-lg-0 px-md-3 px-5">
                <div class="col-lg-2 col-md-4 text-center py-4 my-3">
                    <a href="https://twitter.com/latrelligan">
                      <img src="x.png" width="80px" title="X/Twitter" class="zoom-in-effect">
                    </a>
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3">
                <a href="https://github.com/Atling123">
                  <img src="github.png" width="80px" title="Github" class="zoom-in-effect">
                </a>
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3">
                  <a href="https://www.facebook.com/latrell.ligan?mibextid=ZbWKwL">
                    <img src="fb.png" width="80px" title="Facebook" class="zoom-in-effect">
                  </a>  
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3">
                  <a href="https://www.instagram.com/latrelligan/">
                    <img src="ig.png" width="80px" title="Instagram" class="zoom-in-effect">
                  </a>  
                </div>
            </div>
        </div>

<div class="line"></div>
<div class="Skills">
<h2 class="pt-4 mb-4 text-center fw-bold stylish-font3">Skills</h2>
    <div class="row justify-content-evenly px-lg-0 px-md-3 px-5">
        <div class="col-lg-3 col-md-4 text-center py-4 my-3">
          <img src="laravel.png" width="80px" title="Laravel" class="zoom-in-effect" data-bs-toggle="tooltip" data-bs-placement="top">
          <p5> LARAVEL</p5>
        </div>
        <div class="col-lg-3 col-md-4 text-center py-4 my-3">
            <img src="bootstrap.png" width="80px" title="Bootstrap" class="zoom-in-effect">
            <p5> BOOTSTRAP</p5>
        </div>
        <div class="col-lg-3 col-md-4 text-center py-4 my-3">
            <img src="css.png" width="80px" title="CSS" class="zoom-in-effect">
            <p5> CSS</p5>
        </div>
        <div class="col-lg-3 col-md-4 text-center py-4 my-3">
            <img src="js.png" width="80px" title="JavaScript" class="zoom-in-effect">
            <p5> JavaScript</p5>
        </div>
        <div class="col-lg-3 col-md-4 text-center py-4 my-3">
            <img src="php.png" width="140px" title="PHP" class="zoom-in-effect">
            <p5> PHP</p5>
        </div>
        <div class="col-lg-3 col-md-4 text-center py-4 my-3">
            <img src="sql.png" width="130px" title="SQL" class="zoom-in-effect">
            <p5> MYSQL</p5>
        </div>
        <div class="col-lg-3 col-md-4 text-center py-4 my-3">
            <img src="html.png" width="80px" title="HTML" class="zoom-in-effect">
            <p5> HTML</p5>
        </div>
        <div class="col-lg-3 col-md-4 text-center py-4 my-3">
            <img src="vue.png" width="100px" title="Vue.js" class="zoom-in-effect">
            <p5> VUE.js</p5>
        </div>
    </div>
  </div>
</template>


<style scoped>
 .card {
    box-shadow: 0 1opx 25px rgb(0, 0, 0, 0.2);
    width: 60%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

.line {
  height: 1px;
  background-color: rgb(239, 228, 228); /* Change color as needed */
  margin: 20px 100; /* Adjust spacing as needed */
}

.card-img-top {
  width: 100%;
  height: 400px;
}

.portfolio-introduction {
  padding: 50px 0;
  background-color: #989696;
}

.Socials{
  padding: 50px 0;
  background-color: #989696;
}

.Skills{
  padding: 50px 0;
  background-color: #989696;
}

.line {
  height: 1px;
  background-color: rgb(239, 228, 228); /* Change color as needed */
  margin: 20px 100; /* Adjust spacing as needed */
}

.container {
  max-width: 800px;
  margin: 0 auto;
}

.section-title {
  font-size: 32px;
  font-weight: bold;
  margin-bottom: 30px;
}

.introduction-text {
  font-size: 18px;
  line-height: 1.6;
  margin-bottom: 20px;
  margin-top: 30px;
   color: #1d1a1a;
}
</style>
