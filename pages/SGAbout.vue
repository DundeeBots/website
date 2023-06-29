<template>
    <div class="relative bg-gray-50">
      <SGHeader />
      <main class="lg:relative">
        <div class="mx-auto max-w-7xl w-full pt-16 pb-20 lg:py-30">
          <div class="px-4 lg:w-1/2 sm:px-8 xl:pr-16">
            <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 sm:text-5xl md:text-6xl text-center">
              <span class="block xl:inline"> About </span> <br>
              <!--<span class="block xl:inline xl:text-5xl"> through physical computing</span> -->
            </h1>
            
            <h2 class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be">
              Contents
            </h2>
            <!-- Page Contents -->
            <ul class = "mt-3 tracking-tight" style="list-style-type: disc;">
              <li> 
                <a href = "#background"> 
                  Background of the Project
                </a> 
              </li>
              <li> 
                <a href = "#hydroponics">
                  What's Hydroponics?
                </a> 
              </li>
              <li> 
                <a href = "#next_steps">
                  What's Next?
                </a> 
              </li>
            </ul>

            <h2 class="text-center">
              <a id = "background" class="mt-4 text-3xl font-extrabold tracking-tight text-teal-600 sm:text-5xl md:text-6xl ">
                Background of the Project
              </a>
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

              <h2 class="text-center">
                <a id = "hydroponics" class="mt-4 text-3xl font-extrabold tracking-tight text-teal-600 sm:text-5xl md:text-6xl text-center">
                  What's Hydroponics?
                </a>
              </h2>
              
              <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                Hydroponics is a method of growing plants without soil, using nutrient-rich water instead. The plants are grown 
                in a controlled environment, typically indoors or in a greenhouse, and the water is carefully monitored and 
                adjusted to provide the necessary nutrients. This method has become increasingly popular in recent years due to 
                its sustainability and efficiency. Within our system we are still using a substrate to hold the plants.  
              </p>

              <h2 class="text-cneter">
                <a id="next_steps" class="mt-4 text-3xl font-extrabold tracking-tight text-teal-600 sm:text-5xl md:text-6xl text-center">
                  Hydropionics in a Box
                </a>
              </h2>
              
              <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                The hydroponics in a box consists of:
                <ul class = "mt-3" style="list-style-type: square">
                  <li class="mt-3">
                    <b> Plastic Box </b> - while the system is not in use it can be packed down and stored in the box.
                  </li>
                  <li class="mt-3">
                    <b> Water Pump </b>  -  I circulate the water and food around the plants.
                  </li>
                  <li class="mt-3">
                    <b> Water Level Sensor </b> - I sense the level of the water and when it gets too low I communicate with the LEDs to turn red and 
                    alert a human that we need more water.
                  </li>
                  <li class="mt-3"> 
                    <b> LED strips </b> - I am stuck to the lid of the box and help the plant grow where there is not enough natural light.
                  </li>
                  <li class="mt-3">
                    <b> Wooden Frame </b> -  I am made up of scrap bits of wood and sit on top of the box to allow the plants to have enough room to grow 
                    between the box and the lights.
                  </li>
                  <li class="mt-3">
                    <b> Seed Tray </b> - I hold the substrate and the plants.
                  </li>
                  <li class="mt-3">
                    <b> Moisture Sensor </b> -  I detect when the substrate is too dry and communicate with the pump that the plants need more water.
                  </li>
                  <li class="mt-3">
                    <b> Raspberry Pi Pico </b> -  I am the brain of the system. I hold all the code to communicate with all the electronics and power the 
                    whole system through my microUSB power cable.
                  </li>
                  <li class="mt-3">
                    <b> A Breadboard </b> - I have wires that run through me and connect all the electronics to the brain.
                  </li>
                </ul>
              </p>

              <h2 class="mt-4 text-3xl font-extrabold tracking-tight text-teal-600 sm:text-5xl md:text-6xl text-center">
                What's Next?
              </h2>
              
              <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                Now that we have got the base of the system up and running there are another few things that we want to do:
                <ul class="mt-3" style="list-style-type: square">
                  <li class="mt-3">
                    <b> Web App </b> - We want to setup a web app so we can monitor the hydroponics system remotely. This will also entitle us to get a 
                    notification stright to our mobile device/dashboard if anything is wrong and the system needs attention.
                  </li>
                  <li class="mt-3">
                    <b> Solar Panel </b> - Allowing the system to be set up anywhere and sustainable without elecrticity.
                  </li>
                  <li class="mt-3"> 
                    <b> PH Sensor </b> - Integrate a PH sensor to measure the PH within the water so we can adjust accordingly.
                  </li>
                </ul>
              </p>

              <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                We would also like to eventually use the system with different substrates, lighting and plants. We will also be thinking of different ways 
                that we could encase the system to make it usable all year round to prolong growing seasons. If/when this happens we will document it right here, so 
                make sure you sign up to our mailing list to find out about future updates.
              </p>
              
            <!--<div class="grid grid-cols-2 grid-rows-2 gap-2 place-items-auto h-30 mt-10 sm:ml-3">
              <div class="rounded-md shadow sm:mt-0 sm:ml-3">
                <NuxtLink to="/microbit" style ="background-color:#76B82A; color:#0E7452; font-weight: bold; font-size: 18px" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-base rounded-md text-black md:py-4 md:text-lg md:px-4">
                  micro:bit
                </NuxtLink>
              </div>
            
              <div class="rounded-md shadow sm:mt-0 sm:ml-3">
                <NuxtLink to="/RaspberryPi" style ="background-color:#76B82A; color:#0E7452; font-weight: bold; font-size: 18px" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-base rounded-md text-black md:py-4 md:text-lg md:px-4">
                  Raspberry Pi
                </NuxtLink> 
              </div>
          
              <div class="rounded-md shadow sm:mt-0 sm:ml-3">
                <router-link to="/ComputerRepair" style ="background-color:#76B82A;" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-base rounded-md text-black md:py-4 md:text-lg md:px-4">
                  Computer Repair
                </router-link>
              </div>
          
              <div class="rounded-md shadow sm:mt-0 sm:ml-3">
                <router-link to="/SoftwareInstall" style ="background-color:#76B82A;" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-base rounded-md text-black md:py-4 md:text-lg md:px-4">
                  Software Install
                </router-link>
              </div>
            </div> -->
          </div>
        </div>
    
        <div class="relative w-full h-64 sm:h-72 md:h-96 lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2 lg:h-full">
          <img class="absolute inset-0 w-full h-full object-cover" src="/HydroponicsPrototype.jpg" alt="Hydroponics in a Box Prototype">
        </div>
      </main>
  
      <!-- Neswletter form -->
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
    import Vue from "vue";
    import SGHeader from "~/components/SGHeader.vue";
    import SGFooter from "~/components/SGFooter.vue";
  
    export default Vue.extend({
      components: {
        SGHeader,
        SGFooter
      }
    });
  </script>