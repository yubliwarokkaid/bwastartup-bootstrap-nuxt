<template>
  <div class="page-content-home">
    <Navbar />
    <div class="bg-detail"></div>
    <section class="project-container">
      <div class="container">
        <div class="row row-project">
          <div class="col-lg-9 mb-5">
            <div class="card card-image-project">
              <img
                src="~/assets/images/project-image.jpg"
                alt="project-image"
                class="w-100"
              />
            </div>
            <div class="row mt-3">
              <div class="col-lg-3">
                <div class="card card-thumb-project">
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
                <div class="card card-thumb-project">
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
                <div class="card card-thumb-project">
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
                <div class="card card-thumb-project">
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
          </div>
          <div class="col-lg-3">
            <div class="card card-leader">
              <div class="card-body body-leader">
                <h1 class="card-title">Project Leader:</h1>
                <div class="d-flex mt-3 align-items-center">
                  <div>
                    <img
                      src="~/assets/images/testimonial-1-icon.png"
                      alt=""
                      class="w-75 rounded-circle"
                    />
                  </div>
                  <div class="mt-1">
                    <div class="title">Julia Keeva</div>
                    <div class="subtitle">28.093 backer</div>
                  </div>
                </div>
                <h2 class="mt-4">What will you get:</h2>
                <ul class="list-check list-unstyled mt-3">
                  <li>Equity of the startup directly from the founder</li>
                  <li>Special service or product that startup has</li>
                  <li>
                    You can also sell your equity once the startup going IPO
                  </li>
                </ul>
                <input
                  type="number"
                  class="form-control form-control-lg"
                  placeholder="Amount in Rp"
                />
                <div>
                  <button
                    @click="$router.push({ path: '/fund-success' })"
                    class="btn btn-fund-now btn-block mt-3"
                  >
                    Fund Now
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-9">
            <div class="detail-descreiption">
              <h2>Wireboard Fortune</h2>
              <h3>The new era of mechanical keyboard for everyone</h3>
              <div class="progress mt-4">
                <div
                  class="progress-bar progress-bar-striped progress-bar-animated"
                  role="progressbar"
                  style="width: 80%"
                  aria-valuenow="80"
                  aria-valuemin="0"
                  aria-valuemax="100"
                ></div>
              </div>
              <div class="progress-detail d-flex justify-content-between mt-3">
                <div class="percent-detail">80%</div>
                <div class="price-detail">Rp 40.000.000</div>
              </div>
              <p class="mt-4 text-dark">
                Designed to fit your dedicated typing experience. No matter what
                you like, linear, clicky or a little in between, we’ve got you
                covered with three Gateron switches options (Blue, Brown, Red).
                With a lifespan of 50 million keystroke lifespan we want to make
                sure that you experience same feedback for every keystroke.
              </p>
              <p class="mt-3 text-dark">
                With N-key rollover (NKRO on wired mode only) you can register
                as many keys as you can press at once without missing out
                characters. It allows to use all the same media keys as
                conventional macOS.
              </p>
              <p class="mt-3 text-dark">
                This keyboard can last up to 72 hours typing, or up to 9 days of
                normal use (8 hrs/day) with a 4000 mAh big battery.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <CallToAction />
    <Footer />
  </div>
</template>

<style scoped></style>
