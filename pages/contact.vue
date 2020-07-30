<template>
<div id="body">
    <div ></div>
      <Navbar />
    <Contact />
    <Footer />
      
  
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@media (max-width: 858px) {
#body{
       background: linear-gradient(to right, rgb(165, 214, 243),rgb(194, 224, 238),rgb(217, 233, 236));
}
.nav{
    position: absolute;
width: 1440px;
height: 390px;
left: 0px;
top: 0px;
}
img {
    overflow: hidden;
    width: 100%;
}
}
</style>