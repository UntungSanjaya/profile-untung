<template>
<header class = "pb-1 overflow-hidden " >
            <div class = "container">
                <div class = "row py-5">
                    <div class = "col-sm-6 text-lg-start">
                        <a href = "#" class = "navbar-brand text-white fs-1">
                            <img src="./assets/Mylogo.png" alt="">
                        </a>
                    </div>
                    <div class = "col-sm-6 d-none d-md-flex text-white align-items-center nav-icons justify-content-end">
                        <p class = "fw-bold mb-0"><router-link to="/" style="color: aliceblue;">Home</router-link></p>
                        <p class = "fw-bold mb-0"><router-link to="/about" style="color: aliceblue;">About</router-link></p>
                    
                    </div>
                </div>

                <div class = "row">
                    <div class = "col-lg-6 text-white text-center text-lg-start">
                        <h1 class = "display-1 fw-normal mt-6">Hy, i'm Untung Sanjaya</h1>
                        <p class = "my-4 lead fs-5">Ini Merupakan Website Profile Saya</p>
                    </div>
                    <div class = "col-lg-6 lusi-img d-none d-lg-flex justify-content-end">
                        <img src = "./assets/untung.png">
                    </div>
                </div>
            </div>
</header>

  <router-view />
</template>

<script>
export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
/* misc stylings */
ul li{
    list-style-type: none;
}
.container{
    max-width: 1200px;
}
.display-1{
    letter-spacing: 1px;
}
.bg-green{
    background-color: var(--green)!important;
}
.bg-grey{
    background-color: var(--light-grey);
}
.text-green{
    color: var(--green);
}

.lh-lg{
    line-height: 1.7!important;
}
.circle-icon{
    width:55px;
    height: 55px;
    border-radius: 50%;
    background-color: var(--green);
}

/* header */
header{
    height: 100vh;
    background-color: #2f2525;
}

.navbar-brand .fa{
    font-size: 1.3rem;
}

.navbar-brand img{
  width: 150px;
}

.nav-icons p{
    font-size: 1rem;
    margin-right: 0.6rem;
}
.nav-icons{
    font-size: 1.2rem;
}
.btn-header:hover{
    background-color: #fff;
    color: var(--green)!important;
}
.untung-img img{
    width: 400px;
}
</style>
