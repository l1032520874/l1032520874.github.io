<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Document</title>
</head>
<style>  
    .login_content {  
      position: absolute;  
      text-align: center; 
      min-width: 450px;   
    }  

    .login_content div:after, .login_content div:before {  
      background: #000;  
      content: "";  
      height: 1px;  
      position: absolute;  
      top: 50%;  
      width: 20%; 
    }  
  
    .login_content div:before {  
      left: 0%;  
    }  
  
    .login_content div:after {  
      right: 0;  
    }  
</style>  

</head>  
<body>  

<div class="login_content">  
  <div>中间文字，两边横线</div>  
</div>

</body>
</html>
