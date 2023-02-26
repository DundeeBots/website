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
            
            <HSTHeader />

            <div class="px-4 mx-auto mt-10 max-w-7xl sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
              <div class="sm:text-center lg:text-left">
                <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 sm:text-5xl md:text-6xl">
                  <span class="block xl:inline">
                    Technology & Engineering 
                  </span>
                  <span class="block text-teal-600 xl:inline">
                    Within the Community
                  </span>
                </h1>
                <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                  A community project helping to get more students engaged in Technology and Engineering. 
                </p>
              </div>
            </div>
          </div>
        </main>

        <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
          <img
            class="object-cover w-full h-56 sm:h-72 md:h-96 lg:w-full lg:h-full"
            src="/HilltownStobswellTech.jpeg"
            alt="Retro Arcade"
          />
        </div>
      </div>
      
      <div class="bg-white">
        <div class="mx-auto max-w-7xl py-12 px-6 lg:py-16 lg:px-8">
            <h2 class="text-center text-3xl font-semibold text-teal-600"> 
                Participating Organisations 
            </h2>
            <div class="mt-6 grid grid-cols-2 gap-0.5 md:grid-cols-3 lg:mt-8">
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                    <img class="max-h-12" src="/ClepingtonPrimary.png" alt="Clepington Primary" />
                    <a href = "http://clepingtonprimary.ea.dundeecity.sch.uk/" target="_blank" class="font-medium px-8" style="color: #088494">
                        Clepington Primary
                    </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/DensPrimary.png" alt="Dens Road Primary" />
                  <a href = "http://densroadprimary.ea.dundeecity.sch.uk/" target="_blank" class="font-medium px-8" style="color: #088494">
                    Dens Road Primary
                  </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/FrancesWrightELC.png" alt="Francis Wright Early Learning Centre" />
                  <a href = "https://twitter.com/FWPSCnursery" target="_blank" class="font-medium px-8" style="color: #088494">
                    Frances Wright Early Learning Centre
                  </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/GlebelandsPrimary.png" alt="Glebelands Primary" />
                  <a href = "http://glebelands.ea.dundeecity.sch.uk/" target="_blank" class="font-medium px-8" style="color: #088494">
                    Glebelands Primary 
                  </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/MorganAcademy.png" alt="Morgan Academy" />
                  <a href = "http://morgan.ea.dundeecity.sch.uk/" target="_blank" class="font-medium px-8" style="color: #088494">
                    Morgan Academy
                  </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/OurLadiesPrimary.png" alt="Our Ladies Primary" />
                  <a href = "http://ourladysprimary.ea.dundeecity.sch.uk/" target="_blank" class="font-medium px-8" style="color: #088494">
                    Our Lady’s RC Primary
                  </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/RosebankPrimary.png" alt="Rosebank Primary" />
                  <a href = "http://rosebank.ea.dundeecity.sch.uk/" target="_blank" class="font-medium px-8" style="color: #088494">
                    Rosebank Primary
                  </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/WallaceTownELC.jpeg" alt="Wallacetown Early Learning Centre" />
                  <a href = "https://blogs.glowscotland.org.uk/dd/CfEemergingpracticeinDundee/2012/04/23/wallacetown-nursery-school/" target="_blank" class="font-medium px-8" style="color: #088494">
                    Wallacetown Early Learning Centre
                  </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/DMS.png" alt="Dundee Makerspace" />
                  <a href = "https://www.dundeemakerspace.com/" target="_blank" class="font-medium px-8" style="color: #088494">
                    Dundee Makerspace
                  </a>
                </div>
                
                <div class="col-span-1 flex justify-center bg-gray-50 py-8 px-8">
                  <img class="max-h-12" src="/MAC.png" alt="Makerspace At Central" />
                  <a href = "https://twitter.com/dundeelibraries" target="_blank" class="font-medium px-8" style="color: #088494">
                    Makerspace at Central Library
                  </a>
                </div>
            </div>
        </div>
      </div>
      
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
      <HSTFooter />
    </div>
  </template>

  <script lang="ts">
    import Vue from 'vue';
    import HSTHeader from "../components/HSTHeader.vue";
    import HSTFooter from '../components/HSTFooter.vue';
  
    export default Vue.extend({
      components: {
        HSTHeader,
        HSTFooter
      }
    })
  </script>