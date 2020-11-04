<template>
  <div class="container-fluid">
    <div class="row">
      <!--------------------------//////////////--------------------- -->
      <div class="col-lg-6 col-md-6 d-none d-md-block image-container"></div>
      <!--------------------------//////////////--------------------- -->

      <div class="col-lg-6 col-md-6 form-container">
        <div class="col-lg-8 col-md-12 col-sm-9 col-xs-12 form-box">
          <!----------------///--------------- -->

          <div class="heading mb-3 text-dark">
            <h1 class="text-dark">Sign Up Account</h1>
          </div>

          <!---------------------------FORMS SECTION--------------------- -->
          <div class="form-input">
            <label for="">Email Address</label>
            <input
              type="email"
              placeholder="Write your email address here"
              value="julia.keeva@gmail.com"
            />
          </div>
          <div class="form-input">
            <label for="">Password</label>
            <input
              type="password"
              placeholder="Type your password here"
              value="nasigorenglimaribbu"
            />
          </div>
          <div class="mb-3">
            <button
              @click="$router.push({ path: '/' })"
              class="btn btn-next-auth btn-block"
            >
              Sign In
            </button>
          </div>
          <!---------------------------////////--------------------- -->

          <div class="text-dark text-center">
            Don't have account?
            <nuxt-link
              to="/register"
              class="login-link text-danger text-decoration-none"
              >Sign Up</nuxt-link
            >
          </div>
          <!--------------------------////////--------------------- -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'auth',
}
</script>

<style scoped></style>
