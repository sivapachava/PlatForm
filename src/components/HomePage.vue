<template>
    <div class="screen">
        <nav>
            <div class="title"> Museum'IT</div>
          <div class="header-left">
            <a href="" class="button-left active">Home</a>
            <a href="" class="button-left">Stories</a>
            <a href="" class="button-left">Collections</a>  
            <a href="" class="button-left">SignUp</a>
            <a href="" class="button-left">Login</a>
            <i class="fa fa-search search-icon"></i>
          </div>
          </nav>
        </div>


  <div class="container">
    <div class="collectionform">
        <div class="title1"> 
    <h1>Museums of Information Technologies</h1>
    <h2>It aims to safeguard the contemporary scientific and technical heritage of Information Technology (IT) through the collections of computer museums</h2>
  </div>
    <form>
        <input type="text" placeholder="What you are looking for?">
        <button type="submit">search</button>
    </form>
</div>
          </div>
        <div class="title2"> 
    <h1>Explore</h1>
    <h2>Join with us to explore your Museum data and to represents an important part of the regional and national scientific and cultural heritage data</h2>
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
.collectionform{
  padding: 170px;
  margin-left: 10px;
  color: rgb(245, 247, 248);
}
.h1{
    font-size: large;
    font-weight: bold;
    font-style: inherit;
}
.h2{
    font-size:medium;
    font-weight: bold;
    font-style: inherit;
}
.collectionform form {
    background: #fff;
    width:600px;
    height:40px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-left: 100px;
    margin-top: 70px;
}
.collectionform form input{
    flex:1;
    border:none;
    outline: none;
    font-size: medium;
}
.collectionform form button{
    background: rgb(11, 11, 11);
    padding: 10px 50px;
    border:none;
    outline: none;
    color: #fff;
    letter-spacing: 1px;
    cursor: pointer;
    height: 40px;
    font-size: medium;
    font-weight: bold;
}
.title2 h1{
    text-decoration:underline;
    margin-top: 50px;
}
.title2 h2{
    text-decoration: none;
    text-decoration-line: none;
    margin-top: 20px;

}
</style>