<script setup>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'

</script>

<template>
    <Navbar />

    <div class="blog-home2 py-5">
        <div class="container">
            <!-- Row  -->
            <div class="row justify-content-center">
                <!-- Column -->
                <div class="col-md-8 text-center">
                    <h3 class="my-3">Upcoming Events</h3>
                    <h6 class="subtitle font-weight-normal">You can relay on our amazing features list and also our
                        customer services will be great experience for you without doubt</h6>
                </div>
                <!-- Column -->
                <!-- Column -->
            </div>
            <div class="row mt-4">
                <!-- Column -->
                <div class="col-md-4 on-hover">
                    <div class="card border-0 mb-4">
                        <a href="#"><img class="card-img-top"
                                src="https://www.wrappixel.com/demos/ui-kit/wrapkit/assets/images/blog/blog-home/img3.jpg"
                                alt="wrappixel kit"></a>
                        <div
                            class="date-pos bg-info-gradiant p-2 d-inline-block text-center rounded text-white position-absolute">
                            Oct<span class="d-block">23</span></div>
                        <h5 class="font-weight-medium mt-3"><a href="#" class="text-decoration-none link">You should
                                have eagle’s eye on new trends and techonogies</a></h5>
                        <p class="mt-3">Business Park, Opp. Corns Sam Restaurant, New Yoark, US</p>
                        <a href="#" class="text-decoration-none linking text-themecolor mt-2">Learn More</a>
                    </div>
                </div>
                <!-- Column -->
                <div class="col-md-4 on-hover">
                    <div class="card border-0 mb-4">
                        <a href="#"><img class="card-img-top"
                                src="https://www.wrappixel.com/demos/ui-kit/wrapkit/assets/images/blog/blog-home/img2.jpg"
                                alt="wrappixel kit"></a>
                        <div
                            class="date-pos bg-info-gradiant p-2 d-inline-block text-center rounded text-white position-absolute">
                            Oct<span class="d-block">23</span></div>
                        <h5 class="font-weight-medium mt-3"><a href="#" class="text-decoration-none link">New Seminar on
                                Newest Food Recipe from World’s Best</a></h5>
                        <p class="mt-3">Business Park, Opp. Corns Sam Restaurant, New Yoark, US</p>
                        <a href="#" class="text-decoration-none linking text-themecolor mt-2">Learn More</a>
                    </div>
                </div>
                <!-- Column -->
                <div class="col-md-4 on-hover">
                    <div class="card border-0 mb-4">
                        <a href="#"><img class="card-img-top"
                                src="https://www.wrappixel.com/demos/ui-kit/wrapkit/assets/images/blog/blog-home/img1.jpg"
                                alt="wrappixel kit"></a>
                        <div
                            class="date-pos bg-info-gradiant p-2 d-inline-block text-center rounded text-white position-absolute">
                            Oct<span class="d-block">23</span></div>
                        <h5 class="font-weight-medium mt-3"><a href="#" class="text-decoration-none link">Learn from
                                small things to create something bigger.</a></h5>
                        <p class="mt-3">Business Park, Opp. Corns Sam Restaurant, New Yoark, US</p>
                        <a href="#" class="text-decoration-none linking text-themecolor mt-2">Learn More</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <Footer />
</template>
<style scoped>
@import url(//fonts.googleapis.com/css?family=Montserrat:300,400,500);

.blog-home2 {
    font-family: "Montserrat", sans-serif;
    color: #8d97ad;
    font-weight: 300;
}

.blog-home2 h1,
.blog-home2 h2,
.blog-home2 h3,
.blog-home2 h4,
.blog-home2 h5,
.blog-home2 h6 {
    color: #3e4555;
}

.blog-home2 .font-weight-medium {
    font-weight: 500;
}

.blog-home2 .bg-light {
    background-color: #f4f8fa !important;
}

.blog-home2 .subtitle {
    color: #8d97ad;
    line-height: 24px;
}

.blog-home2 .text-themecolor {
    color: #316ce8;
}

.blog-home2 h5 {
    line-height: 22px;
    font-size: 18px;
}

.blog-home2 a.link {
    color: #3e4555;
}

.blog-home2 a.link:hover {
    color: #316ce8;
}

.blog-home2 .on-hover {
    -webkit-transition: 0.2s ease-in;
    -o-transition: 0.2s ease-in;
    transition: 0.2s ease-in;
}

.blog-home2 .on-hover:hover {
    -webkit-transform: translateY(-10px);
    -ms-transform: translateY(-10px);
    transform: translateY(-10px);
}

.blog-home2 .date-pos {
    right: 10px;
    top: 10px;
}

.blog-home2 .date-pos span {
    font-size: 30px;
    line-height: 30px;
}

.blog-home2 .bg-info-gradiant {
    background: #188ef4;
    background: -webkit-linear-gradient(legacy-direction(to right), #188ef4 0%, #316ce8 100%);
    background: -webkit-gradient(linear, left top, right top, from(#188ef4), to(#316ce8));
    background: -webkit-linear-gradient(left, #188ef4 0%, #316ce8 100%);
    background: -o-linear-gradient(left, #188ef4 0%, #316ce8 100%);
    background: linear-gradient(to right, #188ef4 0%, #316ce8 100%);
}
</style>
