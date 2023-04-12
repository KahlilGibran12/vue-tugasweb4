<template>
  <!--banner image-->

  <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
    <div  class="images">
      <div class="profile">
      <img src="https://cdn.discordapp.com/attachments/1081566575741632522/1095390732845596712/p.png" class="rounded-circle"
           height="300px" width="300px">
    </div>
    <div class="content text-center">
      <h1 class="text-black">Muhamamd Khalil Gibran</h1>
      <h2 class="text-black">Selamat Datang</h2>
    </div>
    </div>
  </div>


</template>

<script>
export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
.text-center{
  margin-top: 40px;
}
.images {
  margin-top: -250px;
}
.banner-image{
  background: #5d5d5d;
  background-size: cover;
}


</style>
