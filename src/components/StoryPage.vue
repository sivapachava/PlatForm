<template>
  <div class="screen">
        <nav>
            <div class="title"> Museum'IT</div>
          <div class="header-left">
            <a href="" class="button-left">Home</a>
            <a href="./StoryPage.vue" class="button-left active">Stories</a>
            <a href="" class="button-left">Collections</a>  
            <a href="" class="button-left">SignUp</a>
            <a href="" class="button-left">Login</a>
            <i class="fa fa-search search-icon"></i>
          </div>
          </nav>
    </div>



        <div class="collectionform">
        <div class="title1"> 
            <h1>Collections</h1>
            <h2>Explore our collection by theme, topic, century, and organisation. is a public library specializing in the field of Natural Sciences, and rich in an important heritage fund . Its activity is part of the general action of the Museum. This resource center of the institution in terms of documentation is intended both for the teams of the Museum and for the general public. It contributes to the dissemination of knowledge and provides its readers with updated scientific documentation enriched by regular acquisitions.</h2>
        </div>
        <div class="title2"> 
            <h1>Collections</h1>
            <h2>Explore our collection by theme, topic, century, and organisation. is a public library specializing in the field of Natural Sciences, and rich in an important heritage fund . Its activity is part of the general action of the Museum. This resource center of the institution in terms of documentation is intended both for the teams of the Museum and for the general public. It contributes to the dissemination of knowledge and provides its readers with updated scientific documentation enriched by regular acquisitions.</h2>
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



.collectionform{
  margin-top: 80px;
  margin-left: 90px;
  background-color: rgb(199, 192, 139);
  height: 160vh;
}
.title1 h1{
  display: flex;
  align-items: center;
  padding-top: 5px;
  margin-bottom: 10px;
  margin-left: 50px;
  font-size:35px;
  font-weight: bold;
  font-family: "Open Sans", sans-serif;
  text-decoration: underline;
}
.title1 h2{
  display: flex;
  align-items:flex-end;
  padding-top: 5px;
  margin-bottom: 10px;
  margin-left: 50px;
  font-size: 15px;
  font-weight: bold;
  font-family: "Open Sans", sans-serif; 
  text-decoration:none;
}
.title2 h1{
  display: flex;
  align-items: center;
  padding-top: 5px;
  margin-bottom: 10px;
  margin-left: 50px;
  font-size:35px;
  font-weight: bold;
  font-family: "Open Sans", sans-serif;
  text-decoration: underline;
}
.title2 h2{
  display: flex;
  align-items:flex-end;
  padding-top: 5px;
  margin-left: 50px;
  font-size: 15px;
  font-weight: bold;
  font-family: "Open Sans", sans-serif; 
  text-decoration:none;
}

</style>