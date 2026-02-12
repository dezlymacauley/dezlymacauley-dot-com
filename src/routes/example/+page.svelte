<script lang="ts">
  import logo from "./images/logo.png";
</script>


<!-- Done  -->

  <!--
    mx-auto is used when you want to align an html block element 
    to the center of its parent container.

    mx-auto only works when you set a limit on the width of the element.
    That's why I have max-w-6xl
    
    This div is the container for the entire navigation bar
  -->
  <div class="max-w-6xl mx-auto px-4">
  
    <!-- Container for the left and right section -->
    <!--
      `flex` to turn the container into a Flexbox

      Use flexbox when you want to align the contents of a container.

      flex by default will align the items in a row
      justify-between will add an equal amount of space between each element
    -->
    <div class="flex justify-between">

      <!-- Left Section  -->
      <div class="flex">

         <!-- 
          items-center  
          align items in the middle vertically
        -->
        <a href="/01-tailwindcss/projects/real-estate-website" class="border-4 border-amber-300 flex items-center py-4 px-2">
          <img class="border-4 border-red-500 h-8 w-8 mr-2" src={logo} alt="brand logo">
          <span class="border-4 border-red-500 text-lg font-semibold text-gray-500">Prime Properties</span>
        </a>

      </div>

      <!-- Right Section  -->
      <div class="flex">

        <a href="/01-tailwindcss/projects/real-estate-website" class="border-4 border-pink-400 px-2 py-4 text-gray-500 font-semibold">
          Home
        </a>
        
        <a href="/01-tailwindcss/projects/real-estate-website" class="border-4 border-pink-400 px-2 py-4 text-gray-500 font-semibold">
          Service 
        </a>

        <a href="/01-tailwindcss/projects/real-estate-website" class="border-4 border-pink-400 px-2 py-4 text-gray-500 font-semibold">
          About
        </a>

        <a href="/01-tailwindcss/projects/real-estate-website" class="border-4 border-pink-400 px-2 py-4 text-gray-500 font-semibold">
          Contact
        </a>
        
        <a href="/01-tailwindcss/projects/real-estate-website" class="border-4 border-pink-400 px-2 py-4 text-gray-500 font-semibold">
          Toggle dark Mode
        </a>
      </div>

    </div>

  </div>
