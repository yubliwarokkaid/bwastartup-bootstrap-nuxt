<template>
  <div class="page-content-dashboard">
    <Navbar />
    <div class="bg-dashbaard"></div>
    <section class="page-dashboard">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="title">
              <h2>Dashboard</h2>
            </div>
          </div>
        </div>
        <div class="row mb-4">
          <div class="col-lg-12">
            <div
              class="all-campaign d-flex justify-content-between align-items-center"
            >
              <h3>Campaign Details</h3>
              <button
                @click="$router.push({ path: '/dashboard/create' })"
                class="btn btn-edit py-1 px-3"
              >
                Edit
              </button>
            </div>
            <div class="card card-dashboard-campaign">
              <div class="card-body body-campaign align-items-center">
                <h4 class="title-campaign mb-3">Cari Uang Buat Gunpla</h4>
                <h5 class="subtitle-campaign">Description</h5>
                <p class="text-campaign">
                  Designed to fit your dedicated typing experience. No matter
                  what you like, linear, clicky or a little in between, we’ve
                  got you covered with three Gateron switches options (Blue,
                  Brown, Red). With a lifespan of 50 million keystroke lifespan
                  we want to make sure that you experience same feedback for
                  every keystroke.
                </p>
                <p class="text-campaign">
                  With N-key rollover (NKRO on wired mode only) you can register
                  as many keys as you can press at once without missing out
                  characters. It allows to use all the same media keys as
                  conventional macOS.
                </p>
                <h5 class="subtitle-campaign">What Will Funders Get</h5>
                <ul class="mb-4">
                  <li>Equity of the startup directly from the founder</li>
                  <li>Special service or product that startup has</li>
                  <li>
                    You can also sell your equity once the startup going IPO
                  </li>
                </ul>
                <h5 class="subtitle-campaign">Price</h5>
                <h6 class="price-amount">200.000</h6>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <div
              class="all-campaign-upload d-flex justify-content-between align-items-center"
            >
              <h3>Gallery</h3>
              <button
                @click="$router.push({ path: '/dashboard/create' })"
                class="btn btn-upload py-1 px-3"
              >
                Upload
              </button>
            </div>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col-lg-3">
            <div class="card card-thumb-dashboard">
              <div class="item-thumbnail">
                <img
                  src="~/assets/images/project-slider-1.jpg"
                  alt=""
                  class="w-100"
                />
              </div>
            </div>
          </div>
          <div class="col-lg-3">
            <div class="card card-thumb-dashboard">
              <div class="item-thumbnail">
                <img
                  src="~/assets/images/project-slider-2.jpg"
                  alt=""
                  class="w-100"
                />
              </div>
            </div>
          </div>
          <div class="col-lg-3">
            <div class="card card-thumb-dashboard">
              <div class="item-thumbnail">
                <img
                  src="~/assets/images/project-slider-3.jpg"
                  alt=""
                  class="w-100"
                />
              </div>
            </div>
          </div>
          <div class="col-lg-3">
            <div class="card card-thumb-dashboard">
              <div class="item-thumbnail">
                <img
                  src="~/assets/images/project-slider-4.jpg"
                  alt=""
                  class="w-100"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="row mt-5">
          <div class="col-lg-12">
            <h3 class="history-transaction mb-4">Transaction History</h3>
            <div class="card card-history">
              <div class="card-body body-history align-items-center">
                <h5 class="title-history">Yubli Audy Warokka</h5>
                <p class="card-text">
                  <small>Rp. 200.000 · 11 October 2020</small>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>
