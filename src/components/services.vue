<template>
    <head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/css/bootstrap.min.css" rel="stylesheet">
   <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>





    <nav><h4 class="has-text-right">jj</h4></nav>
<div class="container">
  <nav class="navbar w-75  text-black">
    <div class="container-fluid">
     
  
  <ul class="nav navbar-nav list-group-horizontal jusitfy-left ">
    
  </ul>
</div><!--end of container fluid-->
  <div class="m-end">
  <form class="text-left">
    <div class="form-group ">
    <label class="m-right" for="Filter">Filter</label><br>
    <input type="text" >
    </div>
  </form>
</div>
</nav>

  <div class="row">
    <div class="col-2">
      <div class="card"  id="customers" >
        <div class="card-title bg-primary text-white p-1"><h5>this is service</h5></div>
        <DIV class="card-body">
          
          <div class="card-img" ><img src="#" id="customer-photo" style="height: 80px;width: 80px;">
         <div class="card-text"></div>
          </div>
          
        </DIV>
      </div>
    </div>
  </div>

 
</div>


</template>
<script>

export default{
name:'services',

data(){
    return {msg:'hello world'
    }
}
}
</script>
<style scoped>

</style>
