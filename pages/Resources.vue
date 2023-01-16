<template>
    <div class="relative bg-gray-50">
        <div class="relative px-4 pt-6 sm:px-6 lg:px-8">
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
        </div>
      <!-- main -->
            
        <div class="relative px-4 sm:px-6 lg:px-8">
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
               <!-- <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
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
                                            <a href = "/GettingStartedMB/LessonPlan.pdf" target="_blank" class="font-medium" style="color: #088494"> 
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
                                            <a href="/GettingStartedMB/SlideDeck.pdf" target="_blank" class="font-medium" style="color: #088494"> 
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
  
  