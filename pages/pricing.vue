<template>
  <div class="container">
    <h1 class="text-center display-3">Rates & Price</h1>
    <!-- <h4 class="text-info text-center mb-5">$7/Hour - $50/Week</h4> -->
    <div>
      <div class="col d-flex justify-content-center py-5">
        <b-card no-body class="overflow-hidden" style="max-width: 700px;">
          <b-row no-gutters>
            <b-col md="6">
              <b-card-img src="@/static/50dollar.png" alt="Image" class="rounded-0"></b-card-img>
            </b-col>
            <b-col md="6">
              <b-card-body title="Social Media Management">
                <b-card-text>
                    1 hour of dedicated service each day. Total Service Hours per Week: 7-10 Hours.
                  <ul>
                    <li>Social Media Management</li>
                    <li>Graphics & Video Design</li>
                    <li>Marketing Research</li>
                    <li>Automation Implementation</li>
                    <li>Community Engagement</li>
                    <li>Dedicated Programming etc.</li>
                  </ul>
                  <b-link to="/contact">Contact Us</b-link> to know more.
                </b-card-text>
              </b-card-body>
            </b-col>
          </b-row>
        </b-card>
      </div>
      <div class="col d-flex justify-content-center py-5">
        <b-card no-body class="overflow-hidden" style="max-width: 700px;">
          <b-row no-gutters>
            <b-col md="6">
              <b-card-img src="@/static/25dollar.png" alt="Image" class="rounded-0"></b-card-img>
            </b-col>
            <b-col md="6">
              <b-card-body title="Virtual Assistance">
                <b-card-text>
                  Best suited for One Time Gigs or Virtual Assistance Service. Duties can be -
                  <ul>
                    <li>Data Entry</li>
                    <li>Graphics Design</li>
                    <li>Market Research</li>
                    <li>Microsoft Office Tasks</li>
                    <li>Organizing Mails and Files etc.</li>
                  </ul>
                  <b-link to="/contact">Contact Us</b-link> to know more.
                </b-card-text>
              </b-card-body>
            </b-col>
          </b-row>
        </b-card>
      </div>
      <div class="col d-flex justify-content-center py-5">
        <b-card no-body class="overflow-hidden" style="max-width: 700px;">
          <b-row no-gutters>
            <b-col md="6">
              <b-card-img src="@/static/6dollar.png" alt="Image" class="rounded-0"></b-card-img>
            </b-col>
            <b-col md="6">
              <b-card-body title="Automation & Data Programming">
                <b-card-text>
                  Programming for your need
                  <ul>
                    <li>Python Programming</li>
                    <li>Automation & Web Scraping</li>
                    <li>Web & API Development</li>
                    <li>Data Analytics & Data Visualization</li>
                    <li>Cloud Implementation etc.</li>
                    <li>Etc.</li>
                  </ul>
                  <b-link href="https://www.anyfactor.xyz">Contact AnyFactor</b-link> to know more.
                </b-card-text>
              </b-card-body>
            </b-col>
          </b-row>
        </b-card>
      </div>
    </div>
    
    <div class="text-center py-5">
        <b-button
          size="lg"
          to="/contact"
          pill variant="info"
        >
          Contact Us
        </b-button>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
</style>