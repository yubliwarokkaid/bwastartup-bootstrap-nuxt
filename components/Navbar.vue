<template>
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <a class="navbar-brand" href="/">
        <img src="@/assets/images/logo-1.svg" alt="logo" class="w-100" />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" href="/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/project.html">Project</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Success Stories</a>
          </li>
        </ul>
        <div class="button-auth">
          <nuxt-link to="/register" class="btn btn-register">Sign Up</nuxt-link>
          <nuxt-link to="/login" class="btn btn-account">
            My Account
          </nuxt-link>
        </div>
      </div>
    </div>
  </nav>
</template>
