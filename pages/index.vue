<template>
  <div class="bg-[#0e0f0f] text-gray-300 h-full">
    <!-- Nav bar -->
    <nav class="p-4 rounded-md flex items-center justify-between px-[80px]">
      <!-- logo -->
      <div class="">
        <span class="hover:text-gray-400 text-2xl">
          Adebi<small class="text-2xl text-yellow-400">mpe</small></span>
      </div>

      <!-- nav links -->
      <div>
        <ul class="flex items-center gap-5">
          <li>
            <a class="hover:text-gray-400 text-lg hover:text-yellow-400 hover:underline" href="#about">About</a>
          </li>
          <li>
            <a class="hover:text-gray-400 text-lg hover:text-yellow-400 hover:underline" href="#works">Works</a>
          </li>
          <li>
            <a class="hover:text-gray-400 text-lg hover:text-yellow-400 hover:underline"
              href="#testimonials">Testimonials</a>
          </li>
          <li>
            <a class="hover:text-gray-400 text-lg hover:text-yellow-400 hover:underline" href="#contact-me">Contact
              Me</a>
          </li>
        </ul>
      </div>
    </nav>
    <hr />
    <!-- Main content -->
    <main class="mt-20 max-w-[1200px] mx-auto bg-[#0e0f0f]">
      <!-- hero section -->
      <div class="flex items-center justify-between h-full">
        <!-- Left side contents -->
        <div class="flex flex-col justify-center h-[400px] w-[600px] space-y-5">
          <h1 class="text-6xl">From Concept to Flawless Digital Experience</h1>
          <p class="text-lg text-gray-400">
            Transforming your websites and apps into their ideal form through meticulous quality assurance and
            thoughtful testing, I bring websites and apps to their optimal state turning your vision into a polished,
            high-performing reality.
          </p>

          <!-- button and social link  -->
          <div>
            <button type="button"
              class="border rounded-full py-3 px-5 hover:bg-shadow-xl text-lg text-gray-300 hover:bg-gray-300 hover:text-black">
              View Portfolio
            </button>
          </div>
        </div>

        <!-- Right side contents -->
        <div class="">
          <!-- profile picture -->
          <div class="w-[400px] shadow-xl">
            <img src="~/assets/images/profile-image.jpg"
              class="object-center object-cover w-full mx-auto h-[500px] shadow-2xl rounded-[500px]"
              alt="adebimpe profile picture" />
          </div>
        </div>
      </div>
    </main>

    <!-- Services -->
    <div class="services mt-20 bg-[#101111] w-full" id="services">
      <div class="max-w-[1200px] mx-auto">
        <div class="py-16 rounded-lg">
          <h2 class="text-5xl font-400px text-[#bbbaa6]">Services</h2>
        </div>
        <div>
          <div class="space-y-4">
            <div class="grid-cols-12 grid gap-4">
              <!-- Service Card 1 -->
              <div
                class="relative bg-[#1a1a1a] p-8 hover:border rounded-[20px] transition-all duration-300 hover:-translate-y-1 border-opacity-10 border-gray-500 col-span-7 group">
                <div
                  class="inline-block bg-[#252525] text-sm py-1 rounded-[10px] border mb-5 group-hover:bg-white group-hover:text-black w-[35px] text-center">
                  01
                </div>
                <svg class="absolute top-8 right-8 w-5 h-5 opacity-60" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                  stroke-linejoin="round">
                  <line x1="7" y1="17" x2="17" y2="7"></line>
                  <polyline points="7 7 17 7 17 17"></polyline>
                </svg>
                <h3 class="text-4xl font-semibold text-[#fefce1] mb-3">
                  Functional Testing
                </h3>
                <p class="text-[#bbbaa6b3]">
                  Comprehensive verification of all system functions against
                  requirements to ensure your software works as intended.
                </p>
              </div>

              <!-- Service Card 2 -->
              <div
                class="relative bg-[#1a1a1a] p-8 hover:border rounded-[20px] transition-all duration-300 hover:-translate-y-1 border-opacity-10 border-gray-500 col-span-5 group">
                <div
                  class="inline-block bg-[#252525] text-sm py-1 mb-5 group-hover:bg-white group-hover:text-black w-[35px] border rounded-[10px] text-center">
                  02
                </div>
                <svg class="absolute top-8 right-8 w-5 h-5 opacity-60" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                  stroke-linejoin="round">
                  <line x1="7" y1="17" x2="17" y2="7"></line>
                  <polyline points="7 7 17 7 17 17"></polyline>
                </svg>
                <h3 class="text-4xl font-semibold text-[#fefce1] mb-3">
                  Automated Testing
                </h3>
                <p class="text-[#bbbaa6b3]">
                  Implementation of robust test automation frameworks to
                  increase coverage, improve efficiency and reduce regression
                  testing time.
                </p>
              </div>
            </div>

            <div class="grid-cols-12 grid gap-4">
              <!-- Service Card 3 -->
              <div
                class="relative bg-[#1a1a1a] p-8 rounded transition-all duration-300 hover:-translate-y-1 hover:border rounded-[20px] border-opacity-10 border-gray-500 col-span-5 group">
                <div
                  class="inline-block bg-[#252525] text-sm py-1 mb-5 group-hover:bg-white group-hover:text-black w-[35px] border rounded-[10px] text-center">
                  03
                </div>
                <svg class="absolute top-8 right-8 w-5 h-5 opacity-60" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                  stroke-linejoin="round">
                  <line x1="7" y1="17" x2="17" y2="7"></line>
                  <polyline points="7 7 17 7 17 17"></polyline>
                </svg>
                <h3 class="text-4xl font-semibold text-[#fefce1] mb-3">
                  Performance Testing
                </h3>
                <p class="text-[#bbbaa6b3]">
                  Detailed analysis of system speed, stability and scalability
                  under various load conditions to ensure optimal user
                  experience.
                </p>
              </div>

              <!-- Service Card 4 -->
              <div
                class="relative bg-[#1a1a1a] p-8 rounded transition-all duration-300 hover:-translate-y-1 hover:border rounded-[20px] border-opacity-10 border-gray-500 col-span-7 group">
                <div
                  class="inline-block bg-[#252525] text-sm py-1 mb-5 group-hover:bg-white group-hover:text-black w-[35px] border rounded-[10px] text-center">
                  04
                </div>
                <svg class="absolute top-8 right-8 w-5 h-5 opacity-60" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                  stroke-linejoin="round">
                  <line x1="7" y1="17" x2="17" y2="7"></line>
                  <polyline points="7 7 17 7 17 17"></polyline>
                </svg>
                <h3 class="text-4xl font-semibold text-[#fefce1] mb-3">
                  Security Testing
                </h3>
                <p class="text-[#bbbaa6b3]">
                  Thorough assessment of application vulnerabilities and
                  protection mechanisms to safeguard your data and user
                  information.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Works -->
    <div class="works bg-[#0e0f0f] w-full" id="works">
      <div class="max-w-[1200px] mx-auto py-16 flex items-center justify-between">
        <!-- works text -->
        <div class="">
          <h2 class="text-5xl font-400px text-[#bbbaa6]">Works</h2>
        </div>

        <!-- button links -->
        <div>
          <ul class="flex items-center gap-5">
            <li>
              <button @click.prevent="toggleWorks('all')" type="button"
                class="border rounded-full py-3 px-5 text-lg text-[#bbbaa6] border-[#bbbaa6]" :class="{
                  'bg-white text-black hover:text-black': activeTab === 'all',
                }">
                All
              </button>
            </li>
            <li>
              <button type="button" @click.prevent="toggleWorks('web-application-testing')"
                class="border rounded-full py-3 px-5 text-lg text-[#bbbaa6] border-[#bbbaa6]" :class="{
                  'bg-white text-black hover:text-black':
                    activeTab === 'web-application-testing',
                }">
                Web Application
              </button>
            </li>
            <li>
              <button type="button" @click.prevent="toggleWorks('mobile-application-testing')"
                class="border rounded-full py-3 px-5 text-lg text-[#bbbaa6] border-[#bbbaa6]" :class="{
                  'bg-white text-black hover:text-black':
                    activeTab === 'mobile-application-testing',
                }">
                Mobile Application
              </button>
            </li>
            <!-- <li>
              <a
                type="#Wordpress-Webisite"
                class="border rounded-full py-3 px-5  text-lg text-[#bbbaa6] border-[#bbbaa6]"
              >
                Wordpress Website
              </a>
            </li> -->
            <li>
              <button type="button" @click.prevent="toggleWorks('others')"
                class="border rounded-full py-3 px-5 text-lg text-[#bbbaa6] border-[#bbbaa6]" :class="{
                  'bg-white text-black hover:text-black':
                    activeTab === 'others',
                }">
                Others
              </button>
            </li>
          </ul>
        </div>
      </div>
      <!-- Work Images -->
      <div class="work-img bg-[#0e0f0f] w-full">
        <div class="max-w-[1200px] mx-auto">
          <div>
            <div class="space-y-4" v-show="activeTab === 'all' || activeTab === 'web-application-testing'
              ">
              <div class="grid-cols-12 grid gap-4">
                <!-- Beezlinq -->
                <div
                  class="relative bg-[#1a1a1a] p-8 hover:border rounded-[20px] transition-all duration-300 hover:-translate-y-1 border-opacity-10 border-gray-500 col-span-6 group">
                  <a href="https://beezlinq.com/" target="_blank" class="block">
                    <div class="overflow-hidden rounded-[25px]">
                      <img src="~/assets/images/beezlinqq.jpg" alt="beezlinq"
                        class="w-full rounded-[25px] mt-4 transition-transform duration-300 group-hover:scale-110" />
                    </div>
                    <h3 class="text-4xl font-semibold text-[#fefce1] mt-3 mb-3">
                      Beezlinq
                    </h3>
                    <p class="text-[#bbbaa6b3]">
                      Comprehensive verification of all system functions against
                      requirements to ensure your software works as intended.
                    </p>
                  </a>
                </div>

                <!-- RealtimePay -->
                <div
                  class="relative bg-[#1a1a1a] p-8 hover:border rounded-[20px] transition-all duration-300 hover:-translate-y-1 border-opacity-10 border-gray-500 col-span-6 group">
                  <a href="https://realtimepay.ng/" target="_blank" class="block">
                    <div class="overflow-hidden rounded-[25px]">
                      <img src="~/assets/images/RealtimePay.jpg" alt="beezlinq"
                        class="w-full rounded-[25px] mt-4 transition-transform duration-300 group-hover:scale-110" />
                    </div>
                    <h3 class="text-4xl font-semibold text-[#fefce1] mt-3 mb-3">
                      Beezlinq
                    </h3>
                    <p class="text-[#bbbaa6b3]">
                      Comprehensive verification of all system functions against
                      requirements to ensure your software works as intended.
                    </p>
                  </a>
                </div>
              </div>

              <div class="grid-cols-12 grid gap-4">
                <!-- Utilify -->
                <div
                  class="relative bg-[#1a1a1a] p-8 hover:border rounded-[20px] transition-all duration-300 hover:-translate-y-1 border-opacity-10 border-gray-500 col-span-6 group">
                  <a href="https://utilify.ng/" target="_blank" class="block">
                    <div class="overflow-hidden rounded-[25px]">
                      <img src="~/assets/images/Utilify.jpg" alt="utilify"
                        class="w-full rounded-[25px] mt-4 transition-transform duration-300 group-hover:scale-110" />
                    </div>
                    <h3 class="text-4xl font-semibold text-[#fefce1] mt-3 mb-3">
                      Utilify
                    </h3>
                    <p class="text-[#bbbaa6b3]">
                      Comprehensive verification of all system functions against
                      requirements to ensure your software works as intended.
                    </p>
                  </a>
                </div>

                <!-- Vixbay Tech -->
                <div
                  class="relative bg-[#1a1a1a] p-8 hover:border rounded-[20px] transition-all duration-300 hover:-translate-y-1 border-opacity-10 border-gray-500 col-span-6 group">
                  <a href="https://vixbaytech.com/" target="_blank" class="block">
                    <div class="overflow-hidden rounded-[25px]">
                      <img src="~/assets/images/Vixbayy.jpg" alt="vixbay-tech"
                        class="w-full rounded-[25px] mt-4 transition-transform duration-300 group-hover:scale-110" />
                    </div>
                    <h3 class="text-4xl font-semibold text-[#fefce1] mt-3 mb-3">
                      Vixbay Tech
                    </h3>
                    <p class="text-[#bbbaa6b3]">
                      Comprehensive verification of all system functions against
                      requirements to ensure your software works as intended.
                    </p>
                  </a>
                </div>
              </div>
              <div class="grid-cols-12 grid gap-4">
                <!-- Interviewhq -->
                <div
                  class="relative bg-[#1a1a1a] p-8 hover:border rounded-[20px] transition-all duration-300 hover:-translate-y-1 border-opacity-10 border-gray-500 col-span-6 group">
                  <a href="https://interviewhq.ai/" target="_blank" class="block">
                    <div class="overflow-hidden rounded-[25px]">
                      <img src="~/assets/images/Interviewhq.jpg" alt="interviewhq"
                        class="w-full rounded-[25px] mt-4 transition-transform duration-300 group-hover:scale-110" />
                    </div>
                    <h3 class="text-4xl font-semibold text-[#fefce1] mt-3 mb-3">
                      Interviewhq
                    </h3>
                    <p class="text-[#bbbaa6b3]">
                      Comprehensive verification of all system functions against
                      requirements to ensure your software works as intended.
                    </p>
                  </a>
                </div>

                <!-- Service Card 4 -->
                <!-- <div
                  class="relative bg-[#1a1a1a] p-8 hover:border rounded-[20px] transition-all duration-300 hover:-translate-y-1 border-opacity-10 border-gray-500 col-span-6 group"
                >
                  <div class="overflow-hidden rounded-[25px]">
                    <img
                      src="~/assets/images/Vixbayy.jpg"
                      alt="beezlinq"
                      class="w-full rounded-[25px] mt-4 transition-transform duration-300 group-hover:scale-110"
                    />
                  </div>
                  <h3 class="text-4xl font-semibold text-[#fefce1] mt-3 mb-3">
                    Beezlinq
                  </h3>
                  <p class="text-[#bbbaa6b3]">
                    Comprehensive verification of all system functions against
                    requirements to ensure your software works as intended.
                  </p>
                </div> -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- About Me -->
    <div class="about-me mt-20 bg-[#101111] w-full " id="about">
      <div class="max-w-[1200px] mx-auto">
        <div class="py-16 rounded-lg">
          <h2 class="text-5xl font-400px text-[#bbbaa6]">About Me</h2>
        </div>
        <div class="grid-cols-12 grid gap-4">
          <!-- About Image -->
          <div class="relative bg-[#1a1a1a] p-8 rounded-[20px] col-span-5 group">
            <div class="w-[200px] h-[300px] rounded-full mx-auto mx-auto">
              <img src="~assets/images/backup-img1.jpeg" class="object-center rounded-full mx-auto" alt="" />
            </div>
          </div>

          <!-- About Text -->
          <div class="relative bg-[#1a1a1a] p-8 rounded-[20px] col-span-7 group">
            <div>
              <h3 class="text-4xl font-semibold text-[#bbbaa6] mt-5 mb-3">
                Hi, I'm Adebimpe Adeniyi
              </h3>
            </div>

            <div>
              <p class="text-[#bbbaa6b3] mt-7">
                I’m a highly motivated and detail-oriented QA Analyst with experience in software testing with a track
                record of
                identifying and resolving critical bugs, collaborating effectively with developers, and ensuring
                high-quality product releases, having experienced offering outstanding support to users of various
                levels.
              </p>
            </div>
            <div>
              <p class="text-[#bbbaa6b3] mt-5">
                With exceptional skills and knowledge in Administration and management, use of systems and average
                programming skills, I aim to always profer solutions and deliver customer satisfaction through the use
                of research data, observation of trends and feedbacks by successfully identifying and deploy solutions
                for clients as well as being a good team player.
              </p>
              <p class="text-[#bbbaa6b3] mt-5">
                My role involves thorough testing and analysis of software products to identify potential issues and
                guarantee optimal performance. With a keen eye for detail and a commitment to delivering reliable
                solutions, I work closely with the development team to implement best practices and achieve seamless
                functionality ensuring that our software solutions meet both user needs and business objectives.
              </p>
            </div>
          </div>
        </div>

        <div class="grid-cols-12 grid gap-4 mt-5">
          <!-- Experience -->
          <div class="relative bg-[#1a1a1a] p-8 rounded-[20px]  col-span-6 group">
            <div>
              <h3 class="text-4xl font-semibold text-[#fefce1] mb-3">
                Experience
              </h3>
              <div class="text-[#bbbaa6b3] mt-7">
                <!-- experience 1 -->
                <div class="dtr-timeline__content"
                  bis_size='{"x":1045,"y":3835,"w":331,"h":61,"abs_x":1045,"abs_y":3890}'>
                  <p class="dtr-timeline__heading"
                    bis_size='{"x":1045,"y":3835,"w":331,"h":28,"abs_x":1045,"abs_y":3890}'>
                    Administrator
                    <span class="dtr-timeline__heading-subtext"
                      bis_size='{"x":1178,"y":3838,"w":197,"h":21,"abs_x":1178,"abs_y":3893}'>
                      @Vixbay Tech Ilorin, Nigeria</span>
                  </p>
                  <div class="dtr-timeline__text"
                    bis_size='{"x":1045,"y":3869,"w":102,"h":27,"abs_x":1045,"abs_y":3924}'>
                    2021 - 2023
                  </div>
                </div>
                <!-- experience 2 -->
                <div class="dtr-timeline__content"
                  bis_size='{"x":1045,"y":3835,"w":331,"h":61,"abs_x":1045,"abs_y":3890}'>
                  <p class="dtr-timeline__heading"
                    bis_size='{"x":1045,"y":3835,"w":331,"h":28,"abs_x":1045,"abs_y":3890}'>
                    Web Development Intern
                    <span class="dtr-timeline__heading-subtext"
                      bis_size='{"x":1178,"y":3838,"w":197,"h":21,"abs_x":1178,"abs_y":3893}'>
                      @Bex-IT Digital Solutions Abuja, Nigeria</span>
                  </p>
                  <div class="dtr-timeline__text"
                    bis_size='{"x":1045,"y":3869,"w":102,"h":27,"abs_x":1045,"abs_y":3924}'>
                    2023 - 2024
                  </div>
                </div>
                <!-- experience 3 -->
                <div class="dtr-timeline__content"
                  bis_size='{"x":1045,"y":3835,"w":331,"h":61,"abs_x":1045,"abs_y":3890}'>
                  <p class="dtr-timeline__heading"
                    bis_size='{"x":1045,"y":3835,"w":331,"h":28,"abs_x":1045,"abs_y":3890}'>
                    Quality Assurance Analyst
                    <span class="dtr-timeline__heading-subtext"
                      bis_size='{"x":1178,"y":3838,"w":197,"h":21,"abs_x":1178,"abs_y":3893}'>
                      @Bex-IT Digital Solutions Abuja, Nigeria</span>
                  </p>
                  <div class="dtr-timeline__text"
                    bis_size='{"x":1045,"y":3869,"w":102,"h":27,"abs_x":1045,"abs_y":3924}'>
                    2024 - present
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Education -->
          <div class="relative bg-[#1a1a1a] p-8 rounded-[20px]  col-span-6 group">
            <h3 class="text-4xl font-semibold text-[#fefce1] mb-3">
              Education
            </h3>
            <div class="text-[#bbbaa6b3] mt-7">
              <div class="dtr-timeline__content"
                bis_size='{"x":1045,"y":3835,"w":331,"h":61,"abs_x":1045,"abs_y":3890}'>
                <p class="dtr-timeline__heading"
                  bis_size='{"x":1045,"y":3835,"w":331,"h":28,"abs_x":1045,"abs_y":3890}'>
                  B.Sc in Library and Information Science
                  <span class="dtr-timeline__heading-subtext"
                    bis_size='{"x":1178,"y":3838,"w":197,"h":21,"abs_x":1178,"abs_y":3893}'>
                    @University Of Ilorin, Nigeria</span>
                </p>
                <div class="dtr-timeline__text" bis_size='{"x":1045,"y":3869,"w":102,"h":27,"abs_x":1045,"abs_y":3924}'>
                  2018 - 2022
                </div>
              </div>
            </div>
          </div>
        </div class="max-w-[1200px] mx-auto">
      </div>
      <!-- skills -->
      <div class=" max-w-[1200px] mx-auto">
        <div class="skills mt-5 bg-[#101111] max-w-[800px] mx-auto">
          <div class="relative bg-[#1a1a1a] p-8 rounded-[20px] h-[300px]">
            <div class="w-[500px] ">
              <h3 class="text-4xl font-semibold text-[#bbbaa6] mt-5 mb-3">
                Skills
              </h3>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Testimonials -->

    <!-- Contact Me -->

    <div class="bg-[#101111] w-full">
      <div class="max-w-[1200px] mx-auto">
        <div class="grid-cols-12 grid gap-4 mt-10">
          <!-- contact -->
          <div class="relative bg-[#1a1a1a] p-8 col-span-6 group">
            <div>
              <h3 class="text-4xl font-semibold text-[#fefce1] mb-3">
                It's time to talk about your project.
              </h3>
              <div class="text-[#bbbaa6b3] mt-7">
                <div class="dtr-timeline__content"
                  bis_size='{"x":1045,"y":3835,"w":331,"h":61,"abs_x":1045,"abs_y":3890}'>
                  <p class="dtr-timeline__heading"
                    bis_size='{"x":1045,"y":3835,"w":331,"h":28,"abs_x":1045,"abs_y":3890}'>
                    Let’s embark on quality journey together making your product stand out in the crowded digital
                    marketplace by ensuring it performs flawlessly for every user
                  </p>

                </div>
              </div>
            </div>
            <div class="space-y-8 mt-5">
              <div class="flex items-center gap-5">
                <div class="w-[40px] h-[40px] rounded-md bg-[#252525] flex items-center justify-center">
                  <SvgPhone class="fill-gray-400" />
                </div>
                <div class="space-y-2">
                  <span class="text-gray-400 text-sm">Phone</span>
                  <h4 class="">+234 9157836424
                  </h4>
                </div>
              </div>

              <div class="flex items-center gap-5">
                <div class="w-[40px] h-[40px] rounded-md bg-[#252525] flex items-center justify-center">
                  <SvgAddress class="fill-white w-6 h-6" />
                </div>
                <div class="space-y-2">
                  <span class="text-gray-400 text-sm">Address</span>
                  <p class="">Katampe Road Abuja, Nigeria
                  </p>
                </div>
                <p></p>
              </div>

              <div class="flex items-center gap-5">
                <div class="w-[40px] h-[40px] rounded-md bg-[#252525] flex items-center justify-center">
                  <SvgMail class="text-white w-6 h-6" />
                </div>
                <div class="space-y-2">
                  <span class="text-gray-400 text-sm">Email address</span>
                  <p>
                    <a href="mailto:adeniyiadebimpe31@gmail.com" target="_blank">
                      adeniyiadebimpe31@gmail.com
                    </a>
                  </p>
                </div>

              </div>

              <div class="flex items-center gap-5">
                <div class="w-[40px] h-[40px] rounded-md bg-[#252525] flex items-center justify-center">
                  <SvgLinkedln class="tect-white w-6 h-6" />
                </div>
                <div class="space-y-2">
                  <span class="text-gray-400 text-sm">Linkedin</span>
                  <p>
                    <a href="http://www.linkedin.com/in/adebimpe-adeniyi-6010b2195" target="_blank">
                      Adebimpe Adeniyi
                    </a>
                  </p>

                </div>
              </div>
            </div>

          </div>

          <!-- contact form -->
          <div class="relative bg-[#1a1a1a] p-8 rounded-[20px]  col-span-6 group">
            <form action="">
              <div>
                <h3 class="text-4xl font-semibold text-[#fefce1] mb-3">
                  Contact Me
                </h3>
                <div class="text-[#bbbaa6b3] mt-7"></div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>





</template>

<script setup>
const activeTab = ref("all");
const tabs = ["all", "web-app-testing", "mobile-app-testing", "others"];

const toggleWorks = (tab) => {
  activeTab.value = tab;
};
</script>

<style scoped>
hr {
  border-color: white;
  opacity: 0.2;
}
</style>
