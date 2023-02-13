<template>
 
 <HomePage />
 <CollectPage />
 <LoginPage />
 <SignupPage />
 <StoryPage />
</template>

<script>
import HomePage from './components/HomePage.vue'
//import CollectPage from './components/CollectPage.vue'
//import LoginPage from './components/LoginPage.vue'
//import SignupPage from './components/SignupPage.vue'
//import StoryPage from './components/StoryPage.vue'

export default {
  name: 'App',
  components: {
    HomePage,
    //CollectPage,
    //LoginPage,
    //SignupPage,
    //StoryPage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
