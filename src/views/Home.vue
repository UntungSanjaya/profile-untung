<template>
    <!--banner image-->
    
    <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
        <div class="content text-center">
            <h1 class="text-white">Haloooo teman teman semua</h1>
        </div>
    </div>

    <!--kontent-->
    <section id = "sec-4" class = "py-5">
        <div class = "container my-4">
            <div class = "row gx-lg-5">
                <div class = "col-lg-6 mb-5">
                     <h3>Sedikit Tentang Saya</h3>
                    <p class = "text-muted fw-light lh-lg my-4">Saya sangat menyukai bidang editing video dan saya juga suka mendengarkan lagu</p>
                    <p class = "text-muted fw-light lh-lg my-4">di dunia perkuliahan saya di kenal sebagai orang yang humoris</p>
                    <button type = "button" class = "btn btn-green mt-2"><router-link to="/about">More About Me</router-link></button>
                </div>
                <div class = "col-lg-6">
                    <img src = "../assets/awal.jpg" class = "img-fluid">
                </div>
            </div>
        </div>
    </section>
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
.banner-image {
    background-color: #24654b;
}
</style>