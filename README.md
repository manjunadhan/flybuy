# flybuy
A responsive e-commerce website 

<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/d1c2ea8b80.js" crossorigin="anonymous"></script>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#"><img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-website-logo-img.png" class="ecommerce-logo" /></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav ml-auto">
                <a class="nav-link active text-dark" href="#home">
                    Home
                    <span class="sr-only">(current)</span>
                </a>
                <a class="nav-link text-dark" href="#servi">Services</a>
                <a class="nav-link text-dark" href="#">Products</a>
                <a class="nav-link text-dark" href="#">Explore Deals & Offers</a>
                <a class="nav-link text-dark" href="#trending">Trending Blogs</a>
            </div>
        </div>
    </nav>
    <div id="carouselExampleIndicators" class="carousel slide ecommerce-carousel-container" data-ride="carousel" id="home">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-carousel-1-img.png" class="d-none d-md-inline w-100 h-100" alt="..." />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-carousel-1-sm-img.png" class="d-inline d-md-none w-100 h-100" alt="..." />
            </div>
            <div class="carousel-item">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-carousel-2-img.png" class="d-none d-md-inline w-100 h-100" alt="..." />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-carousel-2-sm-img.png" class="d-inline d-md-none w-100 h-100" alt="..." />
            </div>
            <div class="carousel-item">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-carousel-3-img.png" class="d-none d-md-inline w-100 h-100" alt="..." />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-carousel-3-sm-img.png" class="d-inline d-md-none w-100 h-100" alt="..." />
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>

    <div class="pt-5 pb-5" id="servi">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h1 class="services-section-heading">Our Services</h1>
                    <p class="services-section-description">
                        Most online stores offer lower prices. Online shopping makes price
                        comparison simpler and quicker. It is very convenient to shop from
                        where you are located. It saves you the cost of driving to stores,
                        as well as parking fees.
                    </p>
                </div>
                <div class="col-12 col-md-4">
                    <div class="shadow p-3 text-center mb-3">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-services-delivery-img.png" class="services-card-image" />
                        <h1 class="services-card-title">Fast and Free Delivery</h1>
                        <p class="services-card-description">
                            Fast, free, and convenient delivery choices on millions of items.
                        </p>
                    </div>
                </div>
                <div class="col-12 col-md-4">
                    <div class="shadow p-3 text-center mb-3">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-services-money-back-img.png" class="services-card-image" />
                        <h1 class="services-card-title">100% Money back guarantee</h1>
                        <p class="services-card-description">
                            This is probably the most popular guarantee in the world.
                        </p>
                    </div>
                </div>
                <div class="col-12 col-md-4">
                    <div class="shadow p-3 text-center mb-3">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-services-24-by-7-support-img.png" class="services-card-image" />
                        <h1 class="services-card-title">Online Support 24/7</h1>
                        <p class="services-card-description">
                            Our Online Support will provide you with many useful functions,
                            valuable information, tips.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="pt-5 pb-5">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h1 class="products-section-heading mb-3">Our Products</h1>
                </div>
                <div class="col-12 col-md-6">
                    <div class="products-card headphones-bg-container d-flex flex-column justify-content-end mb-3">
                        <h1 class="products-card-title">Smart Headphones</h1>
                        <p class="products-card-description">
                            Headphones with Deep Bass, sound,touch...
                        </p>
                        <div>
                            <button type="button" class="products-card-button" data-toggle="modal" data-target="#smartHeadphonesModel">
                                View Details
                            </button>
                            <div class="modal fade" id="smartHeadphonesModel" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                                <div class="modal-dialog mt-5">
                                    <div class="modal-content">
                                        <div class="modal-header">
                                            <h5 class="modal-title products-card-modal-title" id="examcard-modal-pleModalLabel">
                                                Sony WH-1000XM4 Noise Cancelling Headphones
                                            </h5>
                                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                                <span aria-hidden="true">&times;</span>
                                            </button>
                                        </div>
                                        <div class="modal-body">
                                            <p class="products-card-modal-description">
                                                Get Best Smart Headphones Prices Online in India.
                                                Select from the best range of Headphones from most
                                                popular brands...
                                            </p>
                                            <ul class="products-card-modal-list">
                                                <li class="products-card-modal-list-item">
                                                    <span class="products-card-modal-list-item-category">Voice assistant:</span> Alexa, Google Assistant & Siri
                                                </li>
                                                <li class="products-card-modal-list-item">
                                                    <span class="products-card-modal-list-item-category">Smart listening:</span> Ambient sound with the best noise
                                                    cancellation
                                                </li>
                                                <li class="products-card-modal-list-item">
                                                    <span class="products-card-modal-list-item-category">Long battery life:</span> A single charge provides 30 hours
                                                    of playtime
                                                </li>
                                                <li class="products-card-modal-list-item">
                                                    <span class="products-card-modal-list-item-category">Quick charging:</span> Charge for 10 min for 5 hours
                                                    play back
                                                </li>
                                                <li class="products-card-modal-list-item">
                                                    <span class="products-card-modal-list-item-category">Touch controls:</span> Change the track with your fingertip
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="modal-footer">
                                            <button type="button" class="btn btn-outline-dark" data-dismiss="modal">
                                                Buy Now
                                            </button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6">
                    <div class="products-card laptop-bg-container d-flex flex-column justify-content-end mb-3">
                        <h1 class="products-card-title">Laptops</h1>
                        <p class="products-card-description">
                            Explore vast selection of Laptops...
                        </p>
                        <div>
                            <button type="button" class="products-card-button" data-toggle="modal" data-target="#laptopsModal">
                                View Details
                            </button>
                            <div class="modal fade" id="laptopsModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                                <div class="modal-dialog mt-5">
                                    <div class="modal-content">
                                        <div class="modal-header">
                                            <h5 class="modal-title products-card-modal-title" id="exampleModalLabel">
                                                Inspiron 14 5490 core i5 Laptop
                                            </h5>
                                            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                                <span aria-hidden="true">&times;</span>
                                            </button>
                                        </div>
                                        <div class="modal-body">
                                            <p class="products-description">
                                                Get Best Laptop Prices Online in India. Select from
                                                the best range of Laptops from most popular brands...
                                            </p>
                                            <ul class="products-card-modal-list">
                                                <li class="products-card-modal-list-item">
                                                    <span class="products-card-modal-list-item-category">Performance:</span> Core i5 3rd Gen, 2.6 Ghz, 4 GB RAM
                                                </li>
                                                <li class="products-card-modal-list-item"><span class="products-card-modal-list-item-category">Storage:</span> 500 GB HDD, SATA, 7200 RPM</li>
                                                <li class="products-card-modal-list-item"><span class="products-card-modal-list-item-category">Battery:</span> Li-Ion, 6 Cell</li>
                                                <li class="products-card-modal-list-item">
                                                    <span class="products-card-modal-list-item-category">Design:</span> 14.0 Inches, 1366 X 768 , 2.07 Kg, 34 Mm
                                                    Thick
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="modal-footer">
                                            <button type="button" class="btn btn-outline-dark" data-dismiss="modal">
                                                Buy Now
                                            </button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 d-flex flex-row justify-content-end">
                    <a class="products-section-link" href="">
                        See All Offers
                        <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z" />
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </div>

    <div class="pt-5 pb-5">
        <div class="container bg-container d-flex flex-column justify-content-center">
            <div class="row">
                <div class="col-12 col-md-2 order-1 order-md-2">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-offers-special-img.png" class="w-100" />
                </div>
                <div class="col-12 col-md-6 order-2 order-md-3 mb-2">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-offers-appliances-img.png" class="w-100" />
                </div>
                <div class="col-12 col-md-4 order-3 order-md-1 d-flex flex-column justify-content-center">
                    <h1 class="offers-section-heading mb-2">BEST NEW YEAR SPECIAL OFFERS</h1>
                    <p class="offers-section-description mb-2">Best time to buy. Save upto <span class="offer-in-percent">70% cash</span></p>
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-offers-credit-card-img.png" class="offers-section-discount-image" />
                </div>
            </div>
        </div>
    </div>


    <div class="explore-section pt-5 pb-5">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h1 class="explore-section-heading mb-3">Explore Deals & Offers</h1>
                </div>
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="shadow explore-card p-3 mb-3">
                        <h1 class="explore-card-title">
                            Up to 80% Off | Electronics & Gadgets
                        </h1>
                        <div class="d-flex flex-row">
                            <div class="text-center">
                                <div class="explore-card-image-container">
                                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-mamba-watch-img.png" class="explore-card-image" />
                                </div>
                                <h1 class="explore-card-product-title">Smart Watch</h1>
                            </div>
                            <div class="text-center">
                                <div class="explore-card-image-container">
                                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-camera-img.png" class="explore-card-image" />
                                </div>
                                <h1 class="explore-card-product-title">Cameras</h1>
                            </div>
                        </div>
                        <div class="d-flex flex-row">
                            <div class="text-center">
                                <div class="explore-card-image-container">
                                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-sport-and-fitness-img.png" class="explore-card-image" />
                                </div>
                                <h1 class="explore-card-product-title">Sports & Fitness</h1>
                            </div>
                            <div class="text-center">
                                <div class="explore-card-image-container">
                                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-ear-phones-pink-img.png" class="explore-card-image" />
                                </div>
                                <h1 class="explore-card-product-title">Earphones</h1>
                            </div>
                        </div>
                        <a class="explore-card-link" href="">
                            See All Deals
                            <svg width="16px" height="16px" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="#ff9f00" xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd" d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z" />
                            </svg>
                        </a>
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="shadow explore-card p-3 mb-3">
                        <h1 class="explore-card-title">
                            Festive Offers TVs & appliances
                        </h1>
                        <div class="explore-card-image-container">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-tv-img.png" class="explore-card-image" />
                        </div>
                        <a class="explore-card-link" href="">
                            See All Deals
                            <svg width="16px" height="16px" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="#ff9f00" xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd" d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z" />
                            </svg>
                        </a>
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="shadow explore-card p-3 mb-3">
                        <h1 class="explore-card-title mt-3">
                            Under Rs 4000 | Friendly Accessories
                        </h1>
                        <div class="d-flex flex-row">
                            <div class="text-center">
                                <div class="explore-card-image-container">
                                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-tablet-device-img.png" class="explore-card-image" />
                                </div>
                                <h1 class="explore-card-product-title">Tablet</h1>
                            </div>
                            <div class="text-center">
                                <div class="explore-card-image-container">
                                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-joy-stick-img.png" class="explore-card-image" />
                                </div>
                                <h1 class="explore-card-product-title">PlayStation</h1>
                            </div>
                        </div>
                        <div class="d-flex flex-row">
                            <div class="text-center">
                                <div class="explore-card-image-container">
                                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-speakers-big-img.png" class="explore-card-image" />
                                </div>
                                <h1 class="explore-card-product-title">Speakers</h1>
                            </div>
                            <div class="text-center">
                                <div class="explore-card-image-container">
                                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-explore-vr-set-img.png" class="explore-card-image" />
                                </div>
                                <h1 class="explore-card-product-title">Virtual Reality Set</h1>
                            </div>
                        </div>
                        <a class="explore-card-link" href="">
                            See All Deals
                            <svg width="16px" height="16px" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="#ff9f00" xmlns="http://www.w3.org/2000/svg">
                                <path fill-rule="evenodd" d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z" />
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>



    <div class="pt-5 pb-5" id="trending">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h1 class="trending-blogs-section-heading mb-3">Trending Blogs</h1>
                </div>
                <div class="col-12 col-md-6">
                    <div class="shadow mb-3">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-trending-blogs-1-img.png" class="w-100" />
                        <div class="p-3">
                            <h1 class="trending-blogs-card-sub-title">Fountain Pens</h1>
                            <h1 class="trending-blogs-card-title">Guide to Fountain Pen Nibs</h1>
                            <p class="trending-blogs-card-description">
                                If you’re having trouble with a fountain pen whether it’s scratchy, too dry, or too wet...
                            </p>
                            <a class="trending-blogs-card-link" href="">
                                READ MORE
                                <svg width="16px" height="16px" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z" />
                                </svg>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6">
                    <div class="shadow mb-3">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-trending-blogs-2-img.png" class="w-100" />
                        <div class="p-3">
                            <h1 class="trending-blogs-card-sub-title">Productivity</h1>
                            <h1 class="trending-blogs-card-title">How to Craft a Better Todo List</h1>
                            <p class="trending-blogs-card-description">
                                A well-crafted Todo list acts as a guiding light for your day. It helps you overcome...
                            </p>
                            <a class="trending-blogs-card-link" href="">
                                READ MORE
                                <svg width="16px" height="16px" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z" />
                                </svg>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="contact-us-section pt-5 pb-5 text-center">
        <h1 class="contact-us-section-heading mb-3">Let us Join Together</h1>
        <button class="custom-button">CONTACT US</button>
    </div>

    <div class="ecommerce-footer-section pt-5 pb-5">
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-6 col-lg-3">
                    <div class="text-center text-md-left">
                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/ecommerce-website-logo-img.png" class="ecommerce-logo" />
                        <div class="d-flex flex-row justify-content-center justify-content-md-start mt-3 mb-3">
                            <div class="ecommerce-footer-section-icon-container">
                                <i class="fab fa-google icon"></i>
                            </div>
                            <div class="ecommerce-footer-section-icon-container">
                                <i class="fab fa-twitter icon"></i>
                            </div>
                            <div class="ecommerce-footer-section-icon-container">
                                <i class="fab fa-instagram icon"></i>
                            </div>
                            <div class="ecommerce-footer-section-icon-container">
                                <i class="fa fa-linkedin-square icon"></i>
                            </div>
                        </div>
                        <p class="ecommerce-footer-section-address">
                            37, Ayur Vigyan Nagar, New Delhi, India.
                        </p>
                    </div>
                </div>
                <div class="col-6 col-lg-3 mt-3">
                    <h1 class="ecommerce-footer-section-heading mb-3">Get to know us</h1>
                    <ul class="ecommerce-footer-section-list">
                        <li class="ecommerce-footer-section-list-item">About us</li>
                        <li class="ecommerce-footer-section-list-item">Career</li>
                        <li class="ecommerce-footer-section-list-item">Press Releases</li>
                        <li class="ecommerce-footer-section-list-item">Gift a smile</li>
                    </ul>
                </div>
                <div class="col-6 col-lg-3 mt-3">
                    <h1 class="ecommerce-footer-section-heading mb-3">Contact with Us</h1>
                    <ul class="ecommerce-footer-section-list">
                        <li class="ecommerce-footer-section-list-item">Facebook</li>
                        <li class="ecommerce-footer-section-list-item">Twitter</li>
                        <li class="ecommerce-footer-section-list-item">Instagram</li>
                    </ul>
                </div>
                <div class="col-6 col-lg-3 mt-3">
                    <h1 class="ecommerce-footer-section-heading mb-3">
                        Let Us Help You
                    </h1>
                    <ul class="ecommerce-footer-section-list">
                        <li class="ecommerce-footer-section-list-item">
                            100% Purchase Protection
                        </li>
                        <li class="ecommerce-footer-section-list-item">Your Account</li>
                        <li class="ecommerce-footer-section-list-item">Return Centre</li>
                        <li class="ecommerce-footer-section-list-item">Help</li>
                    </ul>
                </div>
            </div>
            <hr class="hr-line" />
            <div class="text-center">
                <i class="fa fa-copyright icon" aria-hidden="true"></i>
                <span class="ecommerce-footer-section-copyright">
                    2020 by Manjunadhan. Created with Bootstrap.
                </span>
            </div>
        </div>
    </div>

</body>

</html>
