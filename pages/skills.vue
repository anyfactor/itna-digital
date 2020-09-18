<template>
  <div class="container">
    <h1 class="text-center display-3 mb-5">Technical & Tehnological Skills</h1>
    <listmaker
      header="Human Skills"
      :items="human"
    />
    <listmaker
      header="Software Skills"
      :items="software"
    />
    <h2 class="py-4">
      Programming Skills by <a href="http://www.anyfactor.xyz" target="_blank" rel="noopener noreferrer">AnyFactor</a>
      <ul class="h4 text-body">
        <li class="m-3">
          <b-link href="https://twitter.com/anyfactor/status/1306707048214622208" target="_blank" rel="noopener noreferrer">Automated twitter posting with images sourced from local files, API or other websites</b-link>
        </li>
        <li class="m-3">
          <b-link href="https://twitter.com/anyfactor/status/1306701652397715456" target="_blank" rel="noopener noreferrer">Rapid graphical text video/gif productions in 5-10 minutes from blogs or other text contents</b-link>
        </li>
      </ul>
    </h2>
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
import listmaker from '@/components/listmaker'
export default {
  components: {
    'listmaker': listmaker
  },
  data () {
    return {
      human: ['Copywriting & Content Creation', 'Market, Target Demographics & Competition Research', 'Startup & Passive Investment Management', 'Community Engagement & Cultural Empathy', 'Copywriting posts, adverts, engagement email, waitlist emails etc','Data Entry and Rapid Typing', 'Near Native Fluency in English'],
      software: ['Intermediate skills in Photoshop, Canva and other image processing software', 'Intermediate level skills in Video Editing & Slide Presentation using VSDC, Canca, Powerpoint, FFMPEG', 'Graphics Design, Custom GIFs & Memes', 'Mail Sending Tool such as: SendGrid', 'Various SEO and Tag Management Tools', 'Post Scheduling Tools']

    }
  }
}
</script>

<style>

</style>