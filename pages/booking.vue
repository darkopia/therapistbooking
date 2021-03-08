<template>
  <div>
    <navbar />
    <div class="container">
      <div>
        <h1 class="title">Booking</h1>
        <!-- Calendly inline widget begin -->
        <div
          class="calendly-inline-widget"
          data-url="https://calendly.com/benjaminklea?hide_gdpr_banner=1&hide_landing_page_details=1"
          style="min-width: 600px; height: 700px"
        ></div>
        <script
          type="text/javascript"
          src="https://assets.calendly.com/assets/external/widget.js"
          async
        ></script>
        <!-- Calendly inline widget end -->
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
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
