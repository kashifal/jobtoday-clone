<template>
  <div
    class="absolute right-4 top-4 z-10 flex justify-end gap-4 bg-black px-4 pt-4 md:static md:h-20 md:py-5"
  >
    <button
      class="jt-btn-secondary-inverted-next text-sm jt-btn-sm hidden text-white border items-center gap-2 px-3 rounded-md  md:flex"
      type="button"
      data-testid="navigation_download-app-button"
    >
      <span>Get the app:</span>
      <img
        src="https://jobtoday.b-cdn.net/static/images/apple-white-24.svg"
        alt="AppStore"
        width="24"
        height="24"
      />
      <img
        src="https://jobtoday.b-cdn.net/static/images/play-color-24.svg"
        alt="Google Play"
        width="24"
        height="24"
      />
    </button>
    <a
      class="jt-btn-primary-inverted-next jt-btn-sm text-black hover:bg-white/90 transition-all  duration-200 border flex items-center justify-center px-3 rounded-md bg-white text-sm"
      data-testid="header_start-hiring-button"
      href="https://jobtoday.com/gb/landings/hire"
    >Hire staff</a>
    <button
      class="jt-btn-primary-inverted-next jt-btn-sm text-black hover:bg-white/90 transition-all  duration-200 border flex items-center justify-center px-3 rounded-md bg-white text-sm"
      type="button"
      data-testid="header_log-in-button"
    >Log In</button>
  </div>
</template>

<script setup lang="ts">
</script>

<style scoped>
</style>