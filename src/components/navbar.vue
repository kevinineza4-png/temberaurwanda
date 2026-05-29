<template>
  <nav class="bg-green-800 text-white flex justify-between py-4 px-3 items-center shadow-lg">
    
    <span class="text-xl font-bold flex gap-2">
      <img src="../assets/GPB.png" alt="TR" class="w-10 h-10 rounded-full">
    </span>

    <ul class="flex gap-8 text-sm font-medium">
      
      <li>
        <router-link to="/" class="hover:text-yellow-300">
          Home
        </router-link>
      </li>

      <li>
        <router-link to="/about" class="hover:text-yellow-300">
          About us
        </router-link>
      </li>

      <li>
        <router-link to="/services" class="hover:text-yellow-300">
          Services
        </router-link>
      </li>

      <!-- Gallery -->
      <li class="relative group">
        
        <span class="hover:text-yellow-300 cursor-default select-none">
          Gallery <span>▼</span>
        </span>

        <ul
          class="invisible group-hover:visible opacity-0 group-hover:opacity-100 absolute bg-white text-green-900 rounded shadow w-48 mt-2 z-50 transition-all duration-300"
        >
          <li>
            <router-link
              to="/photos"
              class="block px-4 py-2 hover:bg-green-200"
            >
              Photos
            </router-link>
          </li>

          <li>
            <router-link
              to="/video"
              class="block px-4 py-2 hover:bg-green-200"
            >
              Videos
            </router-link>
          </li>
        </ul>
      </li>

      <!-- Destination -->
      <li class="relative group">

        <span class="hover:text-yellow-300 cursor-default select-none">
          Destination <span>▼</span>
        </span>

        <ul
          class="invisible group-hover:visible opacity-0 group-hover:opacity-100 absolute bg-white text-green-900 rounded shadow w-48 mt-2 z-50 transition-all duration-300"
        >
          <li>
            <router-link
              to="/northern"
              class="block px-4 py-2 hover:bg-green-200"
            >
              Northern province
            </router-link>
          </li>

          <li>
            <router-link
              to="/Eastern"
              class="block px-4 py-2 hover:bg-green-200"
            >
              Eastern province
            </router-link>
          </li>

          <li>
            <router-link
              to="/kigali"
              class="block px-4 py-2 hover:bg-green-200"
            >
              Kigali City
            </router-link>
          </li>

          <li>
            <router-link
              to="/western"
              class="block px-4 py-2 hover:bg-green-200"
            >
              Western province
            </router-link>
          </li>

          <li>
            <router-link
              to="/southern"
              class="block px-4 py-2 hover:bg-green-200"
            >
              Southern province
            </router-link>
          </li>
        </ul>
      </li>

      <li>
        <router-link to="/contact" class="hover:text-yellow-300">
          Contact
        </router-link>
      </li>

    </ul>
  </nav>
</template>