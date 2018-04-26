<template>
  <div id="blog-header">
        <div id="nav-items">
            <ul>
               <li><a href="#"><img src="../assets/logo.png" alt="logo"></a></li>
               <li><a href="#">Home</a></li>
               <li><a href="#">Who we are</a></li>
               <li><a href="#">Blog</a></li> 
            </ul>
        </div>
      </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    #blog-header{
        background-color: rgb(97, 245, 163);
        height: 60px;
        width: 100%;
        position: fixed;
        padding: 6px;
    }
    #nav-items  ul{
        float: right;
        position: relative;
        margin-right: 50px;
        display: block;
    }
    
    #nav-items ul li{
        display: inline;
    }
    #nav-items  ul  li  a{
        padding: 0.5em 0.5em;
        color: #555555;
        text-decoration: none;
        font-size: 20px;
        position: relative;
        font-family: Arial, Helvetica, sans-serif;
    }
    #nav-items img{
        position: relative;
        height:40px;
        width: 40px;
        margin-right: 900px;
    }
    
</style>

