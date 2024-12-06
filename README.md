<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Amazon</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel='stylesheet' type='text/css' media='screen' href='assets/css/style.css'>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="icon" type="image/x-icon" href="assets/images/logo.png">
</head>

<body class="bg-dark" data-bs-theme="dark">
    <!-- top header start -->

    <div class="sticky-top">


        <nav class="navbar navbar-expand-lg bg-dark " data-bs-theme="dark">
            <div class="container">
                <a class="logo" href="index.html"> <img class="" src="assets/images/logo.png" alt="" width="30"
                        height="30"></a>
                <a class="navbar-brand" href="index.html">Amazon</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0 justify-content-end">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="index.html">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://www.amazon.com/" target="_blank">Link</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                                aria-expanded="false">
                                Dropdown
                            </a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="About.html">About</a></li>
                                <li><a class="dropdown-item" href="Contact.html">Contact</a></li>
                                <li>
                                    <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="Help.html">Help</a></li>
                            </ul>
                        </li>

                    </ul>
                    <form class="d-flex search justify-content-center" role="search">
                        <input class="form-control me-2 justify-content-center " type="search" placeholder="Search"
                            aria-label="Search">
                        <button class="btn btn-outline-success" type="submit">Search</button>
                    </form>
                </div>
            </div>
            <div class="icon">
                <i class="bi bi-github"></i>
                <i class="bi bi-twitter"></i>
            </div>


            <div class="modes">
                <div class="dropdown navbar position-fixed top-0 end-0 mb-3 me-3 bd-mode-toggle">
                    <button class="btn btn-bd-primary py-2 dropdown-toggle d-flex align-items-center" id="bd-theme"
                        type="button" aria-expanded="false" data-bs-toggle="dropdown" aria-label="Toggle theme (auto)">
                        <svg class="bi my-1 theme-icon-active" width="1em" height="1em">
                            <use href="#circle-half"></use>
                        </svg>
                        <span class="visually-hidden" id="bd-theme-text">Toggle theme</span>
                    </button>
                    <ul class="dropdown-menu dropdown-menu-end shadow" aria-labelledby="bd-theme-text">
                        <li>
                            <button type="button" class="dropdown-item d-flex align-items-center"
                                data-bs-theme-value="light" aria-pressed="false">
                                <svg class="bi me-2 opacity-50" width="1em" height="1em">
                                    <use href="#sun-fill"></use>
                                </svg>
                                Light
                                <svg class="bi ms-auto d-none" width="1em" height="1em">
                                    <use href="#check2"></use>
                                </svg>
                            </button>
                        </li>
                        <li>
                            <button type="button" class="dropdown-item d-flex align-items-center"
                                data-bs-theme-value="dark" aria-pressed="false">
                                <svg class="bi me-2 opacity-50" width="1em" height="1em">
                                    <use href="#moon-stars-fill"></use>
                                </svg>
                                Dark
                                <svg class="bi ms-auto d-none" width="1em" height="1em">
                                    <use href="#check2"></use>
                                </svg>
                            </button>
                        </li>
                        <li>
                            <button type="button" class="dropdown-item d-flex align-items-center active"
                                data-bs-theme-value="auto" aria-pressed="true">
                                <svg class="bi me-2 opacity-50" width="1em" height="1em">
                                    <use href="#circle-half"></use>
                                </svg>
                                Auto
                                <svg class="bi ms-auto d-none" width="1em" height="1em">
                                    <use href="#check2"></use>
                                </svg>
                            </button>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

    </div>
    <!-- bottom header starts -->
    <div class="d-flex flex-row mb-3 bg-secondary " data-bs-theme="dark">
        <div class="p-2">
            <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas"
                data-bs-target="#offcanvasScrolling" aria-controls="offcanvasScrolling">All</button>

            <div class="offcanvas offcanvas-start" data-bs-scroll="true" data-bs-backdrop="false" tabindex="-1"
                id="offcanvasScrolling" aria-labelledby="offcanvasScrollingLabel">
                <div class="offcanvas-header">
                    <h5 class="offcanvas-title bg-black text-white" id="offcanvasScrollingLabel">Hello, sign in</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                </div>
                <div class="offcanvas-body">
                    <ul>
                        <li>
                            <a href="index.html" class="">Home</a>
                        </li>
                        <li><a href="Gallery.html">Gallery</a></li>
                    </ul>

                </div>
            </div>
        </div>
        <div class="p-2"><a href="index.html" class="text-white"><button type="button"
                    class="btn btn-primary">Fresh</a></button></div>
      
        <div class="p-2"><a href="Best Seller.html" class="text-white"><button type="button" class="btn btn-primary">
                    Best
                    Seller</a></button></div>
        <div class="p-2"><a href="Mobiles.html" class="text-white"><button type="button" class="btn btn-primary">
                    Mobile</a></button></div>
        
    </div>
    <!-- Content Area -->
    <div class="">
        <div class="row row-cols-1 row-cols-md-3 g-4 bg-dark mt-3 mx-3 mb-3" data-bs-theme="dark">
            <div class="col">

                <div class="card h-100">

                    <img src="assets/images/159.jpg" class="card-img-top mt-3" alt="">
                    <div class="card-body">
                        <p>
                            Samsung
                        </p>

                        <div class="text-center">

                        </div>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">

                    <img src="assets/images/162.jpg" class="card-img-top mt-3" alt="">
                    <div class="card-body">
                        <p>
                            Ipad
                        </p>

                        <div class="text-center">

                        </div>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">

                    <img src="assets/images/98.jpg" class="card-img-top mt-3" alt="">
                    <div class="card-body">
                        <p>
                            IPhone
                        </p>

                        <div class="text-center">

                        </div>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">

                    <img src="assets/images/164.jpg" class="card-img-top mt-3" alt="">
                    <div class="card-body">
                        <p>
                            Redmi
                        </p>

                        <div class="text-center">

                        </div>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">

                    <img src="assets/images/165.jpg" class="card-img-top mt-3" alt="">
                    <div class="card-body">
                        <p>
                            Nokia
                        </p>

                        <div class="text-center">

                        </div>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">

                    <img src="assets/images/175.webp" class="card-img-top mt-3" alt="">
                    <div class="card-body">
                        <p>
                            Huawei
                        </p>

                        <div class="text-center">

                        </div>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">

                    <img src="assets/images/163.jpg" class="card-img-top mt-3" alt="">
                    <div class="card-body">
                        <p>
                            One Plus
                        </p>

                        <div class="text-center">

                        </div>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">

                    <img src="assets/images/176.webp" class="card-img-top mt-3" alt="">
                    <div class="card-body">
                        <p>
                            Google
                        </p>

                        <div class="text-center">

                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>
    <!-- footer area -->

    <footer class="footer mt-auto w-100 bg-secondary text-dark" data-bs-theme="dark">

        <div class="container bg-secondary" data-bs-theme="dark">
            <a class="logo" href="index.html"> <img class="mt-3 mx-50 justify-content-center"
                    src="assets/images/logo.png" alt="" width="50" height="50"></a>
            <footer class="py-5">
                <div class="row">
                    <div class="col-6 col-md-2 mb-3">
                        <h5>Get to know us</h5>
                        <ul class="nav flex-column">
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Carrers</a>
                            </li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Block</a>
                            </li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About
                                    Amazon</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Amazon
                                    Science</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Amazon
                                    Devices</a></li>
                        </ul>
                    </div>

                    <div class="col-6 col-md-2 mb-3">
                        <h5>Make Money</h5>
                        <ul class="nav flex-column">
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Sell
                                    Products</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Sell
                                    Apps</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Sell on
                                    Amazon business</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Advertise
                                    your Products</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Host on
                                    Amazon Hub</a></li>
                        </ul>
                    </div>

                    <div class="col-6 col-md-2 mb-3">
                        <h5>Amazon Payment </h5>
                        <ul class="nav flex-column">
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Amazon
                                    Business Card</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Shop
                                    Points</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Reload
                                    Balance</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Amazon
                                    Currency Convertor</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Points to
                                    Currency</a></li>
                        </ul>
                    </div>

                    <div class="col-md-5 offset-md-1 mb-3">
                        <form>
                            <h5>Subscribe to our newsletter</h5>

                            <div class="d-flex flex-column flex-sm-row w-100 gap-2">
                                <label for="newsletter1" class="visually-hidden">Email address</label>
                                <input id="newsletter1" type="text" class="form-control" placeholder="Email address">
                                <button class="btn btn-primary" type="button">Subscribe</button>
                            </div>
                        </form>
                    </div>
                </div>

                <div class="d-flex flex-column flex-sm-row justify-content-between py-4 my-4 border-top">
                    <p>Copyrights &copy; 2024 Company, Amazon All rights reserved.</p>
                    <ul class="list-unstyled d-flex">
                        <li class="ms-3"><i class="bi bi-twitter"></i><a class="link-body-emphasis" href="#"><svg
                                    class="bi" width="24" height="24">
                                    <use xlink:href="#twitter" />
                                </svg></a></li>
                        <li class="ms-3"><i class="bi bi-instagram"></i><a class="link-body-emphasis" href="#"><svg
                                    class="bi" width="24" height="24">
                                    <use xlink:href="#instagram" />
                                </svg></a></li>
                        <li class="ms-3"><i class="bi bi-facebook"></i><a class="link-body-emphasis" href="#"><svg
                                    class="bi" width="24" height="24">
                                    <use xlink:href="#facebook" />
                                </svg></a></li>
                    </ul>
                </div>
            </footer>
            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
                integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
                crossorigin="anonymous"></script>

</body>

</html>
