<template>
    <div>
      <nav class="bg-white px-2 sm:px-4 py-5 text-lg">
        <div class="container flex flex-wrap justify-between items-center mx-auto">
            <a href="" class="flex items-center">
                <img src="../assets/logo.png" class="mr-3 h-6 sm:h-9" alt="Logo" />
                <span class="self-center text-3xl font-bold">RaiseUpFaith</span>
            </a>

            <button data-collapse-toggle="mobile-menu" type="button" class="inline-flex items-center p-2 ml-3 text-l rounded-lg md:hidden">
                <span class="sr-only">Open main menu</span>
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
                <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
            </button>
            
        <div class="hidden w-full md:block md:w-auto" id="mobile-menu">

        <ul class="flex flex-col items-center mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
            <li>
                <a href="#" class="block py-2 pr-4 pl-3 text-base hover:text-yellow-500 transition duration-200 md:p-0">Pricing</a>
            </li>

            <li>
                <a href="#" class="block py-2 pr-4 pl-3 text-base hover:text-yellow-500 transition duration-200 md:p-0">Free Resources</a>
            </li>

            <li>
                <a href="#" class="block py-2 pr-4 pl-3 text-base hover:text-yellow-500 transition duration-200 md:p-0">Curriculums</a>
            </li>

            <li>
                <a href="#" class="block py-2 pr-4 pl-3 text-base hover:text-yellow-500 transition duration-200 md:p-0">Articles</a>
            </li>

            <li>
                <a href="#" class="block py-2 pr-4 pl-3 text-base hover:text-yellow-500 transition duration-200 md:p-0">Log in</a>
            </li>

            <button class="flex items-center text-base justify-center text-cyan-700 p-2 w-32 h-8 border border-cyan-700 rounded-full font-semibold">Take a tour</button>

            <button class="flex items-center text-base justify-center bg-cyan-700 text-white w-32 h-8 border border-cyan-700 rounded-full font-semibold">Try for free</button>
        </ul>
        </div>
  </div>
</nav>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style>

</style>