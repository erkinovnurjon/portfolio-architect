<template >
      <div class="portfolio">
            <h3>Projects</h3>
            <div class="port">
                 <div class="content">
                  <div class="box">
                        <img src="./../assets/images/portfolio/image1.svg" alt=""> 
                         <p>Village Pt</p>
                  </div>
                  <div class="box">
                        <img src="./../assets/images/portfolio/image2.svg" alt=""> 
                         <p>Franklin</p>
                  </div>
                 </div>
                 <div class="content">
                  <div class="box">
                        <img src="./../assets/images/portfolio/image3.svg" alt=""> 
                         <p>Henderson</p>
                  </div>
                  <div class="box">
                        <img src="./../assets/images/portfolio/image4.svg" alt=""> 
                         <p>Hazelwood</p>
                  </div>
                 </div>
                 <div class="content">
                  <div class="box">
                        <img src="./../assets/images/portfolio/image5.svg" alt=""> 
                         <p>Martin St</p>
                  </div>
                  <div class="box">
                        <img src="./../assets/images/portfolio/image6.svg" alt=""> 
                         <p>Concord</p>
                  </div>
                 </div>
                 <div class="content">
                  <div class="box">
                        <img src="./../assets/images/portfolio/image7.svg" alt=""> 
                         <p>Houston St</p>
                  </div>
                  <div class="box">
                        <img src="./../assets/images/portfolio/image8.svg" alt=""> 
                         <p>Hillsboro</p>
                  </div>
                 </div>
                 <div class="content">
                  <div class="box">
                        <img src="./../assets/images/portfolio/image9.svg" alt=""> 
                         <p>Willow Ave</p>
                  </div>
                  <div class="box">
                        <img src="./../assets/images/portfolio/image10.svg" alt=""> 
                         <p>Brentwood</p>
                  </div>
                 </div>
            </div>
      </div>
</template>

<style scoped>
.portfolio{
      margin: 20px auto;
}
.box{
      margin: 15px 0;
}
.port{
      margin: 15px auto;
}
      h3{
            text-transform: uppercase;
            color: #000;
font-family: Arial;
font-size: 17px;
font-style: normal;
font-weight: 400;
line-height: 25.2px; /* 148.235% */
      }
      .content{
            display: flex;
            justify-content: space-between;
            align-items: center;
      }
       p{
            color: #000;
font-family: Arial;
font-size: 20px;
margin-top: 4px;
font-style: normal;
font-weight: 400;
line-height: 24px; /* 104.348% */
      }
</style>