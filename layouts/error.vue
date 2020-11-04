<template>
  <div class="container">
    <div class="row align-items-center row-success justify-content-center">
      <div class="col-lg-4 text-center">
        <img
          src="~/assets/images/404-illustration.svg"
          alt="fund-success"
          class="w-100"
        />
        <h1 class="mt-4 mb-3">Oops! something wrong</h1>
        <p class="mb-4" v-if="error.statusCode === 404">
          The page you requested doesn't
          <br />
          exist at this moment
        </p>
        <p class="" v-else>An error occurred</p>
        <div class="mb-4">
          <div>
            <button
              @click="$router.push({ path: '/' })"
              class="btn btn-fund-other btn-block"
            >
              Back to Home
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['error'],
  layout: 'success',
}
</script>
