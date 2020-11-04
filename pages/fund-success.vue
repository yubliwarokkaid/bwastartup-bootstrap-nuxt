<template>
  <div class="container">
    <div class="row align-items-center row-success justify-content-center">
      <div class="col-lg-4 text-center">
        <img
          src="~/assets/images/success-illustration.svg"
          alt="fund-success"
          class="w-100"
        />
        <h1 class="mt-4 mb-3">Yeay! You are super</h1>
        <p class="mb-4">
          Your money has ben transferred
          <br />
          into company's account
        </p>
        <div class="mb-4">
          <button
            @click="$router.push({ path: '/' })"
            class="btn btn-fund-other btn-block"
          >
            Fund Other Project
          </button>
        </div>
        <div>
          <button
            @click="$router.push({ path: '/dashboard' })"
            class="btn btn-dashboard btn-block"
          >
            My Dashboard
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'success',
}
</script>
