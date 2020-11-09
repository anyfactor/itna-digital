<template>
  <div class="container">
    <div>
      <!-- <Logo /> -->
      <b-img src="@/static/logo.png" fluid width="300px" alt="Responsive image" class="mb-5"></b-img>

      <vue-typed-js
        :strings="['Marketing', 'Sales', 'Management', 'Automation', 'Presence','💖']"
        :typeSpeed="100"
        :backSpeed="50"
      >
        <div class="h1">
          <h1 class="mb-3">Social Media <span class="typing"></span></h1>
        </div>
      </vue-typed-js>

      <h4 class="text-primary">Social Media Marketing & Management</h4>
      <h4 class="text-primary">SAAS, Tech Startup & Small Business</h4>
      <div class="links">
        <b-link
          to="/services"
          class="button--green"
        >
          Services
        </b-link>
        <b-link
          to="/contact"
          class="button--grey"
        >
          Contact Us
        </b-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.h1 {
  justify-content: center;
  margin: 0 auto;
}

</style>
