<template>
  <div class="page-content-dashboard">
    <Navbar />
    <div class="bg-dashbaard"></div>
    <section class="page-dashboard">
      <div class="container">
        <div class="row d-flex justify-content-around align-items-center">
          <div class="col-lg-12">
            <div class="title">
              <h2>Dashboard</h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <div class="all-detail">
              <nuxt-link to="/dashboard" class="mr-3 project"
                >Your Projects</nuxt-link
              >
              <nuxt-link to="/dashboard/transaction" class="transaction active"
                >Your Transactions</nuxt-link
              >
            </div>
            <div
              class="card card-dashboard-transaction mb-3"
              v-for="i in 5"
              :key="i"
            >
              <div class="row g-0 align-items-center">
                <div class="col-md-2">
                  <img
                    src="~/assets/images/img-dummy.svg"
                    alt="card-dummy"
                    class="card-img"
                  />
                </div>
                <div class="col-md-10">
                  <div class="card-body">
                    <div class="detail-desc">
                      <h3 class="card-title">Cari Uang Buat Gunpla</h3>
                      <p class="amount-text">
                        <small>Rp. 200.000.000 · 12 September 2020</small>
                      </p>
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
