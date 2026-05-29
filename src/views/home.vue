<template>
  <div class="w-full min-h-screen bg-green-950 text-white overflow-hidden">

    <!-- HERO SECTION -->
    <section class="relative h-screen">

      <!-- VIDEO -->
      <video
        autoplay
        muted
        loop
        playsinline
        class="absolute top-0 left-0 w-full h-full object-cover"
      >
        <source
          src="https://www.youtube.com/watch?v=-kerFdxWG-w&pp=ygUOcndhbmRhIHRvdXJpc20%3D"
          type="video/mp4"
        />
      </video>

      <!-- OVERLAY -->
      <div class="absolute inset-0 bg-black/60"></div>

      <!-- CONTENT -->
      <div class="relative z-10 flex flex-col justify-center items-center h-full text-center px-6">

        <h1 class="text-5xl md:text-7xl font-extrabold text-yellow-300 mb-6">
          Tembera U Rwanda
        </h1>

        <p class="max-w-3xl text-lg md:text-2xl text-green-100 leading-8 mb-8">
          Discover Rwanda’s beautiful mountains, wildlife, lakes,
          culture, and unforgettable tourism experiences.
        </p>

        <div class="flex gap-4 flex-wrap justify-center">

          <RouterLink
            to="/about"
            class="bg-yellow-300 text-green-900 px-8 py-4 rounded-full font-bold hover:bg-yellow-400 transition duration-300"
          >
            Explore Now
          </RouterLink>

          <RouterLink
            to="/contact"
            class="border-2 border-white px-8 py-4 rounded-full hover:bg-white hover:text-green-900 transition duration-300"
          >
            Contact Us
          </RouterLink>

        </div>

      </div>
    </section>

    <!-- WELCOME SECTION -->
    <section class="py-20 px-8 bg-green-900">

      <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-12 items-center">

        <!-- TEXT -->
        <div>

          <h2 class="text-4xl font-bold text-yellow-300 mb-6">
            Welcome to Rwanda
          </h2>

          <p class="text-green-100 text-lg leading-8 mb-6">
            Rwanda is known as the land of a thousand hills.
            It is one of Africa’s cleanest and safest countries
            with beautiful national parks, lakes, wildlife,
            and amazing culture.
          </p>

          <p class="text-green-100 text-lg leading-8">
            Tembera U Rwanda helps tourists and local visitors
            explore every province and discover the beauty
            hidden across the country.
          </p>

        </div>

        <!-- IMAGE -->
        <div>
          <img
            src="https://images.unsplash.com/photo-1506744038136-46273834b3fb"
            alt="Rwanda Tourism"
            class="w-full h-[450px] object-cover rounded-3xl shadow-2xl"
          />
        </div>

      </div>

    </section>

    <!-- DESTINATIONS -->
    <section class="py-20 px-8 bg-green-950">

      <h2 class="text-center text-4xl font-bold text-yellow-300 mb-14">
        Popular Destinations
      </h2>

      <div class="grid md:grid-cols-3 gap-10 max-w-7xl mx-auto">

        <!-- CARD 1 -->
        <div class="bg-green-900 rounded-3xl overflow-hidden shadow-xl hover:scale-105 transition duration-300">

          <img
            src="https://images.unsplash.com/photo-1547471080-7cc2caa01a7e"
            class="w-full h-60 object-cover"
          />

          <div class="p-6">

            <h3 class="text-2xl font-bold text-yellow-300 mb-4">
              Kigali City
            </h3>

            <p class="text-green-100 leading-7">
              Visit the clean and modern capital city of Rwanda
              filled with culture, restaurants, and entertainment.
            </p>

          </div>

        </div>

        <!-- CARD 2 -->
        <div class="bg-green-900 rounded-3xl overflow-hidden shadow-xl hover:scale-105 transition duration-300">

          <img
            src="https://images.unsplash.com/photo-1516426122078-c23e76319801"
            class="w-full h-60 object-cover"
          />

          <div class="p-6">

            <h3 class="text-2xl font-bold text-yellow-300 mb-4">
              Volcanoes National Park
            </h3>

            <p class="text-green-100 leading-7">
              Explore Rwanda’s famous gorillas and beautiful
              volcanic mountains in the northern province.
            </p>

          </div>

        </div>

        <!-- CARD 3 -->
        <div class="bg-green-900 rounded-3xl overflow-hidden shadow-xl hover:scale-105 transition duration-300">

          <img
            src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee"
            class="w-full h-60 object-cover"
          />

          <div class="p-6">

            <h3 class="text-2xl font-bold text-yellow-300 mb-4">
              Lake Kivu
            </h3>

            <p class="text-green-100 leading-7">
              Relax near Rwanda’s beautiful lake beaches and
              enjoy peaceful views and fresh air.
            </p>

          </div>

        </div>

      </div>

    </section>

  </div>
</template>