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
            <div class="col-md-8">
                <div class="card">
                <div class="card-body">
                    <h2 class="text-center">Đăng Bài Viết</h2>
                    <form>
                    <div class="mb-3">
                        <label for="title" class="form-label">Tiêu Đề</label>
                        <input type="text" class="form-control" id="title" placeholder="Nhập tiêu đề bài viết" required>
                    </div>
                    <div class="mb-3">
                        <label for="content" class="form-label">Nội Dung</label>
                        <textarea class="form-control" id="content" rows="5" placeholder="Nhập nội dung bài viết" required></textarea>
                    </div>
                    <div class="mb-3">
                        <label for="image" class="form-label">Chọn Ảnh</label>
                        <input type="file" class="form-control" id="image">
                    </div>
                    <button type="submit" class="btn btn-dark w-100">Đăng Bài</button>
                    </form>
                </div>
                </div>
            </div>
            </div>
        </div>

        <!-- Footer -->
        <footer class="bg-dark text-center text-white p-3 mt-auto">
            <p>@author: PS39175: NguyenHuuKhoa</p>
        </footer>
    </div>
</template>