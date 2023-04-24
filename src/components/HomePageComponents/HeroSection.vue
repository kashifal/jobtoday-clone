<script setup lang="ts">
  import { ref } from "vue";

  const items: any = [
    { text: "Apply in\na single tap" },
    { text: "Chat to the\nbusiness owner" },
    { text: "Stand out with\nyour profile" },
    { text: "Find jobs. Chat\ndirect. Get hired" },
    { text: "Explore thousands\nof local jobs" },
    { text: "Apply in\na single tap" },
    { text: "Chat to the\nbusiness owner" },
    { text: "Stand out with\nyour profile" }
  ];

  const active: any = ref(4);

  setInterval(() => {
    if (active.value === 7) {
      active.value = 0;
    } else {
      active.value =  4;
    }
  }, 1000);
</script>

<template>
  <div class="flex overflow-hidden bg-black md:h-[calc(100vh-80px)] md:max-h-[1000px] md:justify-center md:py-20">
    <div class="relative flex w-full shrink-0 flex-col justify-center md:flex-row md:items-center">
      <div class="shrink-0 p-4 md:ml-2 md:mr-4 xl:ml-8 xl:mr-16"><img src="https://jobtoday.b-cdn.net/static/icons/JT-Logo-XS.svg" alt="JOB TODAY" class="h-[72px] w-[72px] md:h-[60px] md:w-[60px] lg:h-[80px] lg:w-[80px] xl:h-[108px] xl:w-[108px] 2xl:h-[122px] 2xl:w-[122px]" /></div>
      <div class="relative mb-5 flex shrink-0 flex-row whitespace-pre-line px-[8px] text-[40px] font-black leading-9 tracking-[-.03em] text-white md:mb-0 md:h-24 md:w-[320px] md:flex-col md:px-0 md:text-3xl md:text-[34px] md:leading-[34px] lg:h-[120px] lg:w-[440px] lg:text-5xl xl:h-36 xl:w-[560px] xl:text-6xl 2xl:h-44 2xl:w-[640px] 2xl:text-7xl">
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Apply in<br />a single tap</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Chat to the<br />business owner</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Stand out with<br />your profile</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-100 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Find jobs. Chat<br />direct. Get hired</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Explore thousands<br />of local jobs</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Apply in<br />a single tap</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Chat to the<br />business owner</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Stand out with<br />your profile</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Find jobs. Chat<br />direct. Get hired</div>
        <div class="jt-tagline ease-out-sine flex w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-10 transition duration-500 md:h-[90px] md:w-full md:translate-x-[0%] md:translate-y-[-300%] md:items-center md:px-0 lg:h-[120px] xl:h-36 2xl:h-44">Explore thousands<br />of local jobs</div>
      </div>
      <div class="relative flex max-h-[400px] w-full shrink-0 px-[8px] md:mx-10 md:h-full md:max-h-full md:w-60 md:items-center md:px-0 lg:w-[300px] xl:mx-12 xl:w-[360px] 2xl:w-[400px]">
        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-600.webp" />

            <img
              alt="job screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-600.webp" />

            <img
              alt="messenger screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-600.webp" />

            <img
              alt="profile screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-100 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-0 md:px-0 md:opacity-100 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-600.webp" />

            <img
              alt="feed screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-600.png 600w,
    "
              loading="eager"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-600.webp" />

            <img
              alt="categories screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-600.webp" />

            <img
              alt="job screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/job-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-600.webp" />

            <img
              alt="messenger screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/messenger-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-600.webp" />

            <img
              alt="profile screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/profile-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-600.webp" />

            <img
              alt="feed screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/feed-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>

        <div class="jt-image ease-out-sine min-h-[400px] w-[312px] shrink-0 translate-x-[-300%] px-[8px] opacity-30 transition duration-500 md:absolute md:min-h-0 md:w-[240px] md:translate-x-1/2 md:px-0 md:opacity-0 lg:w-[300px] 2xl:w-[400px]">
          <picture>
            <source type="image/webp" media="(min-width: 1537px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-800.webp" />

            <source type="image/webp" media="(max-width: 1280px)" srcset="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-600.webp" />

            <img
              alt="categories screenshot"
              sizes="
      (max-width: 1280px) 600px
      800px
    "
              src="https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-800.png"
              srcset="
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-800.png,
      https://jobtoday.b-cdn.net/static/images/AnimatedTaglinesSection/en-US/categories-600.png 600w,
    "
              loading="lazy"
              width="296"
              height="604"
            />
          </picture>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
