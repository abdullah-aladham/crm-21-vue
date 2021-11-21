<template>
<head> <link href="//netdna.bootstrapcdn.com/twitter-bootstrap/2.3.2/css/bootstrap-combined.no-icons.min.css" rel="stylesheet">
<link href="//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css" rel="stylesheet">

</head>
  <nav class="navbar w-75 bg-primary m-auto text-black">
    <div class="container-fluid">
     <div class="navbar-header ">
        <router-link to="./app.vue" class="navbar-brand text-white col-1">CRM</router-link>
      </div>
  
  <ul class="nav navbar-nav list-group-horizontal jusitfy-left ">
    <li class=" nav-item"><router-link to="/components/Customer"  class="text-white nav-link">Customers</router-link>
    </li>
    <li class=" nav-item"><router-link class="text-white p-2 nav-link" to="/components/services">Services</router-link></li>
    <li class=" nav-item"><router-link to="/components/login"  class="text-white p-2 nav-link">Login</router-link></li>
  </ul>
<app-customer></app-customer>  
  <form>
    <div class="form-outline">
  <input type='search' placeholder="Search for a customer....." class="input-group-l" >
  
  <button class=" btn btn-transparent p-1"><i>Search</i></button>
    </div>
</form>
</div><!--end of container fluid-->
  </nav>
<customer></customer>  

<footer>
  <span style="font-family:verdana"> made with love by Abdullah Azzam Aladham</span>
</footer>
</template>

<script>
import customer from './components/Customer.vue'


export default {
  name: 'App',
  components: {
    'customer':customer,
   
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
