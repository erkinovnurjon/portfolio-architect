<template >
      <div class="footer">
           <div footer-left>
              <img src="./../assets/images/port/logo.svg" alt="">
              <h4>Powered by Webflow</h4>
           </div>
           <div class="footer-right">
                <ul>
                  <li>Password</li>
                  <li>400</li>
                </ul>
                <ul>
                  <li>Licenses</li>
                  <li>Style Guided </li>
                  <li>Changelog</li>
                </ul>
                <ul>
                  <li>Twitter</li>
                  <li>Instagram</li>
                </ul>
           </div>
      </div>
</template>
<script>
export default {
      
}
</script>
<style  >
      .footer{
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 40px 0;
      }
     
     h4{
      color: #000;
font-family: Arial;
font-size: 17px;
font-style: normal;
font-weight: 400;
line-height: 25.2px; /* 148.235% */
text-decoration-line: underline;
padding: 15px 0;
     }
      .footer-right{
            display: flex;
            justify-content: space-around;
            align-items: center;
            gap: 90px;
      }
      li{
            list-style: none;
            color: #000;
font-family: Arial;
font-size: 17px;
font-style: normal;
font-weight: 400;
line-height: 25.2px; /* 148.235% */
      }
</style>