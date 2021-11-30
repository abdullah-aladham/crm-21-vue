<template>
<head>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/css/bootstrap.min.css" rel="stylesheet">

</head>
  <nav class="navbar  bg-primary  text-black">
    <div class="container-fluid">
     <div class="navbar-header ">
        <a class="navbar-brand text-white col-1">CRM</a>
      </div>
  
  <ul class="nav navbar-nav list-group-horizontal jusitfy-left ">
    <li class=" nav-item"><router-link to="/components/Customer"  class="text-white nav-link">Customers</router-link>
    </li>
    <li class=" nav-item"><router-link class="text-white p-2 nav-link" to="/components/services">Services</router-link></li>
    <li class=" nav-item"><router-link to="/components/login"  class="text-white p-2 nav-link">Login</router-link></li>
  </ul>
<app-customer></app-customer>  
  <form >
    <div class="form-inline">
  <input type='search' placeholder="Search for a customer....." class="input-group-l" >
    
   
  <button class=" btn btn-outline-primary p-1"><i>Search</i></button>
    </div>
</form>
</div><!--end of container fluid-->
  </nav>
<customer></customer>  
<div id="space"></div>
<services></services>
<login></login>
<footer>
  <span style="font-family:verdana"> made with love by Abdullah Azzam Aladham</span>
</footer>
</template>

<script>
import customer from './components/Customer.vue'
import login from './components/login.vue'
import services from './components/services.vue'

export default {
  name: 'App',
  components: {
 customer,
 login,
 services
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
#space{
  width: 100%;
  height:500px;
  background-color: rgb(8, 189, 90);
}
</style>
