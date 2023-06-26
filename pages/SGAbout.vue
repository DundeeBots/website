<template>
  <div class="font-sans">
    <div class="relative overflow-hidden bg-white">
      <main class="mx-auto max-w-7xl">
        <div class="relative z-10 pb-8 bg-white sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32">
          <svg
            class="absolute inset-y-0 right-0 hidden w-48 h-full text-white transform translate-x-1/2 lg:block"
            fill="currentColor"
            viewBox="0 0 100 100"
            preserveAspectRatio="none"
            aria-hidden="true"
          >
            <polygon points="50,0 100,0 50,100 0,100" />
          </svg>

          <SGHeader />
  
          <!--<div class="relative px-4 pt-6 sm:px-6 lg:px-8">
            <nav
              class="relative flex items-center justify-between sm:h-10 lg:justify-start"
              aria-label="Global"
            >
              <div class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0">
                <div class="flex items-center justify-between w-full md:w-auto">
                  <a href="/">
                    <span class="sr-only">DundeeBots</span>
                    <img class="w-auto h-8 sm:h-20" src="/logo.svg" />
                  </a>
                </div>
              </div>
                
              <div class = "hidden lg:flex lg:min-w-0 lg:flex-1 lg:justify-center lg:gap-x-12">
                <a href ="/SGResources" class="lg:gap-x-12 text-base font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-teal-500">
                  Resources
                </a>
              </div>
            </nav>
          </div> -->
  
          <!--
            Mobile menu, show/hide based on menu open state.
  
            Entering: "duration-150 ease-out"
            From: "opacity-0 scale-95"
            To: "opacity-100 scale-100"
            Leaving: "duration-100 ease-in"
            From: "opacity-100 scale-100"
            To: "opacity-0 scale-95"
          -->
          <div class="px-4 mx-auto mt-10 max-w-7xl sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
            <div class="sm:text-center lg:text-left">
              <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 sm:text-5xl md:text-6xl">
                <span class="block xl:inline"> About </span>
              </h1>
              
              <h2 class="mt-4 text-3xl font-extrabold tracking-tight text-teal-600 sm:text-5xl md:text-6xl">
                Background of the Project
              </h2>

              <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                Kerry Kidd from RaspiKidd the Orchestra conductor making sure all the code and electronics work together in 
                harmony. Has been helping the Maxwell Community Garden explore smart garden technology with the help of Morgan 
                Academy and the Central Library Code club. The project was funded by the Institute of Physics.  
              </p>
              
              <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                We originally thought about integrating smart sensors into some of the existing structures of the garden, but 
                after speaking to some of the garden volunteers we seen that we could create a hydroponics system that people 
                could have at home. This is where the hydroponics in a box was born. 
              </p>

              <h2 class="mt-4 text-3xl font-extrabold tracking-tight text-teal-600 sm:text-5xl md:text-6xl">
                What's Hydroponics?
              </h2>
              
              <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                Hydroponics is a method of growing plants without soil, using nutrient-rich water instead. The plants are grown 
                in a controlled environment, typically indoors or in a greenhouse, and the water is carefully monitored and 
                adjusted to provide the necessary nutrients. This method has become increasingly popular in recent years due to 
                its sustainability and efficiency. Within our system we are still using a substrate to hold the plants.  
              </p>
                
              <!-- <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
                <div class="rounded-md shadow">
                  <a
                    href="/SGResources"
                    class="flex items-center justify-center w-full px-8 py-3 text-base font-medium text-white bg-teal-600 border border-transparent rounded-md hover:bg-teal-700 md:py-4 md:text-lg md:px-10"
                  >
                    Resources
                  </a>
                </div> -->
                <!--<div class="mt-3 sm:mt-0 sm:ml-3">
                  <a
                    href="SmartGarden.vue"
                    class="flex items-center justify-center w-full px-8 py-3 text-base font-medium text-white bg-teal-600 border border-transparent rounded-md hover:bg-teal-700 md:py-4 md:text-lg md:px-10"
                  >
                    Smart Garden
                  </a>
                </div> 
              </div> -->
            </div>
          </div>
        </div>
      </main>

      <!-- Main Image-->
      <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
        <img
          class="object-cover w-full h-56 sm:h-72 md:h-96 lg:w-full lg:h-full"
          src="/HydroponicsPrototype.jpg"
          alt="Hydroponics in a Box Prototype"
        />
      </div>
    </div>
  
    <!--<div class="relative px-4 pt-16 pb-20 sm:px-6 lg:pt-24 lg:pb-28 lg:px-8 bg-gray-50">
      <div class="absolute inset-0">
        <div class="bg-gray-50 h-1/3 sm:h-2/3"></div>
      </div>
      <div class="relative mx-auto max-w-7xl bg-gray-50">
        <div class="text-center">
          <h1 class="text-3xl font-extrabold tracking-tight text-teal-600  md:text-7xl">
            From the blog
          </h1>
        </div>
        <div class="grid max-w-lg gap-5 mx-auto mt-12 lg:grid-cols-3 lg:max-w-none">
          <ArticleCard
            v-for="article in articles"
            :key="article.content.title"
            :title="article.content.title"
            :description="article.content.description"
            :slug="`/${article.slug}`"
            :author="article.content.author"
            :image="article.content.image.filename"
            :date="article.content.date.toLocaleDateString()"
          />
        </div>
      </div>
    </div> -->
    <!-- Newsletter Sign Up -->
    <div class="bg-gray-50">
      <div class="px-4 py-12 mx-auto max-w-7xl sm:px-6 lg:py-16 lg:px-8">
        <div class="px-6 py-6 bg-teal-600 rounded-lg md:py-12 md:px-12 lg:py-16 lg:px-16 xl:flex xl:items-center">
          <div class="xl:w-0 xl:flex-1">
            <h2 class="text-2xl font-extrabold tracking-tight text-white sm:text-3xl">
              Sign up to get updates straight to your inbox
            </h2>
            <p class="max-w-3xl mt-3 text-lg leading-6 text-teal-200">
              Enter your email to be the first to know about the latest updates
            </p>
          </div>
          <div class="mt-8 sm:w-full sm:max-w-md xl:mt-0 xl:ml-8">
            <form class="sm:flex" name="Newsletter" netlify action="https://formspree.io/f/xjvpdgqk" method="POST">
              <label for="emailAddress" class="sr-only">Email address</label>
              <input
                id="emailAddress"
                name="emailAddress"
                type="email"
                autocomplete="email"
                required
                class="w-full px-5 py-3 placeholder-gray-500 border-white rounded-md focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-teal-700 focus:ring-white"
                placeholder="Enter your email"
              />
              <button
                type="submit"
                class="flex items-center justify-center w-full px-5 py-3 mt-3 text-base font-medium text-white bg-teal-500 border border-transparent rounded-md shadow hover:bg-teal-400 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-teal-700 focus:ring-white sm:mt-0 sm:ml-3 sm:w-auto sm:flex-shrink-0"
              >
                Sign up
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
    <SGFooter />
  </div>
</template>
  
  <script lang="ts">
  import Vue from 'vue';
  import SGHeader from '~/components/SGHeader.vue';
  import SGFooter from '~/components/SGFooter.vue';
  
  export default Vue.extend({
    components: {
      SGHeader,
      SGFooter
    }
  })
  </script>