<script setup lang="ts">

</script>

<template>
  <div class="bg-gray-50 font-sans">
  <!-- Navigation -->

  <!-- Hero Section -->
  <div class="relative bg-white-100 overflow-hidden">
    <div class="max-w-7xl mx-auto">
      <div class="relative z-10 pb-8 bg-white-100 sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32">
        <div class="pt-10 sm:pt-16 lg:pt-8 lg:pb-14 lg:overflow-hidden">
          <div class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
            <div class="sm:text-center lg:text-left">
              <h2 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">
                <span class="block">New Opportunity</span>
                <span class="block text-violet-600">New Chance 2026</span>
              </h2>
              <p class="pr-[100px] mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                Explore the latest universities and grant programs worldwide.
               </p>
              <div class="mt-10 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
                <div class="rounded-md shadow mt-4">
                  <NuxtLink to="/grants" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-violet-600 md:py-4 md:text-lg md:px-10">
                    Grants
                  </NuxtLink>
                </div>
                <div class="mt-4 sm:ml-3">
                  <NuxtLink to="/scolarships" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-violet-600 md:py-4 md:text-lg md:px-10">
                    ScholarShips
                  </NuxtLink>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full" src="https://plus.unsplash.com/premium_photo-1663079426406-1b82fed16a79?q=80&w=915&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Fashion model">
    </div>
  </div>

  <!-- Categories Section -->
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
    <h2 class="text-2xl font-bold text-gray-900 mb-8">The Most Affordable</h2>
    <div class="grid grid-cols-2 gap-4 md:grid-cols-4">
      <a href="#" class="group relative block bg-gray-100 rounded-lg overflow-hidden">
        <img src="https://assets.weforum.org/article/image/QAAFBg6LUUWydJec7NJGO4cvBrUgy1LxTgfwVL7Q_r0.jpg" alt="Women's clothing" class="w-full h-64 object-cover transition-opacity group-hover:opacity-75">
        <div class="absolute inset-0 bg-gradient-to-t from-gray-900 to-transparent"></div>
        <div class="absolute bottom-0 left-0 p-4">
          <h3 class="text-xl font-semibold text-white">Germany</h3>
          <p class="mt-1 text-sm text-gray-300">View Now</p>
        </div>
      </a>
      <a href="#" class="group relative block bg-gray-100 rounded-lg overflow-hidden">
        <img src="https://www.campervannorway.com/assets/img/blog/455.png" alt="Girls' clothing" class="w-full h-64 object-cover transition-opacity group-hover:opacity-75">
        <div class="absolute inset-0 bg-gradient-to-t from-gray-900 to-transparent"></div>
        <div class="absolute bottom-0 left-0 p-4">
          <h3 class="text-xl font-semibold text-white">Norway</h3>
          <p class="mt-1 text-sm text-gray-300">View now</p>
        </div>
      </a>
      <a href="#" class="group relative block bg-gray-100 rounded-lg overflow-hidden">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmeiGre_R58jyWX4alO0Q6kwOUbXD1vv50PA&s" alt="Women's shoes" class="w-full h-64 object-cover transition-opacity group-hover:opacity-75">
        <div class="absolute inset-0 bg-gradient-to-t from-gray-900 to-transparent"></div>
        <div class="absolute bottom-0 left-0 p-4">
          <h3 class="text-xl font-semibold text-white">Iceland</h3>
          <p class="mt-1 text-sm text-gray-300">View Now</p>
        </div>
      </a>
      <a href="#" class="group relative block bg-gray-100 rounded-lg overflow-hidden">
        <img src="https://worldinparis.com/wp-content/uploads/2022/01/View-from-the-Pantheon.jpg" alt="Girls' shoes" class="w-full h-64 object-cover transition-opacity group-hover:opacity-75">
        <div class="absolute inset-0 bg-gradient-to-t from-gray-900 to-transparent"></div>
        <div class="absolute bottom-0 left-0 p-4">
          <h3 class="text-xl font-semibold text-white">France</h3>
          <p class="mt-1 text-sm text-gray-300">View Now</p>
        </div>
      </a>
    </div>
  </div>

  <!-- Products Section -->
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
    <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-8">
      <h2 class="text-2xl font-bold text-gray-900 mb-4 md:mb-0">Inaccessible universities</h2>
      <div class="flex space-x-4">
        <div class="relative">
          <select class="appearance-none bg-white border border-gray-300 rounded-md py-2 pl-3 pr-8 text-sm focus:outline-none focus:ring-pink-500 focus:border-pink-500">
            <option>Sort by: Featured</option>
            <option>Price: Low to High</option>
            <option>Price: High to Low</option>
            <option>Newest Arrivals</option>
          </select>
          <div class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700">
            <i class="fas fa-chevron-down text-xs"></i>
          </div>
        </div>
        <button class="p-2 rounded-md bg-gray-200 text-gray-700 hover:bg-gray-300">
          <i class="fas fa-filter"></i>
        </button>
      </div>
    </div>

    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
      <!-- Product 1 -->
      <div class="group relative bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg transition-shadow duration-300">
        <div class="relative">
          <img src="https://imgproxy.divecdn.com/ji_SFobiyyXvU2SrWoG3ssZvrdoUBEOJlur73auKvPg/g:ce/rs:fill:1200:675:1/Z3M6Ly9kaXZlc2l0ZS1zdG9yYWdlL2RpdmVpbWFnZS9HZXR0eUltYWdlcy0yMTcwNDI5MzY0LTIuanBn.webp" alt="Harvard" class="w-full h-80 object-cover">
          <div class="absolute top-2 right-2">
            <button class="p-2 rounded-full bg-white text-gray-700 hover:bg-pink-100 hover:text-pink-600 transition-colors duration-300">
              <i class="far fa-heart"></i>
            </button>
          </div>
          <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black to-transparent p-4">
            <span class="text-xs font-semibold text-white">Cambridge</span>
          </div>
        </div>
        <div class="p-4">
          <div class="flex justify-between items-start">
            <div>
              <h3 class="text-sm font-medium text-gray-900">
                <a href="#">
                  <span aria-hidden="true" class="absolute inset-0"></span>
                  Harvard
                </a>
              </h3>
              <p class="mt-1 text-sm text-gray-500">totally a year</p>
            </div>
            <p class="text-sm font-medium text-[#ab74ff]">$86,366–$91,166</p>
          </div>
          <div class="mt-4 flex space-x-2">
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">30</span>
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">40</span>
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">ethuro</span>
          </div>
          <div class="mt-4">
            <button class="w-full bg-violet-600  text-white py-2 px-4 rounded-md text-sm font-medium transition-colors duration-300">
              Get a link
            </button>
          </div>
        </div>
      </div>

      <!-- Product 2 -->
      <div class="group relative bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg transition-shadow duration-300">
        <div class="relative">
          <img src="https://images.unsplash.com/photo-1582530646451-9b34ae592131?fm=jpg&q=60&w=3000&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTB8fG94Zm9yZCUyMHVuaXZlcnNpdHl8ZW58MHx8MHx8fDA%3D" alt="Oxford" class="w-full h-80 object-cover">
          <div class="absolute top-2 right-2">
            <button class="p-2 rounded-full bg-white text-gray-700 hover:bg-pink-100 hover:text-pink-600 transition-colors duration-300">
              <i class="far fa-heart"></i>
            </button>
          </div>
          <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black to-transparent p-4">
            <span class="text-xs font-semibold text-white">UK</span>
          </div>
        </div>
        <div class="p-4">
          <div class="flex justify-between items-start">
            <div>
              <h3 class="text-sm font-medium text-gray-900">
                <a href="#">
                  <span aria-hidden="true" class="absolute inset-0"></span>
                  Oxford
                </a>
              </h3>
              <p class="mt-1 text-sm text-gray-500">totally a year</p>
            </div>
            <p class="text-sm font-medium text-[#ab74ff]">£38 900</p>
          </div>
          <div class="mt-4 flex space-x-2">
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">16-17</span>
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">18</span>
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">21+</span>
          </div>
          <div class="mt-4">
            <button class="w-full bg-violet-600 text-white py-2 px-4 rounded-md text-sm font-medium transition-colors duration-300">
              Get a link
            </button>
          </div>
        </div>
      </div>

      <!-- Product 3 -->
      <div class="group relative bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg transition-shadow duration-300">
        <div class="relative">
          <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/ETH_Z%C3%BCrich_-_Hauptgeb%C3%A4ude_-_Unispital_2012-07-30_07-57-03_ShiftN.jpg" alt="Women's shoes" class="w-full h-80 object-cover">
          <div class="absolute top-2 right-2">
            <button class="p-2 rounded-full bg-white text-gray-700 hover:bg-pink-100 hover:text-pink-600 transition-colors duration-300">
              <i class="far fa-heart"></i>
            </button>
          </div>
          <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black to-transparent p-4">
            <span class="text-xs font-semibold text-white">Swedan</span>
          </div>
        </div>
        <div class="p-4">
          <div class="flex justify-between items-start">
            <div>
              <h3 class="text-sm font-medium text-gray-900">
                <a href="#">
                  <span aria-hidden="true" class="absolute inset-0"></span>
                  ETH Zurich
                </a>
              </h3>
              <p class="mt-1 text-sm text-gray-500">totally a year</p>
            </div>
            <p class="text-sm font-medium text-[#ab74ff]">27 000 CHF</p>
          </div>
          <div class="mt-4 flex space-x-2">
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">16-17</span>
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">18-20</span>
            <span class="inline-flex items-center px-2.5 py-0.5 rounded-full text-xs font-medium bg-[#ddceff] text-black">25+</span>
          </div>
          <div class="mt-4">
            <button class="w-full bg-violet-600 text-white py-2 px-4 rounded-md text-sm font-medium transition-colors duration-300">
              Get A Link
            </button>
          </div>
        </div>
      </div>

      <!-- Product 4 -->
    </div>

    <div class="mt-12 text-center">
      <button class="inline-flex items-center px-4 py-2 border border-gray-300 text-sm font-medium rounded-md text-gray-700 bg-white hover:bg-gray-50">
        View All UNIVERSITIES
        <i class="fas fa-arrow-right ml-2"></i>
      </button>
    </div>
  </div>

  <!-- Newsletter Section -->



  <!-- Shopping Cart Sidebar (hidden by default) -->
  <div class="fixed inset-0 overflow-hidden z-50 hidden" id="cart-sidebar">
    <div class="absolute inset-0 overflow-hidden">
      <div class="absolute inset-0 bg-gray-500 bg-opacity-75 transition-opacity" aria-hidden="true"></div>
      <div class="fixed inset-y-0 right-0 pl-10 max-w-full flex">
        <div class="w-screen max-w-md">
          <div class="h-full flex flex-col bg-white shadow-xl overflow-y-scroll">
            <div class="flex-1 py-6 overflow-y-auto px-4 sm:px-6">
              <div class="flex items-start justify-between">
                <h2 class="text-lg font-medium text-gray-900">Shopping cart</h2>
                <div class="ml-3 h-7 flex items-center">
                  <button type="button" class="-m-2 p-2 text-gray-400 hover:text-gray-500" id="close-cart">
                    <span class="sr-only">Close panel</span>
                    <i class="fas fa-times"></i>
                  </button>
                </div>
              </div>

              <div class="mt-8">
                <div class="flow-root">
                  <ul class="-my-6 divide-y divide-gray-200">
                    <li class="py-6 flex">
                      <div class="flex-shrink-0 w-24 h-24 border border-gray-200 rounded-md overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1581044777550-4cfa60707c03?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=686&q=80" alt="Floral Summer Dress" class="w-full h-full object-center object-cover">
                      </div>

                      <div class="ml-4 flex-1 flex flex-col">
                        <div>
                          <div class="flex justify-between text-base font-medium text-gray-900">
                            <h3>
                              Floral Summer Dress
                            </h3>
                            <p class="ml-4">
                              $39.99
                            </p>
                          </div>
                          <p class="mt-1 text-sm text-gray-500">
                            Women's Dress - Size M
                          </p>
                        </div>
                        <div class="flex-1 flex items-end justify-between text-sm">
                          <p class="text-gray-500">
                            Qty 1
                          </p>

                          <div class="flex">
                            <button type="button" class="font-medium text-pink-600 hover:text-pink-500">
                              Remove
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>

                    <li class="py-6 flex">
                      <div class="flex-shrink-0 w-24 h-24 border border-gray-200 rounded-md overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1549298916-b41d501d3772?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1112&q=80" alt="White Sneakers" class="w-full h-full object-center object-cover">
                      </div>

                      <div class="ml-4 flex-1 flex flex-col">
                        <div>
                          <div class="flex justify-between text-base font-medium text-gray-900">
                            <h3>
                              White Sneakers
                            </h3>
                            <p class="ml-4">
                              $49.99
                            </p>
                          </div>
                          <p class="mt-1 text-sm text-gray-500">
                            Women's Shoes - Size 7
                          </p>
                        </div>
                        <div class="flex-1 flex items-end justify-between text-sm">
                          <p class="text-gray-500">
                            Qty 1
                          </p>

                          <div class="flex">
                            <button type="button" class="font-medium text-pink-600 hover:text-pink-500">
                              Remove
                            </button>
                          </div>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
            </div>

            <div class="border-t border-gray-200 py-6 px-4 sm:px-6">
              <div class="flex justify-between text-base font-medium text-gray-900">
                <p>Subtotal</p>
                <p>$89.98</p>
              </div>
              <p class="mt-0.5 text-sm text-gray-500">Shipping and taxes calculated at checkout.</p>
              <div class="mt-6">
                <a href="#" class="flex justify-center items-center px-6 py-3 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-pink-600 hover:bg-pink-700">
                  Checkout
                </a>
              </div>
              <div class="mt-6 flex justify-center text-sm text-center text-gray-500">
                <p>
                  or
                  <button type="button" class="text-pink-600 font-medium hover:text-pink-500" id="continue-shopping">
                    Continue Shopping<span aria-hidden="true"> &rarr;</span>
                  </button>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<style scoped>

</style>