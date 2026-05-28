<template>
  <nav class="bg-green-800 text-white flex justify-between py-4 px-3 items-center shadow-lg">
    
    <span class="text-xl font-bold flex gap-2">
      <img src="../assets/GPB.png" alt="TR" class="w-10 h-10 rounded-full">
    </span>

    <ul class="flex gap-8 text-sm font-medium">
      
      <li>
        <a href="/" class="hover:text-yellow-300">Home</a>
      </li>

      <li>
        <a href="/about" class="hover:text-yellow-300">About us</a>
      </li>

      <li>
        <a href="/services" class="hover:text-yellow-300">Services</a>
      </li>

      <!-- Gallery -->
      <li class="relative group">
        
        <!-- cursor disabled -->
        <span class="hover:text-yellow-300 cursor-default select-none">
          Gallery <span>▼</span>
        </span>

        <ul
          class="invisible group-hover:visible opacity-0 group-hover:opacity-100 absolute bg-white text-green-900 rounded shadow w-48 mt-2 z-50 transition-all duration-300"
        >
          <li>
            <a href="/photos" class="block px-4 py-2 hover:bg-green-200">
              Photos
            </a>
          </li>

          <li>
            <a href="/video" class="block px-4 py-2 hover:bg-green-200">
              Videos
            </a>
          </li>
        </ul>
      </li>

      <!-- Destination -->
      <li class="relative group">

        <!-- cursor disabled -->
        <span class="hover:text-yellow-300 cursor-default select-none">
          Destination <span>▼</span>
        </span>

        <ul
          class="invisible group-hover:visible opacity-0 group-hover:opacity-100 absolute bg-white text-green-900 rounded shadow w-48 mt-2 z-50 transition-all duration-300"
        >
          <li>
            <a href="/northern" class="block px-4 py-2 hover:bg-green-200">
              Northern province
            </a>
          </li>

          <li>
            <a href="/Eastern" class="block px-4 py-2 hover:bg-green-200">
              Eastern province
            </a>
          </li>

          <li>
            <a href="/kigali" class="block px-4 py-2 hover:bg-green-200">
              Kigali City
            </a>
          </li>

          <li>
            <a href="/western" class="block px-4 py-2 hover:bg-green-200">
              Western province
            </a>
          </li>

          <li>
            <a href="/southern" class="block px-4 py-2 hover:bg-green-200">
              Southern province
            </a>
          </li>
        </ul>
      </li>

      <li>
        <a href="/contact" class="hover:text-yellow-300">Contact</a>
      </li>

    </ul>
  </nav>
</template>