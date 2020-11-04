<template>
  <div class="container">
    <div class="row align-items-center row-success justify-content-center">
      <div class="col-lg-4 text-center">
        <div class="avatar mb-4">
          <nuxt-link to="/upload" style="position: relative">
            <img
              src="@/assets/images/avatar.svg"
              alt=""
              width="120"
              height="120"
              style="
                border-radius: 100%;
                padding: 2px;
                border: 3px solid #fea929;
              "
            />
            <img
              src="@/assets/images/icon-avatar-add.svg"
              alt=""
              style="position: absolute; right: 2%; bottom: -180%"
            />
          </nuxt-link>
        </div>
        <h1 class="mb-2 text-dark text-center">Hi, Julia</h1>
        <p class="text-dark text-center mb-4">Please upload your selfie</p>
        <div class="mb-4">
          <div class="mb-3">
            <button
              @click="$router.push({ path: '/register-success' })"
              class="btn btn-sign-up btn-block"
            >
              Sign Up
            </button>
          </div>
          <div>
            <button
              @click="$router.push({ path: '/register-success' })"
              class="btn btn-skip btn-block"
            >
              SKIP
            </button>
          </div>
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
