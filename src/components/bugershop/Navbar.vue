<script setup>
</script>

<template>
    <!-- 主導覽 start -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="index.html">LOGO</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">

                    <li class="nav-item">
                        <a class="nav-link" href="about.html">關於我們</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            產品列表
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="product-list.html">產品分類1</a></li>
                            <li><a class="dropdown-item" href="product-list.html">產品分類2</a></li>
                            <li><a class="dropdown-item" href="product-list.html">產品分類3</a></li>
                            <li><a class="dropdown-item" href="product-list.html">產品分類4</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="store.html">門市店舖</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="faq.html">常見問題</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">聯絡我們</a>
                    </li>


                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-primary" type="submit"><i class="bi bi-search"></i></button>
                </form>
                <a href="javascript:;" data-bs-toggle="modal" data-bs-target="#userModal">
                    <i class="bi bi-person-circle fs-3 ms-2"></i>
                </a>
                <a href="javascript:;" data-bs-toggle="modal" data-bs-target="#cartModal">
                    <i class="bi bi-cart fs-3 ms-2"></i>
                </a>
            </div>
        </div>
    </nav>
    <!-- 主導覽 end -->
    <!-- modal start -->

    <!-- Modal -->
    <div class="modal fade" id="userModal" tabindex="-1" aria-labelledby="userModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="userModalLabel">登入/註冊會員</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <p>立即登入，隨時收到獨家優惠</p>
                    <form>
                        <div class="form-floating mb-3">
                            <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                            <label for="floatingInput">電子郵件</label>
                        </div>
                        <div class="form-floating">
                            <input type="password" class="form-control" id="floatingPassword" placeholder="Password">
                            <label for="floatingPassword">密碼</label>
                        </div>
                        <a href="javascript:;" class="float-end">忘記密碼</a>
                        <button type="submit" class="btn btn-primary form-control">登入</button>
                        <a href="javascript:;">還未加入我們嗎？立即行動！</a>
                    </form>
                </div>
            </div>
        </div>
    </div>
    <div class="modal fade" id="cartModal" tabindex="-1" aria-labelledby="cartModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-body">
                    您的購物車是空的
                </div>
                <div class="modal-footer">
                    <p>共 0 件商品</p>
                    <button type="button" class="btn btn-primary">查看購物車</button>
                </div>
            </div>
        </div>
    </div>
    <!-- modal end -->
</template>

<style scoped></style>