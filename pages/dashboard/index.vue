<template>
  <div class="page-content-dashboard">
    <Navbar />
    <div class="bg-dashbaard"></div>
    <section class="page-dashboard">
      <div class="container">
        <div class="row d-flex justify-content-around align-items-center">
          <div class="col-lg-6">
            <div class="title">
              <h2>Dashboard</h2>
            </div>
          </div>
          <div class="col-lg-6">
            <div class="button-campaign text-right">
              <nuxt-link
                to="/dashboard/create"
                role="button"
                class="btn btn-create"
                >Create Campaign</nuxt-link
              >
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <div class="all-detail">
              <nuxt-link to="/dashboard" class="mr-3 project active"
                >Your Projects</nuxt-link
              >
              <nuxt-link to="/dashboard/transaction" class="transaction"
                >Your Transactions</nuxt-link
              >
            </div>
            <div
              class="card card-dashboard-detail mb-3"
              v-for="i in 5"
              :key="i"
            >
              <div class="row g-0 align-items-center">
                <div class="col-md-2">
                  <img
                    src="~/assets/images/card-img-client.svg"
                    alt="card-cliet"
                    class="card-img"
                  />
                </div>
                <div class="col-md-10">
                  <div class="card-body">
                    <div class="detail-desc">
                      <h3 class="card-title">Cari Uang Buat Gunpla</h3>
                      <p class="amount-text">
                        <small>Rp. 200.000.000 · 80%</small>
                      </p>
                      <p class="card-text">
                        With N-key rollover (NKRO on wired mode only) you can
                        register as many keys as you can press at once without
                        missing out characters. It allows to use all the same
                        media keys as conventional macOS.
                      </p>
                      <nuxt-link
                        class="btn btn-detail"
                        :to="'/dashboard/projects/' + i"
                        role="button"
                        >Detail</nuxt-link
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>
