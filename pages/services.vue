<template>
  <div class="container">
    <h1 class="text-center display-3 mb-5">Services</h1>
    <listmaker header="Social Media & Digital Marketing" :items="social_media"></listmaker>
    <listmaker header="Virtual Assistance & Social Media Management" :items="va"></listmaker>
    <div class="text-center py-5">
        <b-link
          to="/pricing"
          class="button--green"
        >
          Pricing & Rates
        </b-link>
        <b-link
          to="/contact"
          class="button--grey"
        >
          Contact Us
        </b-link>
      </div>
  </div>
</template>

<script>
import listmaker from "@/components/listmaker";
export default {
  component: {
    'listmaker': listmaker
  },
  data() {
    return {
      social_media: ['Copywriting & Creating Posts', 'Graphics Design & Infographs', 'Sharing Blog Posts & News Article', 'Update Posts & Advertisement of the Business', 'Cold Email & Waitlist', 'Communicate Potential Customer Inquiries, Requests and Messages to the Owner', 'Sanitize Feeds & Messages for the Peace of Mind', 'Virtual Assistance Activities'],
      va: ['Responding and Managing Business Response', 'Business & Competition Research', 'Managing ECommerce Store', 'Customer Service', 'Data Entry', 'Proofreading & Editing', 'Calendar Management & Daily Planning', 'Podcast and Stream management', 'Paralegal Services']
    }
  }
}
</script>

<style>
li {
  margin: 5px;
}
</style>