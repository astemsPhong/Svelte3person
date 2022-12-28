<svelte:head>
	<title>Test</title>
	<meta name="description" content="Test Svelte" />
</svelte:head>
<script>
    
</script>

<section>
    <div class="container text-center">
        <div class="row">
          <div class="col-sm">
            BEST SELLER
          </div>
        </div>
    </div>
    <hr class="accessory">
    <div class="container text-center">
        <!-- <div class="row">
          <div class="col-sm">
            FOODWEAR
          </div>
        </div> -->
        <div class="container text-center">
            <div class="row align-items-start">
                <div class="col-4">
                    <div class="product-item">
                        <div class="product-pic">
                            <img src="https://glab.vn/storage/products/2022/12/27/480x320/63aaae0d2dc6e.jpg" alt="" style="display: inline-block;">
                        </div>
                        <div class="product-info">
                            <p class="product-name">
                                <a href="0">AIR JORDAN 1 RETRO HIGH OG CHICAGO LOST AND FOUND</a>
                            </p>
                            <p class="product-price">
                                <span>đ 2,500,000</span>
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="product-item">
                        <div class="product-pic ">
                            <img src="https://glab.vn/storage/products/2022/12/27/480x320/63aaae0d2dc6e.jpg" alt="" style="display: inline-block;">
                        </div>
                        <div class="product-info ">
                            <p class="product-name">
                                <a href="0">AIR JORDAN 1 RETRO HIGH OG CHICAGO LOST AND FOUND</a>
                            </p>
                            <p class="product-price">
                                <span>đ 2,500,000</span>
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="product-item">
                        <div class="product-pic">
                            <img src="https://glab.vn/storage/products/2022/12/27/480x320/63aaae0d2dc6e.jpg" alt="" style="display: inline-block;">
                        </div>
                        <div class="product-info ">
                            <p class="product-name">
                                <a href="0">AIR JORDAN 1 RETRO HIGH OG CHICAGO LOST AND FOUND</a>
                            </p>
                            <p class="product-price">
                                <span>đ 2,500,000</span>
                            </p>
                        </div>
                    </div>
                </div>
              </div>
        </div>
    </div>
    <div class="container text-center">
        <div class="row">
          <div class="col-sm">
            APPAREL
          </div>
        </div>
    </div>
    <div class="container text-center">
        <div class="row">
          <div class="col-sm">
            ACCESSORIES
          </div>
        </div>
    </div>
</section>
<style>
/* Reset */

    hr {
    border: 0;
    margin: 1.35em auto;
    max-width: 100%;
    background-position: 50%;
    box-sizing: border-box;
    }
    .accessory {
    height: 6px;
    background-image: radial-gradient(
        closest-side,
        hsla(0, 0%, 50%, 1.0),
        hsla(0, 0%, 50%, 0) 100%);
    position: relative;
    }
    .product-pic img{
        border: 0;
        max-width: 100%;
        height: auto;
        max-height: 100%;
        margin: 0 5px;
    }
    p{
        margin: 0;
    }
    .product-name a{
        font-size: 13px;
        color: black;
    }
    .product-price span{
        font-size: 13px;
        color: gray;
    }
</style>
