<template>
  <div class="screen">
        <nav>
            <div class="title"> Museum'IT</div>
          <div class="header-left">
            <a href="" class="button-left">Home</a>
            <a href="" class="button-left">Stories</a>
            <a href="" class="button-left">Collections</a>  
            <a href="" class="button-left">SignUp</a>
            <a href="./LoginPage.vue" class="button-left active">Login</a>
            <i class="fa fa-search search-icon"></i>
          </div>
          </nav>
        </div>

        <div class="container">
        <div class="loginbox">
    <img  class="image3">
    <h1>Login Here</h1>
               <form>
                   <p>Username</p>
                   <input type="text" name="" placeholder="Enter Username">                
                   <p>Password</p>
                   <input type="password" name="" placeholder="Enter password">
                   <div class="Button">                 
                   <input type="submit" name="" value="login">
                   </div>
                   <a href="">Forgot Your Password?</a><br>
                   <a href="">Don't have an account?</a>                            
               </form> 
           </div>
           </div>
</template>

<script>
export default {

}
</script>

<style>
.screen{
    width: 100%;
    height: 8vh;

}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: -60px;
}
.title {
  align-items: center;
  margin-top: 10px;
  margin-left: 200px;
  font-size:30px;
  font-weight: bold;
  font-family: "Open Sans", sans-serif;
}

.header-left {
  align-items: center;
  margin-top: 10px;
  margin-right: 40px;
}
.button-left {
  font-family: "Open Sans", sans-serif;
  font-size: 14px;
  color: black;
  border: none;
  border-radius: 20px;
  padding-top: 8px;
  padding-right: 15px;
  padding-left: 15px;
  padding-bottom: 8px;
  font-weight: 600;
  margin-right: 4px;
  text-decoration: none;
}
.button-left:hover {
  background-color: rgb(194, 131, 131);
}
.button-left.active {
  background-color: rgb(76, 36, 233);
}
.search-icon{
  align-items: center;
  margin-top: 10px;
  margin-right: 10px;
  cursor: pointer;
}



.container{
    width:100%;
    height:90vh;
    display: flex;
    margin-top: 30px;
    background-image: url("C:\Users\Siva Ratnam Pachava\OneDrive\Desktop\main-vue-p\src\assets\backimage.jpg");
    background-size: cover;
    background-repeat: no-repeat;
}
.loginbox{
    align-items: center;
    position: absolute;
    width:670px;
    height:430px;
    margin-left: 300px;
    background: #a7aca0;
    box-sizing:border-box; 
    padding: 70px 30px;
    margin-top: 70px;   
}
.image3{
    width:100px;
    height:80px;
    border-radius:50%;
    position: absolute;
    left: 260px;
    top: -50px;
    background-image: url('C:\Users\Siva Ratnam Pachava\OneDrive\Desktop\main-vue-p\src\assets\image1.jpg');
}
h1{
    margin:0;
    padding: 0 0 20px;
    text-align: center;
    font-size: 42px;
}
.loginbox p{
    margin:0;
    padding:0;
    font-weight: bold;
    font-size: 20px;
    margin-left: 90px;
    display: flex;
}
.loginbox input{
    width: 70%;
    margin-bottom: 20px;
}
.loginbox input[type="text"], input[type="password"]
{
    border: none;
    border-bottom: 1px solid #fff;
    background: transparent;
    height: 40px;
    font-size: 18px;
}
form .Button
{
    height: 25px;
    margin: 25px 170px;
    border-radius: 5px;
    padding: 0px 200px 0px 100px;
    width: 100%;
    
}
.loginbox input[type="submit"]
{
    border: none;
    width: 10%;
    background: rgb(26, 24, 24);
    height: 40px;
    font-size: 20px;
    text-align: center;
    outline:none;
    color:#fff;
    border-radius: 5px;
    display:flex;
    flex-wrap: wrap;
    padding: 0px 50px 0px 10px;
}
.loginbox input[type="submit"]:hover
{
    cursor: pointer;
    background: #aaa38d;
    color: #000;
    position: relative;
}
.loginbox a
{
    text-decoration: none;
    font-size: 15px;
    line-height: 20px;
    color: darkblue;
    padding-right: 300px;
}
.loginbox a:hover
{
    color: #db4227
}
</style>