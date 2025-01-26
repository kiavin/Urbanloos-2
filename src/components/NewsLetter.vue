<script setup>
</script>
<template>
    <div class="newsletter">
        <h1>This is the newsletter section</h1>
    </div>

    <!-- thiis is for a blog component -->

    <div class="blog-home5 py-5">
        <div class="container">
            <!-- Row  -->
            <div class="row justify-content-center">
                <!-- Column -->
                <div class="col-md-8 text-center">
                    <h3 class="mb-3">Latest from Our Blog</h3>
                    <h6 class="subtitle font-weight-normal">You can relay on our amazing features list and also our
                        customer services will be great experience for you without doubt</h6>
                </div>
                <!-- Column -->
            </div>
            <!-- Row  -->
            <div class="row mt-4">
                <!-- Column -->
                <div class="col-md-4">
                    <div class="card b-h-box position-relative font-14 border-0 mb-4">
                        <img class="card-img"
                            src="https://www.wrappixel.com/demos/ui-kit/wrapkit/assets/images/blog/blog-home/img9.jpg"
                            alt="Card image">
                        <div class="card-img-overlay overflow-hidden">
                            <div class="d-flex align-items-center">
                                <span
                                    class="bg-danger-gradiant badge overflow-hidden text-white px-3 py-1 font-weight-normal">Charity,
                                    Ngo</span>
                                <div class="ml-2">
                                    <span class="ml-2">Feb 18, 2018</span>
                                </div>
                            </div>
                            <h5 class="card-title my-3 font-weight-normal">Help out the people who really need it on
                                time.</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                                eiusmod...</p>
                        </div>
                    </div>
                </div>
                <!-- Column -->
                <!-- Column -->
                <div class="col-md-4">
                    <div class="card b-h-box position-relative font-14 border-0 mb-4">
                        <img class="card-img"
                            src="https://www.wrappixel.com/demos/ui-kit/wrapkit/assets/images/blog/blog-home/img10.jpg"
                            alt="Card image">
                        <div class="card-img-overlay overflow-hidden">
                            <div class="d-flex align-items-center">
                                <span
                                    class="bg-danger-gradiant badge overflow-hidden text-white px-3 py-1 font-weight-normal">Charity,
                                    Ngo</span>
                                <div class="ml-2">
                                    <span class="ml-2">Feb 18, 2018</span>
                                </div>
                            </div>
                            <h5 class="card-title my-3 font-weight-normal">Help out the people who really need it on
                                time.</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                                eiusmod...</p>
                        </div>
                    </div>
                </div>
                <!-- Column -->
                <!-- Column -->
                <div class="col-md-4">
                    <div class="card b-h-box position-relative font-14 border-0 mb-4">
                        <img class="card-img"
                            src="https://www.wrappixel.com/demos/ui-kit/wrapkit/assets/images/blog/blog-home/img11.jpg"
                            alt="Card image">
                        <div class="card-img-overlay overflow-hidden">
                            <div class="d-flex align-items-center">
                                <span
                                    class="bg-danger-gradiant badge overflow-hidden text-white px-3 py-1 font-weight-normal">Charity,
                                    Ngo</span>
                                <div class="ml-2">
                                    <span class="ml-2">Feb 18, 2018</span>
                                </div>
                            </div>
                            <h5 class="card-title my-3 font-weight-normal">Help out the people who really need it on
                                time.</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                                eiusmod...</p>
                        </div>
                    </div>
                </div>
                <!-- Column -->
            </div>
        </div>
    </div>
</template>
<style scoped>
@import url(//fonts.googleapis.com/css?family=Montserrat:300,400,500);

.blog-home5 {
    font-family: "Montserrat", sans-serif;
    color: #8d97ad;
    font-weight: 300;
}

.blog-home5 h1,
.blog-home5 h2,
.blog-home5 h3,
.blog-home5 h4,
.blog-home5 h5,
.blog-home5 h6 {
    color: #3e4555;
}

.blog-home5 .card-title {
    font-size: 18px;
}

.blog-home5 .subtitle {
    color: #8d97ad;
    line-height: 24px;
}

.blog-home5 .card.card-shadow {
    -webkit-box-shadow: 0px 0px 30px rgba(115, 128, 157, 0.1);
    box-shadow: 0px 0px 30px rgba(115, 128, 157, 0.1);
}

.blog-home5 .b-h-box .card-img-overlay {
    bottom: 0px;
    top: auto;
    -webkit-transition: 0.2s ease-in;
    -o-transition: 0.2s ease-in;
    transition: 0.2s ease-in;
    height: 55%;
}

.blog-home5 .b-h-box .card-title {
    color: #ffffff;
}

.blog-home5 .b-h-box {
    color: #ffffff;
}

.blog-home5 .b-h-box .card-text {
    display: none;
}

.blog-home5 .b-h-box:hover {
    color: #8d97ad;
}

.blog-home5 .b-h-box:hover .card-img-overlay {
    height: 100%;
    background: #ffffff;
    border: 3px solid rgba(120, 130, 140, 0.13);
}

.blog-home5 .b-h-box:hover .card-title {
    color: #263238;
    margin: 15px 0;
}

.blog-home5 .b-h-box:hover .card-text {
    display: block;
}

.blog-home5 .bg-danger-gradiant {
    background: #ff4d7e;
    background: -webkit-linear-gradient(legacy-direction(to right), #ff4d7e 0%, #ff6a5b 100%);
    background: -webkit-gradient(linear, left top, right top, from(#ff4d7e), to(#ff6a5b));
    background: -webkit-linear-gradient(left, #ff4d7e 0%, #ff6a5b 100%);
    background: -o-linear-gradient(left, #ff4d7e 0%, #ff6a5b 100%);
    background: linear-gradient(to right, #ff4d7e 0%, #ff6a5b 100%);
}

.blog-home5 .font-14 {
    font-size: 14px;
}

@media (max-width:768px) {
    .blog-home5 .b-h-box .card-img-overlay {
        height: 40%;
    }
}
</style>