<template>
    <div class="relative bg-gray-50">
        
        <HSTHeaderPages />
     
        <!-- main -->
         <div class="relative px-4 pt-6 sm:px-6 lg:px-8">
            <!--Page Heading-->
            <div class="text-lg max-w-prose mx-auto">
                <h1 class="text-4xl tracking-tight font-extrabold text-teal-600 sm:text-5xl md:text-6xl lg:text-5xl xl:text-6xl">
                    3d Printing
                </h1>
            </div>
              
            <div class="mt-6 prose prose-indigo prose-lg text-gray-500 mx-auto">   
                <!-- Page Description -->           
                <p> 
                    Useful 3d printing resources for the classroom
                </p>

                <!-- Section header -->
                 <!-- <h2 class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be">
                    Contents
                </h2>

                 Page Contents
                <ul>
                    <li> 
                        <a href = "#microbit"> 
                            micro:bit resources
                        </a> 
                    </li>
                    <li> 
                        <a href = "#pico">
                            Raspberry Pi Pico resources
                        </a> 
                    </li>
                    <li> 
                        <a href = "#anvil">
                            Anvil Web App
                        </a> 
                    </li>
                </ul> -->
                
                <h3 class = "font-extrabold" style="color:#66b7be">
                    <!-- <a id = "microbit" class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be"> -->
                        3d Printer Software
                    <!-- </a> -->
                </h3>

                <p> Cura Slicer – Use this to process a 3D model prior to printing on a 3D printer.</p>

                <p> Tinkercad - Free website used to design 3d models. Lots of free resources </p>
                
                <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
                    <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">
                        <div class="sm:col-span-2">
                            <dt class="text-md font-medium text-gray-500" style="color: #088494">
                                Links
                            </dt>
                            <dd class="mt-1 text-sm text-gray-900">
                                <ul role="list" class="border border-gray-200 rounded-md divide-y divide-gray-200">
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/globe.svg" alt="Link to cura"/>
                                            <span class="ml-2 flex-1 w-0 truncate">  Cura free 3d printing slicer </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href = "https://ultimaker.com/software/ultimaker-cura" target="_blank" class="font-medium" style="color: #088494"> 
                                                Cura Download
                                            </a>
                                        </div>
                                    </li>

                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/globe.svg" alt="Slide deck download"/>
                                            <span class="ml-2 flex-1 w-0 truncate">  
                                                Tinkercad - free 3d modelling software 
                                            </span>
                                        </div>
                           
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="https://www.tinkercad.com/" target="_blank" class="font-medium" style="color: #088494"> 
                                                Tinkercad
                                            </a>
                                        </div>
                                    </li>

                                    <!--<li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/paperclip.svg" alt="Teaching Notes download"/>
                                            <span class="ml-2 flex-1 w-0 truncate"> Code for remote micro:bit controlling the LEDs e.g. press button A for Red </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="/microbit-LEDRemote.hex" target="_blank" class="font-medium" style="color: #088494"> 
                                                Download 
                                            </a>
                                        </div>
                                    </li> -->
                                </ul>
                           </dd>
                        </div>
                     </dl>
                </div>

                <h3 class = "font-extrabold" style="color:#66b7be">
                    <!-- <a id = "Greenhouse" class="md:text-3xl tracking-tight font-extrabold" style="color:#66b7be"> -->
                     3d Models   
                    <!-- </a> -->
                </h3>

                <p> 
                    <b> Supported file formats are STL, OBJ, X3D and 3MF. </b> 
                </p>

                <p>
                    There is a number of different sites that offer free 3D models. As long as you download a 3D model in one of the above file formats, it can be opened in Cura and processed for 3D printing.
                </p>
                
                <!-- Downloads section for Smart Garden Kit -->
               <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
                    <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">
                        <div class="sm:col-span-2">
                            <dt class="text-md font-medium text-gray-500" style="color: #088494">
                                Useful Links
                            </dt>

                            <dd class="mt-1 text-sm text-gray-900">
                                <ul role="list" class="border border-gray-200 rounded-md divide-y divide-gray-200">
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/globe.svg" alt="thingiverse" />
                                            <span class="ml-2 flex-1 w-0 truncate">  
                                                Thingiverse - Digital Designs for physical objects
                                            </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href = "https://www.thingiverse.com/" target="_blank" class="font-medium" style="color: #088494"> 
                                                Thingiverse
                                            </a>
                                        </div>
                                    </li>

                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/globe.svg" alt="Slide deck download"/>
                                            <span class="ml-2 flex-1 w-0 truncate">  
                                                Printables - 3D models database
                                            </span>
                                        </div>
                           
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="https://www.printables.com/" target="_blank" class="font-medium" style="color: #088494"> 
                                                Printables
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
              
                <h3 class = "font-extrabold" style="color:#66b7be">
                    <!-- <a id = "pico" class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be"> -->
                        Standard part 3D models
                    <!-- </a> -->
                </h3>
    
                <p>
                    If you require 3D models of standard parts like screws, nuts and bolts or other random “industrial” items they can be found on McMaster-Carr.
                </p>

                <p>
                    Not all of the advertised parts have 3D models, but if you see this little logo (See below) a 3D model is available.
                </p>

                <img class="flex-shrink-0 h-20 w-20" src="@/static/CADIcon.svg" alt="CAD Icon" />

                <img src="@/static/Screws.png" alt="Screws example" />

                <p>
                    In this example, selecting a part number opens a new drop-down allowing you to select different file formats. From the drop down select 3D STEP. This file can be opened in your 3D modelling software and saved as an STL for 3D printing.
                </p>

                <img src="@/static/Screws2.png" alt="Screws example" />

                <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
                    <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">
                        <div class="sm:col-span-2">
                            <dt class="text-md font-medium text-gray-500" style="color: #088494">
                                Links
                            </dt>

                            <dd class="mt-1 text-sm text-gray-900">
                                <ul role="list" class="border border-gray-200 rounded-md divide-y divide-gray-200">
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/globe.svg" alt="Lesson plan download" />
                                            <span class="ml-2 flex-1 w-0 truncate">
                                                McMaster-Carr - General engineering parts
                                            </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href = "https://www.mcmaster.com/" target="_blank" class="font-medium" style="color: #088494"> 
                                                McMaster
                                            </a>
                                        </div>
                                    </li>
                                   <!-- <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
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
                                    </li> -->
                                </ul>
                           </dd>
                        </div>
                     </dl>
                </div>
                
                <h3 class = "font-extrabold" style="color:#66b7be">
                    <!-- <a id = "pico" class="text-3xl tracking-tight font-extrabold sm:text-5xl md:text-5xl lg:text-4xl xl:text-5xl" style="color:#66b7be"> -->
                        3D Printing Videos
                    <!-- </a> -->
                </h3>
                
                <p> 
                    Here are some links to useful YouTube Videos.
                </p>

                <div class="border-t border-gray-200 px-4 py-5 sm:px-6">
                    <dl class="grid grid-cols-1 gap-x-4 gap-y-8 sm:grid-cols-2">
                        <div class="sm:col-span-2">
                            <dt class="text-md font-medium text-gray-500" style="color: #088494"> 
                            Videos
                            </dt>
                            <dd class="mt-1 text-sm text-gray-900">
                                <ul role="list" class="border border-gray-200 rounded-md divide-y divide-gray-200">
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/youtube.svg" alt="Lesson plan download" />
                                            <span class="ml-2 flex-1 w-0 truncate">  Getting Started with Ender 3 </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href = "https://www.youtube.com/watch?v=T-Z3GmM20JM&list=PLGqRUdq5ULsOwW9G08jV43YTdMyqJ6xGB" target="_blank" class="font-medium" style="color: #088494"> 
                                                Video
                                            </a>
                                        </div>
                                    </li>
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/youtube.svg" alt="Slide deck download"/>
                                            <span class="ml-2 flex-1 w-0 truncate">  Teaching Tech </span>
                                        </div>
                           
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="https://www.youtube.com/c/TeachingTech/playlists" target="_blank" class="font-medium" style="color: #088494"> 
                                                Video
                                            </a>
                                        </div>
                                    </li>
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/youtube.svg" alt="Teaching Notes download"/>
                                            <span class="ml-2 flex-1 w-0 truncate"> Makers Muse YouTue Channel </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="https://www.youtube.com/c/MakersMuse/playlists" target="_blank" class="font-medium" style="color: #088494"> 
                                                Video
                                            </a>
                                        </div>
                                    </li>
                                    <li class="pl-3 pr-4 py-3 flex items-center justify-between text-sm">
                                        <div class="w-0 flex-1 flex items-center">
                                            <img class="flex-shrink-0 h-5 w-5" src="@/static/youtube.svg" alt="Teaching Notes download"/>
                                            <span class="ml-2 flex-1 w-0 truncate"> 3D Printing 101 </span>
                                        </div>
                          
                                        <div class="ml-4 flex-shrink-0">
                                            <a href="https://www.youtube.com/playlist?list=PLTCCNNvHC8PDR_jQy609toqq8EAfhiOOL" target="_blank" class="font-medium" style="color: #088494"> 
                                                Video
                                            </a>
                                        </div>
                                    </li>
                                </ul>
                           </dd>
                        </div>
                     </dl>
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import Vue from "vue";
    import HSTHeaderPages from "~/components/HSTHeaderPages.vue";

    export default Vue.extend({
        components: {
            HSTHeaderPages
        }
        
    });
</script>
  
  