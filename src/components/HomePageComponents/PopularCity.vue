<template>
     <div class="jt-container my-8 w-full max-w-[1135px] mx-auto mt-28">
    <div class="flex flex-col gap-8 md:gap-12">
      <div class="flex flex-col gap-4 md:gap-6">
        <div>
          <div class="flex items-start justify-between gap-8 md:items-center">
            <h1 class="text-xl font-extrabold md:text-2xl">Popular job locations for the UK</h1>
            <a class="text-jt-primary whitespace-nowrap leading-8" href="https://jobtoday.com/gb/hub/locations">More cities</a>
          </div>
          <p>More than 24 cities are available for your job search. Find a job near you</p>
        </div>
        <div>
          <div class="flex flex-col gap-6">
            <div class="grid gap-6 md:grid-cols-4">
              <div class="flex" data-testid="landing_cities-pictures-list">
                <a class="relative text-black" href="https://jobtoday.com/gb/jobs/london"
                  ><div class="relative overflow-hidden rounded-xl shadow-lg transition-shadow duration-300 ease-in-out hover:shadow-xl">
                    <picture
                      ><source type="image/webp" srcset="https://static.jobtoday.com/cities/uk/cities/london@2x.webp" />
                      <img class="w-full" src="https://static.jobtoday.com/cities/uk/cities/london@2x.webp" alt="London" width="670" height="444" loading="lazy"
                    /></picture>
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#00000080]"></div>
                  </div>
                  <span class="absolute bottom-2 left-4 z-10 font-semibold text-white">London</span></a
                >
              </div>
              <div class="flex" data-testid="landing_cities-pictures-list">
                <a class="relative text-black" href="https://jobtoday.com/gb/jobs/manchester"
                  ><div class="relative overflow-hidden rounded-xl shadow-lg transition-shadow duration-300 ease-in-out hover:shadow-xl">
                    <picture
                      ><source type="image/webp" srcset="https://static.jobtoday.com/cities/uk/cities/manchester@2x.webp" />
                      <img class="w-full" src="https://static.jobtoday.com/cities/uk/cities/manchester@2x.webp" alt="Manchester" width="670" height="444" loading="lazy"
                    /></picture>
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#00000080]"></div>
                  </div>
                  <span class="absolute bottom-2 left-4 z-10 font-semibold text-white">Manchester</span></a
                >
              </div>
              <div class="flex" data-testid="landing_cities-pictures-list">
                <a class="relative text-black" href="https://jobtoday.com/gb/jobs/birmingham"
                  ><div class="relative overflow-hidden rounded-xl shadow-lg transition-shadow duration-300 ease-in-out hover:shadow-xl">
                    <picture
                      ><source type="image/webp" srcset="https://static.jobtoday.com/cities/uk/cities/birmingham@2x.webp" />
                      <img class="w-full" src="https://static.jobtoday.com/cities/uk/cities/birmingham@2x.webp" alt="Birmingham" width="670" height="444" loading="lazy"
                    /></picture>
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#00000080]"></div>
                  </div>
                  <span class="absolute bottom-2 left-4 z-10 font-semibold text-white">Birmingham</span></a
                >
              </div>
              <div class="flex" data-testid="landing_cities-pictures-list">
                <a class="relative text-black" href="https://jobtoday.com/gb/jobs/bristol"
                  ><div class="relative overflow-hidden rounded-xl shadow-lg transition-shadow duration-300 ease-in-out hover:shadow-xl">
                    <picture
                      ><source type="image/webp" srcset="https://static.jobtoday.com/cities/uk/cities/bristol@2x.webp" />
                      <img class="w-full" src="https://static.jobtoday.com/cities/uk/cities/bristol@2x.webp" alt="Bristol" width="670" height="444" loading="lazy"
                    /></picture>
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#00000080]"></div>
                  </div>
                  <span class="absolute bottom-2 left-4 z-10 font-semibold text-white">Bristol</span></a
                >
              </div>
              <div class="flex" data-testid="landing_cities-pictures-list">
                <a class="relative text-black" href="https://jobtoday.com/gb/jobs/watford"
                  ><div class="relative overflow-hidden rounded-xl shadow-lg transition-shadow duration-300 ease-in-out hover:shadow-xl">
                    <picture
                      ><source type="image/webp" srcset="https://static.jobtoday.com/cities/uk/cities/watford@2x.webp" />
                      <img class="w-full" src="https://static.jobtoday.com/cities/uk/cities/watford@2x.webp" alt="Watford" width="670" height="444" loading="lazy"
                    /></picture>
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#00000080]"></div>
                  </div>
                  <span class="absolute bottom-2 left-4 z-10 font-semibold text-white">Watford</span></a
                >
              </div>
              <div class="flex" data-testid="landing_cities-pictures-list">
                <a class="relative text-black" href="https://jobtoday.com/gb/jobs/brighton"
                  ><div class="relative overflow-hidden rounded-xl shadow-lg transition-shadow duration-300 ease-in-out hover:shadow-xl">
                    <picture
                      ><source type="image/webp" srcset="https://static.jobtoday.com/cities/uk/cities/brighton@2x.webp" />
                      <img class="w-full" src="https://static.jobtoday.com/cities/uk/cities/brighton@2x.webp" alt="Brighton" width="670" height="444" loading="lazy"
                    /></picture>
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#00000080]"></div>
                  </div>
                  <span class="absolute bottom-2 left-4 z-10 font-semibold text-white">Brighton</span></a
                >
              </div>
              <div class="flex" data-testid="landing_cities-pictures-list">
                <a class="relative text-black" href="https://jobtoday.com/gb/jobs/edinburgh"
                  ><div class="relative overflow-hidden rounded-xl shadow-lg transition-shadow duration-300 ease-in-out hover:shadow-xl">
                    <picture
                      ><source type="image/webp" srcset="https://static.jobtoday.com/cities/uk/cities/edinburgh@2x.webp" />
                      <img class="w-full" src="https://static.jobtoday.com/cities/uk/cities/edinburgh@2x.webp" alt="Edinburgh" width="670" height="444" loading="lazy"
                    /></picture>
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#00000080]"></div>
                  </div>
                  <span class="absolute bottom-2 left-4 z-10 font-semibold text-white">Edinburgh</span></a
                >
              </div>
              <div class="flex" data-testid="landing_cities-pictures-list">
                <a class="relative text-black" href="https://jobtoday.com/gb/jobs/glasgow"
                  ><div class="relative overflow-hidden rounded-xl shadow-lg transition-shadow duration-300 ease-in-out hover:shadow-xl">
                    <picture
                      ><source type="image/webp" srcset="https://static.jobtoday.com/cities/uk/cities/glasgow@2x.webp" />
                      <img class="w-full" src="https://static.jobtoday.com/cities/uk/cities/glasgow@2x.webp" alt="Glasgow" width="670" height="444" loading="lazy"
                    /></picture>
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#00000080]"></div>
                  </div>
                  <span class="absolute bottom-2 left-4 z-10 font-semibold text-white">Glasgow</span></a
                >
              </div>
            </div>
            <div class="grid grid-cols-2 gap-6 md:grid-cols-4">
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/leeds">Leeds</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/liverpool">Liverpool</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/reading">Reading</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/nottingham">Nottingham</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/sheffield">Sheffield</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/cardiff">Cardiff</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/chelmsford">Chelmsford</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/dartford">Dartford</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/luton">Luton</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/coventry">Coventry</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/peterborough">Peterborough</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/exeter">Exeter</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/wolverhampton">Wolverhampton</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/bath">Bath</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/milton-keynes">Milton keynes</a></div>
              <div class="flex" data-testid="landing_cities-list"><a class="relative line-clamp-1 text-black" href="https://jobtoday.com/gb/jobs/stoke-on-trent">Stoke-on-trent</a></div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-col gap-4 md:gap-6">
        <div>
          <div class="flex items-start justify-between gap-8 md:items-center"><h1 class="text-xl font-extrabold md:text-2xl">Jobs by categories in the UK</h1></div>
        </div>
        <div>
          <ul class="scrollbar-none flex snap-x snap-proximity gap-2 overflow-x-auto md:flex-wrap md:overflow-visible md:pb-0">
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-chef-and-cook" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-chef_cook-32.png" alt="Chef &amp; Cook icon" loading="lazy" width="20" height="20" />
                <!-- -->Chef &amp; Cook</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-waiters" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-waiters-32.png" alt="Waiters icon" loading="lazy" width="20" height="20" />
                <!-- -->Waiters</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-bar-staff" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-bar_staff-32.png" alt="Bar Staff icon" loading="lazy" width="20" height="20" />
                <!-- -->Bar Staff</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-retail" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-retail-32.png" alt="Retail icon" loading="lazy" width="20" height="20" />
                <!-- -->Retail</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-kitchen-porter" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-kitchen_assistants-32.png" alt="Kitchen Porter icon" loading="lazy" width="20" height="20" />
                <!-- -->Kitchen Porter</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-barista" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-barista-32.png" alt="Barista icon" loading="lazy" width="20" height="20" />
                <!-- -->Barista</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-accounting-and-finance" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-accounting_finance-32.png" alt="Accounting &amp; Finance icon" loading="lazy" width="20" height="20" />
                <!-- -->Accounting &amp; Finance</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-animal-care" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-animal_care-32.png" alt="Animal Care icon" loading="lazy" width="20" height="20" />
                <!-- -->Animal Care</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-art-media-design" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-visual_media-32.png" alt="Art, Media, Design icon" loading="lazy" width="20" height="20" />
                <!-- -->Art, Media, Design</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-child-care" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-child_youth_care-32.png" alt="Child Care icon" loading="lazy" width="20" height="20" />
                <!-- -->Child Care</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-cleaning" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-cleaner-32.png" alt="Cleaning icon" loading="lazy" width="20" height="20" />
                <!-- -->Cleaning</a
              >
            </li>
            <li class="flex flex flex-shrink-0 snap-start">
              <a href="https://jobtoday.com/gb/jobs-construction-and-trades" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-construction_repair-32.png" alt="Construction &amp; Trades icon" loading="lazy" width="20" height="20" />
                <!-- -->Construction &amp; Trades</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-customer-service" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-customer_service-32.png" alt="Customer Service icon" loading="lazy" width="20" height="20" />
                <!-- -->Customer Service</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-driver-and-delivery" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-driver_delivery-32.png" alt="Driver &amp; Delivery icon" loading="lazy" width="20" height="20" />
                <!-- -->Driver &amp; Delivery</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-education" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-education_training-32.png" alt="Education icon" loading="lazy" width="20" height="20" />
                <!-- -->Education</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-engineering" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-engineer-32.png" alt="Engineering icon" loading="lazy" width="20" height="20" />
                <!-- -->Engineering</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-entertainment" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-arts_entertainment-32.png" alt="Entertainment icon" loading="lazy" width="20" height="20" />
                <!-- -->Entertainment</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-events-and-promotion" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-events_promotion-32.png" alt="Events &amp; Promotion icon" loading="lazy" width="20" height="20" />
                <!-- -->Events &amp; Promotion</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-healthcare" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-healthcare-32.png" alt="Healthcare icon" loading="lazy" width="20" height="20" />
                <!-- -->Healthcare</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-host-and-hostess" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-host_hostess-32.png" alt="Host &amp; Hostess icon" loading="lazy" width="20" height="20" />
                <!-- -->Host &amp; Hostess</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-information-technology" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-information_technology-32.png" alt="Information Technology icon" loading="lazy" width="20" height="20" />
                <!-- -->Information Technology</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-legal" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-legal-32.png" alt="Legal icon" loading="lazy" width="20" height="20" />
                <!-- -->Legal</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-management" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-business_management-32.png" alt="Management icon" loading="lazy" width="20" height="20" />
                <!-- -->Management</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-manufacturing" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-production_manufacturing-32.png" alt="Manufacturing icon" loading="lazy" width="20" height="20" />
                <!-- -->Manufacturing</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-office-and-admin" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-admin_secretarial-32.png" alt="Office &amp; Admin icon" loading="lazy" width="20" height="20" />
                <!-- -->Office &amp; Admin</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-online-jobs" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-odd_jobs-32.png" alt="Online Jobs icon" loading="lazy" width="20" height="20" />
                <!-- -->Online Jobs</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-sales-and-marketing" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-sales_marketing-32.png" alt="Sales &amp; Marketing icon" loading="lazy" width="20" height="20" />
                <!-- -->Sales &amp; Marketing</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-salon-and-beauty" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-salon_beauty-32.png" alt="Salon &amp; Beauty icon" loading="lazy" width="20" height="20" />
                <!-- -->Salon &amp; Beauty</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-science" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-science-32.png" alt="Science icon" loading="lazy" width="20" height="20" />
                <!-- -->Science</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-security" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-security-32.png" alt="Security icon" loading="lazy" width="20" height="20" />
                <!-- -->Security</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start md:hidden">
              <a href="https://jobtoday.com/gb/jobs-sports-and-wellness" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-sports_wellness-32.png" alt="Sports &amp; Wellness icon" loading="lazy" width="20" height="20" />
                <!-- -->Sports &amp; Wellness</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-warehouse" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-warehouse-32.png" alt="Warehouse icon" loading="lazy" width="20" height="20" />
                <!-- -->Warehouse</a
              >
            </li>
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-writing-and-editing" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-editor_writer-32.png" alt="Writing &amp; Editing icon" loading="lazy" width="20" height="20" />
                <!-- -->Writing &amp; Editing</a
              >
            </li>
           
            <li class="flex flex-shrink-0 snap-start " :class="tags ? 'block' : 'hidden'">
              <a href="https://jobtoday.com/gb/jobs-other" class="md:hover:border-jt-primary md:hover:bg-jt-primary-light md:hover:text-jt-primary flex shrink-0 items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 text-black transition duration-200 ease-in-out md:hover:shadow-sm"
                ><img src="https://cdn.jobtoday.com/categories/32x32/ic-emj-other-32.png" alt="Other icon" loading="lazy" width="20" height="20" />
                <!-- -->Other</a
              >
            </li>
            <li class="hidden md:block" data-type="more" @click="showTags">
              <button type="button" class="hover:border-jt-primary hover:bg-jt-primary-light hover:text-jt-primary flex shrink-0 cursor-pointer items-center gap-2 whitespace-nowrap rounded-lg border border-gray-200 bg-gray-100 px-3 py-2 font-semibold text-black transition duration-200 ease-in-out hover:shadow-sm">{{tags ? 'Less' : 'More'}}
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-4 h-4">
  <path stroke-linecap="round" stroke-linejoin="round" :d="tags ?  'M4.5 15.75l7.5-7.5 7.5 7.5' : ' M19.5 8.25l-7.5 7.5-7.5-7.5'" /></svg></button>
  

            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>

import {ref} from 'vue';


const tags = ref(false);

const showTags = () => {
  tags.value= !tags.value;
}

 

</script>

<style lang="scss" scoped>

</style>