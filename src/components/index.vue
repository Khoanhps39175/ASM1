<template>
    <div>
        <div class="container-fluid bg-dark">
            <div class="container">
                <nav class="row p-2 bg-dark navbar navbar-expand-sm navbar-dark text-white">
                    <div class="container">
                        <a href="#" class="navbar-brand">
                            <img src="../assets/img/logo.png" alt="Logo" style="width: 75px;">
                        </a>
                        <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                            data-bs-target="#collapsibleNavBar">
                            <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="collapsibleNavBar">
                            <ul class="navbar-nav me-auto">
                                <li class="nav-item">
                                    <a class="nav-link" href="../components/index.vue">
                                        <i class="fa-solid fa-house"></i> Trang chủ
                                    </a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="../components/post.vue">
                                        <i class="fa-solid fa-upload"></i> Đăng bài viết
                                    </a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="../components/profile.vue">
                                        <i class="fa-solid fa-address-card"></i> Thông tin cá nhân
                                    </a>
                                </li>
                            </ul>
                            <ul class="navbar-nav d-flex">
                                <li class="nav-item dropdown">
                                    <a class="nav-link dropdown-toggle " href="#" role="button" data-bs-toggle="dropdown">
                                        <i class="fa-solid fa-user"></i> Tài khoản
                                    </a>
                                    <ul class="dropdown-menu">
                                        <li><a class="dropdown-item" href="/ASM1/html/login.html">Đăng nhập</a></li>
                                        <li><a class="dropdown-item" href="/ASM1/html/register.html">Đăng ký</a></li>
                                    </ul>
                                </li>
                            </ul>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
        <div class="container">
            <div id="carousel" class="carousel slide">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carousel" data-bs-slide-to="0" class="active" aria-current="true"
                        aria-label="slide1">
                    </button>
                    <button type="button" data-bs-target="#carousel" data-bs-slide-to="1" aria-current="true"
                        aria-label="slide2">
                    </button>
                    <button type="button" data-bs-target="#carousel" data-bs-slide-to="2" aria-current="true"
                        aria-label="slide3">
                    </button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="../assets/img/Banner1.png" class="d-block w-100" alt="">
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/img/Banner2.png" class="d-block w-100" alt="">
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/img/Banner3.png" class="d-block w-100" alt="">
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carousel" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Prev</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carousel" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
            <section class="row">
                <aside class="col-sm-4 pt-5">
                    <div class="mt-3">
                        <ul class="nav nav-tabs" role="tablist">
                            <li class="nav-item">
                                <a class="nav-link active" data-bs-toggle="tab" href="#topDoc">
                                    <h5 class="text-dark ">Đọc nhiều</h5>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" data-bs-toggle="tab" href="#topXem">
                                    <h5 class="text-dark ">Xem nhiều</h5>
                                </a>
                            </li>
                            <li class="nav item">
                            </li>
                        </ul>
                        <div class="tab-content">
                            <div id="topDoc" class="container tab-pane active"><br>
                                <div class="card border-light">
                                    <!-- Card 1 -->
                                    <div class="row g-0">
                                        <div class="col-4">
                                            <img src="../assets/img/corevalue.jpg" class="img-fluid pt-3 pr-3"
                                                alt="Card 1 image">
                                        </div>
                                        <div class="col-8">
                                            <div class="card-body">
                                                <h6 class="card-title">Biết ơn đời, đời sẽ thương ta</h6>
                                                <p class="card-text"><small class="text-muted">30 bình luận</small></p>
                                            </div>
                                        </div>
                                    </div>
                                    <!-- Card 2 -->
                                    <div class="row g-0">
                                        <div class="col-4">
                                            <img src="../assets/img/sesameoil_300x300.jpg" class="img-fluid pt-2 pr-3"
                                                alt="Card 3 image">
                                        </div>
                                        <div class="col-8">
                                            <div class="card-body">
                                                <h6 class="card-title">10 công dụng bất ngờ từ dầu dừa</h6>
                                                <p class="card-text"><small class="text-muted">15 bình luận</small></p>
                                            </div>
                                        </div>
                                    </div>
                                    <!-- Card 3 -->
                                    <div class="row g-0">
                                        <div class="col-4">
                                            <img src="../assets/img/spinach_300x300.jpg" class="img-fluid pt-2 pb-3 pr-3"
                                                alt="Card 4 image">
                                        </div>
                                        <div class="col-8">
                                            <div class="card-body">
                                                <h6 class="card-title">Lợi ích khi ăn rau mỗi ngày</h6>
                                                <p class="card-text"><small class="text-muted">12 bình luận</small></p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div id="topXem" class="container tab-pane fade"><br>
                                <div class="card border-light">
                                    <!-- Card 1 -->
                                    <div class="row g-0">
                                        <div class="col-4">
                                            <img src="../assets/img/corevalue.jpg" class="img-fluid px-3 pr-3"
                                                alt="Card 1 image">
                                        </div>
                                        <div class="col-8">
                                            <div class="card-body">
                                                <h6 class="card-title">Biết ơn đời, đời sẽ thương ta</h6>
                                                <p class="card-text"><small class="text-muted">30 bình luận</small></p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </aside>
                <article class="col-sm-8 pt-5 my-3">
                    <h3 class="text-dark text-center mb-3">BÀI VIẾT ĐỪNG BỎ LỠ</h3>
                    <div class="row row-cols-1 row-cols-md-2 g-4">
                        <div class="col">
                            <div class="card">
                                <img src="../assets/img/video1.jpg" class="card-img-top p-3" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Đi xa hơn để trưởng thành hơn</h5>
                                    <p class="card-text">Tuổi trẻ chỉ nghĩ đến những chuyến đi, đợi mong một ngày được bay
                                        nhảy trên những phương trời mới lạ.
                                        Để rồi những cô đơn mãi mê, tuổi trẻ ấy mới muốn một nơi để trở về.
                                    </p>
                                    <a href="/ASM1/html/postDetail.html" class="btn btn-outline-dark">Xem chi tiết</a>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="card">
                                <img src="../assets/img/video2.jpg" class="card-img-top p-3" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Chút tâm tư những ngày cuối năm</h5>
                                    <p class="card-text">Guồng quay cuộc sống dẫu có vội vàng, dẫu có tấp nập đến đâu thì
                                        cũng chẳng nằm ngoài quy luật tự nhiên và bất biến xuân, hạ, thu, đông.
                                        Và rồi một năm cũ sắp trôi qua.
                                    </p>
                                    <a href="#" class="btn btn-outline-dark">Xem chi tiết</a>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="card">
                                <img src="../assets/img/video3.jpg" class="card-img-top p-3" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Ước gì được trở về tuổi thơ</h5>
                                    <p class="card-text">Tuổi trẻ chỉ nghĩ đến những chuyến đi, đợi mong một ngày được bay
                                        nhảy trên những phương trời mới lạ.
                                        Để rồi những cô đơn mãi mê, tuổi trẻ ấy mới muốn một nơi để trở về.
                                    </p>
                                    <a href="#" class="btn btn-outline-dark">Xem chi tiết</a>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="card">
                                <img src="../assets/img/video4.jpg" class="card-img-top p-3" alt="...">
                                <div class="card-body">
                                    <h5 class="card-title">Ba người thầy vĩ đại</h5>
                                    <p class="card-text">
                                        Ta xem vạn vật là thầy.
                                        Tinh thần học hỏi của ta luôn rộng mở hơn tất cả các người.
                                        Ta học hỏi từ tất cả mọi vật, từ cành cây ngọn cỏ đến đám mây trên trời kia.
                                    </p>
                                    <a href="#" class="btn btn-outline-dark">Xem chi tiết</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="text-center mt-3">
                        <button class="btn btn-dark">Xem thêm</button>
                    </div>
                </article>
            </section>
        </div>
        <footer class="row bg-dark p-3">
            <p class="text-center text-white">@authour: PS39175: NguyenHuuKhoa</p>
        </footer>
    </div>
</template>