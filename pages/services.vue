<template>
  <div class="container">
    <h1 class="text-center display-3">Services</h1>
    <h4 class="text-center mb-5">Marketing, Sales, Management, Automation & Presence </h4>
    <listmaker header="Social Media & Digital Marketing" :items="marketing"></listmaker>
    <listmaker header="Social Media Sales" :items="sales"></listmaker>
    <listmaker header="Social Media Management" :items="management"></listmaker>
    <listmaker header="Social Media Automation" :items="automation"></listmaker>
    <listmaker header="Social Media Presence" :items="presence"></listmaker>
    <div class="text-center pt-5">
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
          Contact
        </b-link>
      </div>
    <div class="text-center pt-3 pb-5">
        <!-- <b-link
          to="/skills"
          class="button--grey"
        >
          Skills
        </b-link> -->
        <b-link
          to="/cases"
          class="button--green"
        >
          Case Studies
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
      marketing : ['Market & Competition Research', 'Business Development', 'Graphics Design & Infographics', 'Animated Ads & Explainer Videos', 'Social Media Outreach Engagement', 'Cold Email & Waitlist', 'Cross Promotional Activities'],
      sales: ['Finding & Investigating Forums for Potential Customer', 'AIDA Comments & Messages (Attention, Interest, Decision, Action)', 'Value-Added DMs', 'Warm Email'],
      management: ['Social Media & Community Activity', 'Update Post & Advertise Business', 'Finding & Sharing Useful Resources', 'Detoxify & Sanitization', 'Virtual Assistance Activities', 'Responding and Managing Business Response & Requests', 'Managing ECommerce Store & Website', 'Customer Assistance Service', 'Calendar Management & Daily Planning', 'Podcast and Stream management'],
      automation: ['Python Based Automation Service', 'Technology Driven Social Media Management'],
      presence: ['Maintain Community Engagement for Potential Opportunity', 'Engage Discussion to Plug Business', 'Guerilla Marketing', 'Trigger Discussion with Hidden Promotional Message']
    }
  }
}
</script>

<style>
li {
  margin: 5px;
}
</style>