<template>
   <div class="md:jt-container w-full md:my-8 max-w-[1135px] mx-auto bg-gray-300 rounded-md">
    <div class="bg-jt-gray-200 relative p-4 md:rounded-3xl md:p-10">
      <h2 class="pb-12 text-3xl font-black leading-[2.1rem] tracking-tight text-black md:pb-16">Explore jobs in Lahore</h2>
      <form class="relative flex flex-col gap-4 md:flex-row" method="POST" action="/search-feed">
        <input type="hidden" name="countryCode" value="pk" /><input type="hidden" name="appHeaders" value='{"Origin":"https://jobtoday.com","user-agent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36","X-ORIGIN":"https://jobtoday.com","X-GUID":"7c793adb-8f4e-4c9a-b149-be9d3be0afdc","X-LOCALE":"en-US","X-LANGUAGE":"en","X-APP-VERSION":"2.2.2","X-TYPE":"3","X-WEB-DEVICE-TYPE":"desktop","X-SESSION-TOKEN":"","X-FORWARDED-FOR":"223.29.228.140, 10.0.103.57, 10.0.72.242"}' /><label class="relative flex flex-grow-[2]"><img class="absolute left-4 top-1/2 -translate-y-1/2" src="https://jobtoday.b-cdn.net/static/icons/ic-magnifyingglass-black-28.svg" alt="search icon" width="24" height="24" /><input class="border-jt-gray-200 rounded-2xl pl-12 text-xl font-medium w-full" type="search" name="keywordField" data-testid="search-bar_keyword" autocomplete="off" placeholder="Search jobs" value="" /></label><label class="relative flex flex-grow-[2]"><img class="absolute left-4 top-1/2 -translate-y-1/2" src="https://jobtoday.b-cdn.net/static/icons/ic-flag-PK-24x24.svg" alt="search icon" width="24" height="24" /><input class="border-jt-gray-200 rounded-2xl pl-12 text-xl font-medium w-full" type="search" name="locationField" data-testid="search-bar_location" autocomplete="off" placeholder="Which city?" value="Lahore" /></label><button class="jt-btn-primary-next h-14 bg-blue-600 text-white hover:bg-blue-600/90 w-full rounded-2xl text-lg font-medium md:w-auto md:flex-grow" type="submit" aria-label="search" data-testid="search-bar_find-button">Find Jobs</button>
      </form>
      <div class="mt-4 flex justify-center py-5 md:absolute md:right-10 md:top-2"><button class="text-jt-primary hover:text-jt-primary-dark text-lg font-medium" type="button" data-testid="search-bar_show-all-jobs-in-location ">Show all jobs in Lahore</button></div>
    </div>
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>