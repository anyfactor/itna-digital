<template>
  <div class="container">
    <div>
      <!-- <Logo /> -->
      <b-img src="@/static/logo.png" fluid width="300px" alt="Responsive image" class="mb-5"></b-img>
      <h1 class="text-center mb-3">Intelligence Technology Niche Assistance</h1>
      <h4 class="text-primary">Social Media & Community Management | Virtual Assistance</h4>
      <h4 class="text-primary">Digital Marketing | Online Business Management</h4>
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
  min-height: 100vh;
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
</style>
