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
              class="all-new-project d-flex justify-content-between align-items-center"
            >
              <h3>Create New Projects</h3>
              <nuxt-link
                class="btn btn-save py-1 px-3"
                to="/dashboard/create"
                role="button"
                >Save</nuxt-link
              >
            </div>
            <div class="card card-new-project">
              <div class="card-body body-new-project">
                <div class="row g-3">
                  <div class="col-md-6">
                    <label for="campaignName">CAMPAIGN NAME</label>
                    <input
                      type="text"
                      class="form-control"
                      id="campaignName"
                      placeholder="Contoh: Demi Gunpla Demi Istri"
                    />
                  </div>
                  <div class="col-md-6">
                    <label for="priceCampaign">PRICE</label>
                    <input
                      type="number"
                      class="form-control"
                      id="priceCampaign"
                      placeholder="Contoh: 200000"
                    />
                  </div>
                  <div class="col-12">
                    <label for="shortDescription">SHORT DESCRIPTION</label>
                    <input
                      type="text"
                      class="form-control"
                      id="shortDescription"
                      placeholder="Deskripsi singkat mengenai projectmu"
                    />
                  </div>
                  <div class="col-12">
                    <label for="whatWill">WHAT WILL BACKERS GET</label>
                    <input
                      type="text"
                      class="form-control"
                      id="whatWill"
                      placeholder="Contoh: Ayam, Nasi Goreng, Piring"
                    />
                  </div>
                  <div class="col-12">
                    <div class="form-group">
                      <label for="description">DESCRIPTION</label>
                      <textarea
                        id="description"
                        class="form-control"
                        rows="3"
                        placeholder="Isi deskripsi panjang untuk projectmu..."
                      ></textarea>
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
