<template>
    <div class="relative bg-gray-50">
        <!-- <div class="relative px-4 pt-6 sm:px-6 lg:px-8">
            <nav
                class="relative flex items-center justify-between sm:h-10 lg:justify-start"
                aria-label="Global"
            >
                <div
                  class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0"
                >
                    <div class="flex items-center justify-between w-full md:w-auto">
                        <a href="/">
                            <span class="sr-only">DundeeBots</span>
                            <img class="w-auto h-8 sm:h-20" src="/logo.svg" />
                        </a>
                    </div>
                </div>
                <div class = "hidden lg:flex lg:min-w-0 lg:flex-1 lg:justify-center lg:gap-x-12">
                    <a href ="/SmartGarden" class="lg:gap-x-12 text-base font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-teal-500">
                    Smart Garden
                    </a>
                </div>
            </nav>
        </div> -->
        <div class="max-w-7xl mx-auto px-4 sm:px-6">
            <div class="flex justify-between items-center py-6 md:justify-start md:space-x-10">
                <div class="flex justify-start lg:w-0 lg:flex-1">
                    <a href="/">
                        <span class="sr-only">DundeeBots</span>
                        <img class="h-8 w-auto sm:h-20" src="@/static/logo.svg" alt="Logo">
                    </a>
                </div>
         
                <div class="-mr-2 -my-2 md:hidden">
                    <button type="button" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-teal-600">
                        <span class="sr-only">
                            Open menu
                        </span>
                    </button>
                </div>

                <!-- Desktop Menu -->
                <nav class="hidden md:flex space-x-10">
                    <!-- Nested menu -->
                    <!-- <div class="relative">
                        <button type="button" @click="isOpen =!isOpen" class="group bg-white rounded-md text-gray-500 inline-flex items-center text-base font-medium hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-red-500">
                            <span> Tutorials </span>
                            <svg class="ml-2 h-5 w-5 text-gray-400 group-hover:text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                            </svg>
                        </button>

                        <transition
                            enter-active-class="transition ease-out duration-200 transform"
                            enter-class="opacity-0 translate-y-1"
                            enter-to-class="opacity-100 translate-y-0"
                            leave-active-class="transition ease-in duration-150"
                            leave-class="opacity-100 translate-y-0"
                            leave-to-class="opacity-0 translate-y-1"
                        >      
                            <div v-show="isOpen" class="origin-top-right absolute right-0 mt-2 w-56 rounded-md shadow-lg">
                                <div class="rounded-md bg-white shadow-xs">
                   
                                    <div class="absolute -ml-4 mt-3 transform z-10 px-2 w-screen max-w-md sm:px-0 lg:ml-0 lg:left-1/2 lg:-translate-x-1/2">
                                    <div class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 overflow-hidden">
                                    <div class="relative grid gap-6 bg-white px-5 py-6 sm:gap-8 sm:p-8">
                     
                         <NuxtLink to="/RaspberryPi" class="-m-3 p-3 flex items-start rounded-lg hover:bg-gray-50">
                           <img class="flex-shrink-0 h-6 w-6" src="/static/images/RaspberryPi.png" alt="Image of a Raspberry Pi">
                           <div class="ml-4">
                             <p class="text-base font-medium text-gray-900">
                               Raspberry Pi
                             </p>
                             <p class="mt-1 text-sm text-gray-500">
                               Raspberry Pi Tutorials
                             </p>
                           </div>
                         </NuxtLink>

                         <NuxtLink to="/microbit" class="-m-3 p-3 flex items-start rounded-lg hover:bg-gray-50">
                           <img class="flex-shrink-0 h-6 w-6" src="@/static/images/microbit.png" alt="Image of a micro:bit">
                           <div class="ml-4">
                             <p class="text-base font-medium text-gray-900">
                               micro:bit
                             </p>
                             <p class="mt-1 text-sm text-gray-500">
                               BBC micro:bit Tutorials
                             </p>
                           </div>
                         </NuxtLink>
                       </div>
                     </div>
                   </div>
                 </div>
               </div>
             </transition>
           </div> -->

                    <a href="/SmartGarden" class="text-base font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-teal-600">
                        Smart Garden
                    </a>

                    <!-- <a href="/HilltownStobswellTech" class="text-base font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-teal-600">
                        Hilltown Stobswell Tech
                    </a> -->
                </nav>
                <!-- Desktop Menu END -->
            </div>
       
            <!-- Mobile Menu -->
            <div class="absolute top-0 inset-x-0 z-10 p-2 transition transform origin-top-right md:hidden">
                <div class="rounded-lg shadow-lg ring-1 ring-black ring-opacity-5 bg-white divide-y-2 divide-gray-50">
                    <div class="pt-5 pb-6 px-5">
                        <div class="flex items-center justify-between">
                            <a href="/">
                                <img class="h-8 w-auto sm:h-10" src="@/static/logo.svg" alt="Logo">
                            </a>
                            
                            <div class="-mr-2">
                                <button type="button" @click="isOpen = !isOpen" class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-teal-600">
                                    <span class="sr-only">
                                        Open menu
                                    </span>
                                    <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                                    </svg>
                                </button>
                 
                                <transition
                                    enter-active-class="duration-150 ease-out"
                                    enter-class="opacity-0 scale-95"
                                    enter-to-class="opacity-100 scale-100"
                                    leave-active-class="duration-100 ease-in"
                                    leave-class="opacity-100 scale-100"
                                    leave-to-class="opacity-0 scale-95"
                                >
                                    <div v-show="isOpen" class="origin-top-right absolute right-0 mt-2 w-56 rounded-md shadow-lg">
                                        <div class="rounded-md bg-white shadow-xs">
                                            <div class="mt-6">
                                                <nav class="grid gap-y-8">
                                                    <a href="/SmartGarden" class="text-base font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-teal-600 p-3">
                                                        Smart Garden
                                                    </a>
                                                </nav>
                                            </div>
                                        </div>
                                    </div>
                                </transition>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
      
        <!-- main -->
        <div class="relative px-4 pt-6 sm:px-6 lg:px-8">
            <!--Page Heading-->
            <div class="text-lg max-w-prose mx-auto">
                <h1 class="text-4xl tracking-tight font-extrabold text-teal-600 sm:text-5xl md:text-6xl lg:text-5xl xl:text-6xl">
                    Resources
                </h1>
            </div>
              
            <div class="mt-6 prose prose-indigo prose-lg text-gray-500 mx-auto">   
                <!-- Page Description -->           
                <p> 
                    This page will provide you with all the coding examples and resources that we are using for the Smart Garden project.
                </p>

                <!-- Section header -->
                <h2 class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be">
                    Contents
                </h2>

                <!-- Page Contents -->
                <ul>
                    <li> 
                        <a href = "#microbit"> 
                            micro:bit resources
                        </a> 
                    </li>
                   <!--  <li> 
                        <a href = "#pico">
                            Raspberry Pi Pico resources
                        </a> 
                    </li>
                    <li> 
                        <a href = "#anvil">
                            Anvil Web App
                        </a> 
                    </li> -->
                </ul>
                
                <!-- micro:bit Section -->
                <h2>
                    <a id = "microbit" class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be">
                        micro:bit
                    </a>
                </h2>
                
                <p>
                    List of all code examples and micro:bit resources we are using for the micro:bit
                </p> 
                <!-- micro:bit Section Contents -->
                <ul>
                    <li> 
                        <a href = "#LEDStripCode"> 
                            LED Strip Code
                        </a> 
                    </li>
                   <li> 
                        <a href = "#Greenhouse">
                            Kitronik Smart Green House Kit
                        </a> 
                    </li>
                    <!--<li> 
                        <a href = "#anvil">
                            Anvil Web App
                        </a> 
                    </li> -->
                </ul>
                
                <h3>
                    <a id = "LEDStripCode" class="md:text-3xl tracking-tight font-extrabold" style="color:#66b7be">
                        LED Strip Code
                    </a>
                </h3>

                <p> 
                    Click the download links to download the corresponding code file for the micro:bit 
                </p>
                
                <!-- Downloads section for LED Strip -->
                <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
                    <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">
                        <div class="sm:col-span-2">
                            <dt class="text-md font-medium text-gray-500" style="color: #088494">Downloads</dt>
                            <dd class="mt-1 text-sm text-gray-900">
                                <ul role="list" class="border border-gray-200 rounded-md divide-y divide-gray-200">
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Lesson plan download" />
                                            <span class="ml-2 flex-1 w-0 truncate">  LED Strip Test </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href = "microbit-LEDTest.hex" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download
                                            </a>
                                        </div>
                                    </li>

                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Slide deck download"/>
                                            <span class="ml-2 flex-1 w-0 truncate">  Code for LED Strip waiting for command from Remote micro:bit </span>
                                        </div>
                           
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="/microbit-LEDRecieved.hex" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download 
                                            </a>
                                        </div>
                                    </li>

                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Teaching Notes download"/>
                                            <span class="ml-2 flex-1 w-0 truncate"> Code for remote micro:bit controlling the LEDs e.g. press button A for Red </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="/microbit-LEDRemote.hex" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download 
                                            </a>
                                        </div>
                                    </li>
                                </ul>
                           </dd>
                        </div>
                     </dl>
                </div>

                <h3>
                    <a id = "Greenhouse" class="md:text-3xl tracking-tight font-extrabold" style="color:#66b7be">
                        Kitronik Smart Green House Kit
                    </a>
                </h3>

                <p> 
                    Links to resources and code downloads. 
                </p>
                
                <!-- Downloads section for Smart Garden Kit -->
               <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
                    <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">
                        <div class="sm:col-span-2">
                            <dt class="text-md font-medium text-gray-500" style="color: #088494">Downloads and Links</dt>
                            <dd class="mt-1 text-sm text-gray-900">
                                <ul role="list" class="border border-gray-200 rounded-md divide-y divide-gray-200">
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/link.svg" alt="Lesson plan download" />
                                            <span class="ml-2 flex-1 w-0 truncate">  Smart Garden Webpage </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href = "https://kitronik.co.uk/collections/microbit-and-accessories/products/5699-kitronik-smart-greenhouse-kit" target="_blank" class="font-medium" style="color: #088494"> 
                                                Link
                                            </a>
                                        </div>
                                    </li>

                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/link.svg" alt="Slide deck download"/>
                                            <span class="ml-2 flex-1 w-0 truncate">  Coding Tutorials for the Greenhouse Kit </span>
                                        </div>
                           
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="https://kitronik.co.uk/blogs/resources/kitronik-greenhouse-kit-online-makecode-tutorials" target="_blank" class="font-medium" style="color: #088494"> 
                                                Link
                                            </a>
                                        </div>
                                    </li>

                                    <!-- <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Teaching Notes download"/>
                                            <span class="ml-2 flex-1 w-0 truncate"> Code for remote micro:bit controlling the LEDs e.g. press button A for Red </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="/GettingStartedMB/TeacherNotes.pdf" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download 
                                            </a>
                                        </div>
                                    </li> -->
                                </ul>
                           </dd>
                        </div>
                     </dl>
                    </div>
              
                <!-- Raspberry Pi Pico Section -->
                <h2 >
                    <a id = "pico" class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be">
                        Raspberry Pi Pico
                    </a>
                </h2>
    
                <p>
                    List of all code examples and resources we are using for the pico
                </p>
                
                <!-- Downloads Section for Pico -->
                <!-- <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
                    <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">
                        <div class="sm:col-span-2">
                            <dt class="text-md font-medium text-gray-500" style="color: #088494">Downloads</dt>
                            <dd class="mt-1 text-sm text-gray-900">
                                <ul role="list" class="border border-gray-200 rounded-md divide-y divide-gray-200">
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Lesson plan download" />
                                            <span class="ml-2 flex-1 w-0 truncate">  Getting Started Lesson Plan </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href = "/GettingStartedMB/LessonPlan.pdf" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download
                                            </a>
                                        </div>
                                    </li>
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Slide deck download"/>
                                            <span class="ml-2 flex-1 w-0 truncate">  Getting Started Slide Deck </span>
                                        </div>
                           
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="/GettingStartedMB/SlideDeck.pdf" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download 
                                            </a>
                                        </div>
                                    </li>
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Teaching Notes download"/>
                                            <span class="ml-2 flex-1 w-0 truncate"> Getting Started Teaching Notes </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="/GettingStartedMB/TeacherNotes.pdf" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download 
                                            </a>
                                        </div>
                                    </li>
                                </ul>
                           </dd>
                        </div>
                     </dl>
                </div> -->
                
                <!-- Anvil Web App Section -->
                <h2>
                    <a id = "anvil" class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be">
                        Anvil Web App
                    </a>
                </h2>
                
                <p> 
                    Link to the Web App and resources used to create it.
                </p>

                <!-- Downloads Section for Anvil -->
                <!-- <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
                    <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">
                        <div class="sm:col-span-2">
                            <dt class="text-md font-medium text-gray-500" style="color: #088494">Downloads</dt>
                            <dd class="mt-1 text-sm text-gray-900">
                                <ul role="list" class="border border-gray-200 rounded-md divide-y divide-gray-200">
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Lesson plan download" />
                                            <span class="ml-2 flex-1 w-0 truncate">  Getting Started Lesson Plan </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href = "/GettingStartedMB/LessonPlan.pdf" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download
                                            </a>
                                        </div>
                                    </li>
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Slide deck download"/>
                                            <span class="ml-2 flex-1 w-0 truncate">  Getting Started Slide Deck </span>
                                        </div>
                           
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="/GettingStartedMB/SlideDeck.pdf" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download 
                                            </a>
                                        </div>
                                    </li>
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Teaching Notes download"/>
                                            <span class="ml-2 flex-1 w-0 truncate"> Getting Started Teaching Notes </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="/GettingStartedMB/TeacherNotes.pdf" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download 
                                            </a>
                                        </div>
                                    </li>
                                </ul>
                           </dd>
                        </div>
                     </dl>
                </div> -->
            </div>
        </div>
    </div>
</template>
  
<script lang="ts">
    import Vue from "vue";

    export default Vue.extend({
        data: () => ({
            isOpen: false,
        })
    });
</script>