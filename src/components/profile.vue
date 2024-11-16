<template>
    <div class="d-flex flex-column min-vh-100">
        <div class="container-fluid bg-dark">
            <nav class="navbar navbar-expand-sm navbar-dark p-2">
                <div class="container">
                    <a href="#" class="navbar-brand">
                    <img src="../assets/img/logo.png" alt="Logo" style="width: 75px;">
                    </a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavBar">
                    <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="collapsibleNavBar">
                        <ul class="navbar-nav me-auto">
                            <li class="nav-item">
                            <a class="nav-link" href="/ASM1/html/index.html">
                                <i class="fa-solid fa-house"></i> Trang chủ
                            </a>
                            </li>
                            <li class="nav-item">
                            <a class="nav-link" href="/ASM1/html/post.html">
                                <i class="fa-solid fa-upload"></i> Đăng bài viết
                            </a>
                            </li>
                            <li class="nav-item">
                            <a class="nav-link" href="/ASM1/html/profile.html">
                                <i class="fa-solid fa-address-card"></i> Thông tin cá nhân
                            </a>
                            </li>
                        </ul>
                        <ul class="navbar-nav ms-auto">
                            <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">
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

        <!-- Main Content -->
        <div class="container flex-grow-1 mt-5">
            <div class="row justify-content-center">
            <div class="col-md-6">
                <div class="card">
                <div class="card-body">
                    <h2 class="text-center">Thông Tin Cá Nhân</h2>
                    <form>
                    <!-- Full Name -->
                    <div class="mb-3">
                        <label for="fullname" class="form-label">Họ và Tên</label>
                        <input type="text" class="form-control" id="fullname" value="" placeholder="Nhập họ và tên" required>
                    </div>

                    <!-- Email -->
                    <div class="mb-3">
                        <label for="email" class="form-label">Email</label>
                        <input type="email" class="form-control" id="email" value="" placeholder="Nhập email" required>
                    </div>

                    <!-- Phone Number -->
                    <div class="mb-3">
                        <label for="phone" class="form-label">Số Điện Thoại</label>
                        <input type="text" class="form-control" id="phone" value="" placeholder="Nhập số điện thoại">
                    </div>

                    <!-- New Password -->
                    <div class="mb-3">
                        <label for="password" class="form-label">Mật Khẩu Mới</label>
                        <input type="password" class="form-control" id="" placeholder="Nhập mật khẩu mới">
                    </div>

                    <!-- Avatar -->
                    <div class="mb-3">
                        <label for="avatar" class="form-label">Ảnh Đại Diện</label>
                        <input type="file" class="form-control" id="avatar">
                    </div>

                    <button type="submit" class="btn btn-dark w-100">Lưu Thay Đổi</button>
                    </form>
                </div>
                </div>
            </div>
            </div>
        </div>

        <!-- Footer -->
        <footer class="bg-dark text-center text-white p-3 mt-auto">
            <p>@authour: PS39175: NguyenHuuKhoa</p>
        </footer>
    </div>
</template>