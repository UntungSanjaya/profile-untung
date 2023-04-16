<template>

       <section id = "sec-2" class = "py-5">
           <div class = "container my-4">
               <div class = "row gx-lg-5">
                   <div class = "col-lg-6 mb-5">
                        <img src = "../assets/unt.jpg" class = "img-fluid">
                   </div>
                   <div class = "col-lg-6">
                       <h3>About me</h3>
                       <p class = "text-muted fw-light lh-lg my-4">Saya adalah anak ke-1 dari 3 bersaudara</p>
                       <button type = "button" class = "btn btn-green mt-2">Read more</button>
                   </div>
               </div>
           </div>
       </section>

    <section id = "sec-5" class = "py-5">
        <div class = "container my-4">
            <div class = "row mb-5">
                <div class = "col text-center">
                    <h3 class = "mb-4">Video pada masa SMA</h3>
                    <p class = "lh-lg fw-light pt-2 w-75 mx-auto">berikut adalah video saya bersama rekan saya saat di sma</p>
                </div>
            </div>

            <div class = "row">
                <video controls>
                    <source src = "../assets/myvideos.mp4" type = "video/mp4">
                </video>
            </div>
        </div>
    </section>

    <section id = "sec-6" class = "py-5">
        <div class = "container my-4">
            <div class = "row mb-5">
                <div class = "col-12 text-center text-white">
                    <h3 class = "mb-4">MY Sosial Media</h3>
                    <p class = "lh-lg fw-light pt-2 w-75 mx-auto">Berikut ini adalah media sosial saya yang dapat teman teman akses</p>
                </div>
            </div>
            <div class = "row text-uppercase text-center text-white">
                <div class = "col-md-6 col-lg-3 mb-5">
                    <div class = "circle-icon bg-white text-green d-flex align-items-center justify-content-center mx-auto mb-4 fs-2 fw-bold">
						<a href="https://instagram.com/untungsanjaya_02?igshid=OTJhZDVkZWE=" target="_blank">
							<i class="bi bi-instagram"></i>
						</a>
                    </div>
                    <h6>Instagram</h6>
                </div>

                <div class = "col-md-6 col-lg-3 mb-5">
                    <div class = "circle-icon bg-white text-green d-flex align-items-center justify-content-center mx-auto mb-4 fs-2 fw-bold">
						<a href="https://www.facebook.com/profile.php?id=100086714320549&mibextid=ZbWKwL" target="_blank">
							<i class="bi bi-facebook"></i>
						</a>
                    </div>
                    <h6>Facebook</h6>
                </div>

                <div class = "col-md-6 col-lg-3 mb-5">
                    <div class = "circle-icon bg-white text-green d-flex align-items-center justify-content-center mx-auto mb-4 fs-2 fw-bold">
						<a href="https://twitter.com/UntungS03194136?t=MFganxVwTZNRuUdTJkZkeg&s=09" target="_blank">
							<i class="bi bi-twitter"></i>
						</a>
                    </div>
                    <h6>Twitter</h6>
                </div>

                <div class = "col-md-6 col-lg-3 mb-5">
                    <div class = "circle-icon bg-white text-green d-flex align-items-center justify-content-center mx-auto mb-4 fs-2 fw-bold">
						<a href="http://tiktok.com/@babayo_mah" target="_blank">
							<i class="bi bi-tiktok"></i>
						</a>
                    </div>
                    <h6>Tiktok</h6>
                </div>
            </div>
        </div>
    </section>

    <section id = "sec-7" class = "py-5">
        <div class = "container my-4">
            <div class = "row gx-md-5">
                <div class = "col-md-6 my-3">
                    <div class = "card text-center">
                        <img class = "card-img-top" src = "../assets/blog-1-img.jpg">
                        <div class = "card-body py-5">
                            <h4 class = "card-title">Apa yang harus dikuasai oleh editor</h4>
                            <p class = "card-text py-3 lh-lg text-muted fw-light">Editor harus dapat menguasai aplikasi software editing video. dapat bekerja dengan cepat dan tepat.
                            jika bersama tim harus dapat berkomunikasi dengan baik</p>
                            <a href = "#" class = "btn btn-green">Learn more</a>
                        </div>
                    </div>
                </div>

                <div class = "col-md-6 my-3">
                    <div class = "card text-center">
                        <img class = "card-img-top" src = "../assets/blog-2-img.jpg">
                        <div class = "card-body py-5">
                            <h4 class = "card-title">Menemukan ide yang terbaik</h4>
                            <p class = "card-text py-3 lh-lg text-muted fw-light">Biasanya para editor sangat kesulitan dalam mencari ide dari video yang akan dibuat,
                                namun seorang editor harus dapat bekerja pada ruang sendiri agar bisa mencurahkan idenya dari video yang akan dibuat</p>
                            <a href = "#" class = "btn btn-green">Learn more</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class = "bg-green">
        <div class = "container">
            <div class = "row pt-4 text-white">
                <div class = "col-md-6 text-center text-md-start">
                    <p><span class = "fw-bold">DUFAN &copy;</span> Copyright 2022</p>
                </div>
                <div class = "col-md-6 d-flex justify-content-center justify-content-md-end">
                    <ul class = "d-flex p-0">
                        <li><i class = "fab fa-facebook-f px-2"></i></li>
                        <li><i class = "fab fa-twitter px-2"></i></li>
                        <li><i class = "fab fa-instagram px-2"></i></li>
                    </ul>
                </div>
            </div>
        </div>
	</footer>
</template>

<script>
export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
:root{
    --green: #16db93;
    --green-dark: #13bc7e;
    --light-grey: #f1f4f6;
}

*{
    font-family: 'Roboto', sans-serif;
}

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
.btn{
    border: 2px solid #fff;
    border-radius: 1.5rem;
    padding: 0.6rem 0;
    width: 160px;
}
.btn-green{
    background-color: var(--green);
    color: #fff;
    padding: 0.55rem 0;
    width: 140px;
}
.btn-green:hover{
    color: var(--green);
    background: #fff;
    border-color: var(--green);
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



/* section 6 */
#sec-6{
    background: linear-gradient(rgba(22, 219, 147, 0.9), rgba(22, 219, 147, 0.9)), center/cover no-repeat;
}
#sec-6 .circle-icon{
    width: 95px;
    height: 95px;
}

/* section 7 */
#sec-7 .card{
    border: none;
}

/* section 8 */
#sec-8 .carousel-item img{
    width: 180px!important;
}

/* section 9 */
.pricing-item{
    border-radius: 0.3rem;
    overflow: hidden;
    max-width: 340px;
}
.pricing-title{
    background-color: var(--green-dark);
}
.pricing-price, .pricing-item ul li{
    border-bottom: 1px solid rgba(255, 255, 255, 0.5);
    padding: 0.9rem 0;
}
.pricing-item .btn:hover{
    background: transparent!important;
    color: #24654b;
}
</style>