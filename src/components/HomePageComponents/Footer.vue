<template>
    <footer class="bg-jt-gray-50 sticky top-[100vh] border-t border-gray-100 py-8 print:hidden">
  <section class="footer jt-container grid-cols-2 md:grid-cols-4">
    <div data-testid="footer_grid">
      <p class="footer-title opacity-100">Employers</p>
      <a class="text-base text-black" href="https://jobtoday.com/gb/landings/hire">Hire Staff</a><a class="text-base text-black" href="https://jobtoday.com/gb/landings/advertise-for-free">Advertise a job</a><a class="text-base text-black" href="https://jobtoday.com/gb/blog/employer-advice/">Employers Blog</a><a class="text-base text-black" href="https://jobtoday.com/gb/candidates">Candidates</a><a class="text-base text-black" href="https://jobtoday.com/gb/job-description">Job description templates</a><a class="text-base text-black" href="https://jobtoday.com/gb/landings/recruitment">Recruitment tools</a>
    </div>
    <div data-testid="footer_grid">
      <p class="footer-title opacity-100">Job Seekers</p>
      <a class="text-base text-black" href="https://jobtoday.com/gb/blog/career-advice/">Career advice</a><a class="text-base text-black" href="https://jobtoday.com?skipRedirect=true">JOB TODAY Global</a>
    </div>
    <div data-testid="footer_grid">
      <p class="footer-title opacity-100">JOB TODAY</p>
      <a class="text-base text-black" href="/gb/landings/app">Get the App</a><a class="text-base text-black" href="https://jobtoday.com/gb/about-us/">About JOB TODAY</a><a class="text-base text-black" href="https://help.jobtoday.com/">Help Center</a><a class="text-base text-black" href="/gb/hub/queries">All job categories</a><a class="text-base text-black" href="/gb/hub/locations">All job locations</a><a class="text-base text-black" href="/gb/legal/privacy">Privacy Policy</a><a class="text-base text-black" href="/gb/legal/tos">Terms of Service</a><a class="text-base text-black" href="/gb/legal/gdpr">GDPR</a>
    </div>
    <div class="flex flex-col gap-8">
      <div class="order-3 flex items-center md:order-[0]">
        <label class="mr-2 shrink-0" for="lang"><img src="https://jobtoday.b-cdn.net/static/icons/ic-profile-languages.svg" alt="languages icon" loading="lazy" width="20" height="20" /></label
        ><select class="select-bordered select select-sm shrink py-1 text-xs" data-testid="footer_language-selector" id="lang" name="lang">
          <option value="en-US" selected="">English (US)</option>
          <option value="en">English (UK)</option>
          <option value="es">Español</option>
          <option value="fr">Français</option>
        </select>
      </div>
      <div>
        <p class="footer-title text-jt-gray-400 opacity-100">Follow us</p>
        <div class="grid grid-cols-2 gap-4 md:grid-cols-4">
          <a href="https://www.facebook.com/jobtodayUK/" target="_blank" rel="noopener noreferrer" aria-label="Facebook account" title="JOB TODAY Facebook" data-testid="footer_fb-button"><img src="https://jobtoday.b-cdn.net/static/icons/ic-fb-footer.svg" alt="JOB TODAY Facebook" width="40" height="40" /></a><a href="https://twitter.com/jobtoday_uk/" target="_blank" rel="noopener noreferrer" aria-label="Twitter account" title="JOB TODAY Twitter" data-testid="footer_twitter-button"><img src="https://jobtoday.b-cdn.net/static/icons/ic-twitter-footer.svg" alt="JOB TODAY Twitter" width="40" height="40" /></a><a href="https://www.instagram.com/jobtoday_uk/" target="_blank" rel="noopener noreferrer" aria-label="Instagram account" title="JOB TODAY Instagram" data-testid="footer_instagram-button"><img src="https://jobtoday.b-cdn.net/static/icons/ic-insta-footer.svg" alt="JOB TODAY Instagram" width="40" height="40" /></a><a href="https://www.linkedin.com/company/jobtoday/" target="_blank" rel="noopener noreferrer" aria-label="Linkedin account" title="JOB TODAY LinkedIn" data-testid="footer_linkedin-button"><img src="https://jobtoday.b-cdn.net/static/icons/ic-linkedin-footer.svg" alt="JOB TODAY LinkedIn" width="40" height="40" /></a>
        </div>
      </div>
      <div>
        <p class="footer-title text-jt-gray-400 opacity-100">Download our app</p>
        <div class="grid grid-cols-1 items-center gap-4 md:grid-cols-2">
          <button title="JOB TODAY iOS Application" data-testid="footer_appstore-button" type="button"><img src="https://jobtoday.b-cdn.net/static/images/app-store-badge.svg" alt="appstore badge icon" width="180" height="54" /></button><button title="JOB TODAY Android Application" data-testid="footer_playstore-button" type="button"><img src="https://jobtoday.b-cdn.net/static/images/google-play-badge.svg" alt="google play badge icon" width="180" height="54" /></button>
        </div>
      </div>
    </div>
  </section>
  <section class="footer mx-auto max-w-[1135px] p-4">
    <div>
      <div>
        <a href="https://www.trustpilot.com/review/jobtoday.com" rel="noopener noreferrer" target="_blank"><img class="mb-2 md:-mt-20 md:mb-0" src="https://jobtoday.b-cdn.net/static/images/landings/advertise-for-free/trustpilot-gb.svg" alt="trustpilot rating" width="214" height="76" /></a>
      </div>
      <div class="grid grid-flow-col items-center gap-2"><img src="https://jobtoday.b-cdn.net/static/icons/JT-Logo-XS.svg" alt="JOB TODAY logo" title="JOB TODAY logo" width="18" height="18" />© 2023 JobToday S.A. All Rights Reserved</div>
    </div>
  </section>
</footer>

</template>

<script setup>

</script>

<style   scoped>

.bg-jt-gray-50 {
    --tw-bg-opacity: 1;
    background-color: rgb(251 251 251/var(--tw-bg-opacity));
}

.jt-container, .jt-content {
    margin-left: auto;
    margin-right: auto;
}

.jt-container {
    max-width: 1135px;
    padding: 1rem;
}

.footer, .footer>* {
    display: grid;
    place-items: start;
}
.footer-title {
    margin-bottom: 0.5rem;
    font-weight: 700;
    text-transform: uppercase;
    opacity: .5;
}
</style>