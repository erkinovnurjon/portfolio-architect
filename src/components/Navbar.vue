<template >
      <nav class="navbar">
           <div class="nav-left">
            <img src="./../assets/images/port/logo.svg" alt="logo">
           </div>
           
           <ul>
            <li>
                  Projects
            </li>
            <li>
                  Info
            </li>
           </ul>
           
      </nav>
</template>
<script>
export default {
      
}
</script>
<style scoped >
      .navbar{
            
            background: #FFF;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 15px;
      }
      ul{
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 25px;
      }
      li{
            list-style: none;
            color: #000;
font-family: Arial;
font-size: 17px;
font-style: normal;
font-weight: 400;
line-height: 25.2px; /* 148.235% */
text-transform: uppercase;
      }
      li:hover{
            color: #a55efc;
            
      }
      li:nth-child(1):hover::after{
       content: "";
            position: absolute;
            width: 85px;
            height: 2px;
            background: #000;
            top: 40px;
            
            margin-left: -88px;
            transition: ease all 1s;
      }
      li:hover::after{
            content: "";
            position: absolute;
            width: 40px;
            height: 2px;
            background: #000;
            top: 40px;
            margin-left: -40px;
            transition: ease-in all 1s;
      }
</style>