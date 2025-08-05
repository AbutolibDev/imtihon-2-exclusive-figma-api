<template>
    <div class="mx-auto w-[1400px] flex flex-col min-h-screen">

<main class="flex-grow">
  <div class="flex flex-row gap-[40px] m-auto  w-[1170px]">
    <aside class="w-56 border p-4 bg-white shadow-md w-[35%]">
      <ul class="space-y-3 text-sm font-medium text-gray-700">
        <li class="flex justify-between items-center hover:text-black cursor-pointer">
          Woman’s Fashion
          <span>➤</span>
        </li>
        <li class="flex justify-between items-center hover:text-black cursor-pointer">
          Men’s Fashion
          <span>➤</span>
        </li>
        <li class="hover:text-black cursor-pointer">Electronics</li>
        <li class="hover:text-black cursor-pointer">Home & Lifestyle</li>
        <li class="hover:text-black cursor-pointer">Medicine</li>
        <li class="hover:text-black cursor-pointer">Sports & Outdoor</li>
        <li class="hover:text-black cursor-pointer">Baby’s & Toys</li>
        <li class="hover:text-black cursor-pointer">Groceries & Pets</li>
        <li class="hover:text-black cursor-pointer">Health & Beauty</li>
      </ul>
    </aside>

    <section class="px-6 py-10 bg-black text-white flex flex-col md:flex-row items-center justify-between mr-[80px]">
      <div>
        <div class="flex flex-row gap-6  w-[250px] h-[60px] items-center ">
          <img src="../apple.png" class="w-[40px] h-[49px] ">
          <h2 class="text-lg mb-2 font-semibold">iPhone 14 Series</h2>
        </div>
        <h1 class="text-[50px] font-bold mb-4">Up to 10% off Voucher</h1>
        <a href="#" class="inline-flex items-center space-x-1 text-blue-400 hover:underline">
          <span class="text-[15px]">Shop Now</span>
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path d="M17 8l4 4m0 0l-4 4m4-4H3"></path>
          </svg>
        </a>
      </div>
      <ul class="w-[50%] h-[100%]  ">
        <img src="../iphone.png" class="w-[85] h-[85%]">
      </ul>
    </section>
  </div>

  <section class="px-6 py-10 bg-white flex flex-col gap-10  w-[1170px] m-auto">


    <div class="w-full  py-2  items-center">

      <div class="flex flex-col md:flex-row justify-between items-center gap-4">

        <div class="flex  space-x-4 flex-col  w-[30%] h-[100%] ">

          <div class="flex space-x-2 items-center">
            <div class="w-3 h-9 bg-red-500 rounded "></div>
            <span class="text-red-500 text-sm font-semibold">Today’s</span>
          </div>

          <h2 class="text-2xl md:text-3xl font-bold text-gray-900">Most Sales</h2>
        </div>


        <div class="flex space-x-4 text-center text-sm md:text-base text-gray-700  h-[100%] w-[35%] mt-[32px]">
          <div>
            <p class="text-xs">Days</p>
            <p class="font-bold   text-3xl text-black">03</p>
          </div>
          <span class="text-red-400">:</span>
          <div>
            <p class="text-xs">Hours</p>
            <p class="font-bold text-3xl text-black">03</p>
          </div>
          <span class="text-red-400">:</span>
          <div>
            <p class="text-xs">Minutes</p>
            <p class="font-bold  text-3xl text-black">19</p>
          </div>
          <span class="text-red-400">:</span>
          <div>
            <p class="text-xs">Seconds</p>
            <p class="font-bold text-3xl text-black">56</p>
          </div>
        </div>


        <div class="flex items-center space-x-2 mt-[32px]">
          <button class="w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 flex items-center justify-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 text-gray-700" fill="none" viewBox="0 0 24 24"
              stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
            </svg>
          </button>
          <button class="w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 flex items-center justify-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 text-gray-700" fill="none" viewBox="0 0 24 24"
              stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
            </svg>
          </button>
        </div>
      </div>

    </div>


    <div class="flex overflow-x-auto space-x-4 pb-4 scrollbar-thin scrollbar-thumb-gray-300 ">

      <div class="min-w-[200px] flex-shrink-0 border rounded-lg p-4 bg-white hover:shadow-md transition relative">
        <span class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">-40%</span>
        <img src="../imgs/jossi.png" alt="Gamepad" class="w-full h-32 object-contain mb-2">
        <h3 class="text-sm font-medium">HAVIT HV-G92 Gamepad</h3>
        <div class="flex items-center space-x-2 mt-1">
          <span class="text-red-500 font-bold">$120</span>
          <span class="line-through text-gray-400 text-sm">$160</span>
        </div>
        <div class="flex items-center mt-1 text-yellow-400 text-sm">
          ★★★★☆ <span class="text-gray-500 ml-1">(88)</span>
        </div>
      </div>


      <div class="min-w-[200px] flex-shrink-0 border rounded-lg p-4 bg-white hover:shadow-md transition relative">
        <span class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">-35%</span>
        <img src="../imgs/clavish.png" alt="Keyboard" class="w-full h-32 object-contain mb-2">
        <h3 class="text-sm font-medium">AK-900 Wired Keyboard</h3>
        <div class="flex items-center space-x-2 mt-1">
          <span class="text-red-500 font-bold">$960</span>
          <span class="line-through text-gray-400 text-sm">$1160</span>
        </div>
        <div class="flex items-center mt-1 text-yellow-400 text-sm">
          ★★★★☆ <span class="text-gray-500 ml-1">(75)</span>
        </div>
      </div>

      <div class="min-w-[200px] flex-shrink-0 border rounded-lg p-4 bg-white hover:shadow-md transition relative">
        <span class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">-30%</span>
        <img src="../imgs/televizor.png" alt="Keyboard" class="w-full h-32 object-contain mb-2">
        <h3 class="text-sm font-medium">IPS LCD Gaming Monitor</h3>
        <div class="flex items-center space-x-2 mt-1">
          <span class="text-red-500 font-bold">$370</span>
          <span class="line-through text-gray-400 text-sm">$400</span>
        </div>
        <div class="flex items-center mt-1 text-yellow-400 text-sm">
          ★★★★☆ <span class="text-gray-500 ml-1">(99)</span>
        </div>
      </div>

      <div class="min-w-[200px] flex-shrink-0 border rounded-lg p-4 bg-white hover:shadow-md transition relative">
        <span class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">-30%</span>
        <img src="../imgs/stul.png" alt="Keyboard" class="w-full h-32 object-contain mb-2">
        <h3 class="text-sm font-medium">S-Series Comfort Chair </h3>
        <div class="flex items-center space-x-2 mt-1">
          <span class="text-red-500 font-bold">$375</span>
          <span class="line-through text-gray-400 text-sm">$400</span>
        </div>
        <div class="flex items-center mt-1 text-yellow-400 text-sm">
          ★★★★☆ <span class="text-gray-500 ml-1">(99)</span>
        </div>
      </div>

      <div class="min-w-[200px] flex-shrink-0 border rounded-lg p-4 bg-white hover:shadow-md transition relative">
        <span class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">-30%</span>
        <img src="../imgs/stul.png" alt="Keyboard" class="w-full h-32 object-contain mb-2">
        <h3 class="text-sm font-medium">S-Series Comfort Chair </h3>
        <div class="flex items-center space-x-2 mt-1">
          <span class="text-red-500 font-bold">$375</span>
          <span class="line-through text-gray-400 text-sm">$400</span>
        </div>
        <div class="flex items-center mt-1 text-yellow-400 text-sm">
          ★★★★☆ <span class="text-gray-500 ml-1">(99)</span>
        </div>
      </div>

      <div class="min-w-[200px] flex-shrink-0 border rounded-lg p-4 bg-white hover:shadow-md transition relative">
        <span class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">-30%</span>
        <img src="../imgs/stul.png" alt="Keyboard" class="w-full h-32 object-contain mb-2">
        <h3 class="text-sm font-medium">S-Series Comfort Chair </h3>
        <div class="flex items-center space-x-2 mt-1">
          <span class="text-red-500 font-bold">$375</span>
          <span class="line-through text-gray-400 text-sm">$400</span>
        </div>
        <div class="flex items-center mt-1 text-yellow-400 text-sm">
          ★★★★☆ <span class="text-gray-500 ml-1">(99)</span>
        </div>
      </div>

    </div>

    <div class="text-center mt-6">
      <button class="bg-red-500 text-white px-6 py-2 rounded hover:bg-red-600 transition">
        View All Products
      </button>
    </div>
  </section>

  <div class="p-4 bg-white border-b-2 border-blue-500 m-auto  w-[1170px]">

    <div class="flex  flex-row items-center justify-between mb-4 ">
      <div class="flex space-x-2 flex-col gap-3">
        <ul class="flex flex-row items-center gap-3">
          <div class="w-3 h-9 bg-red-500 rounded "></div>
          <span class="text-red-500 text-xs font-semibold">Catigories</span>
        </ul>
        <h2 class="text-xl font-bold ">Browse By Category</h2>
      </div>
      <div class="flex space-x-2  mt-6">
        <button class="w-8 h-8 flex items-center justify-center bg-gray-100 rounded-full hover:bg-gray-200">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7" />
          </svg>
        </button>
        <button class="w-8 h-8 flex items-center justify-center bg-gray-100 rounded-full hover:bg-gray-200">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
          </svg>
        </button>
      </div>
    </div>


    <div class="flex space-x-4 overflow-x-auto">

      <div
        class="flex flex-col items-center justify-center w-[190px] h-[155px] border rounded hover:shadow cursor-pointer">
        <img src="https://img.icons8.com/ios/50/000000/smartphone.png" alt="Phones" class="w-6 h-6 mb-2">
        <span class="text-sm">Phones</span>
      </div>

      <div
        class="flex flex-col items-center justify-center  w-[190px] h-[155px] border rounded hover:shadow cursor-pointer">
        <img src="https://img.icons8.com/ios/50/000000/monitor.png" alt="Computers" class="w-6 h-6 mb-2">
        <span class="text-sm">Computers</span>
      </div>

      <div
        class="flex flex-col items-center justify-center w-[190px] h-[155px] border rounded hover:shadow cursor-pointer">
        <img src="../imgs/soat.png" alt="SmartWatch" class="w-6 h-6 mb-2">
        <span class="text-sm">SmartWatch</span>
      </div>


      <div
        class="flex flex-col items-center justify-center  w-[190px] h-[155px] rounded bg-red-500 text-white cursor-pointer">
        <img src="https://img.icons8.com/ios/50/ffffff/camera.png" alt="Camera" class="w-6 h-6 mb-2">
        <span class="text-sm">Camera</span>
      </div>

      <div
        class="flex flex-col items-center justify-center w-[190px] h-[155px] border rounded hover:shadow cursor-pointer">
        <img src="https://img.icons8.com/ios/50/000000/headphones.png" alt="Headphones" class="w-6 h-6 mb-2">
        <span class="text-sm">HeadPhones</span>
      </div>

      <div
        class="flex flex-col items-center justify-center  w-[190px] h-[155px] border rounded hover:shadow cursor-pointer">
        <img src="https://img.icons8.com/ios/50/000000/controller.png" alt="Gaming" class="w-6 h-6 mb-2">
        <span class="text-sm">Gaming</span>
      </div>
    </div>
  </div>


  <div class="max-w-7xl mx-auto px-4 py-6 gap-10 flex flex-col w-[1170px] mt-10 ">
    <div class="flex items-center justify-between mb-6 ">
      <div class="flex gap-3 flex-col">
        <ul class="flex flex-row items-center gap-3">
          <div class="w-3 h-9 bg-red-500 rounded "></div>
          <span class="text-sm text-red-500 font-medium">This Month</span>
        </ul>
        <h2 class="text-2xl font-bold text-gray-800">Best Selling Products</h2>
      </div>
      <ul class="flex mt-10">
        <button class="bg-red-500 text-white  text-sm px-4 py-2 rounded-md hover:bg-red-600">View All</button>
      </ul>
    </div>

    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">

      <div class="border rounded-lg p-4 relative group">
        <img src="../kurtka.png" alt="The north coat" class="w-full h-40 object-contain mb-4" />
        <h3 class="font-medium text-gray-700">The north coat</h3>
        <div class="flex items-center gap-2 my-2">
          <span class="text-red-500 font-bold">$260</span>
          <span class="text-gray-400 line-through">$360</span>
        </div>
        <div class="text-yellow-400 text-sm">★★★★★ <span class="text-gray-500">(65)</span></div>
        <div class="absolute top-2 right-2 flex flex-col gap-2 opacity-0 group-hover:opacity-100 transition-opacity">
          <button class="bg-white rounded-full p-1 shadow"><span>&#9829;</span></button>
          <button class="bg-white rounded-full p-1 shadow"><span>&#128065;</span></button>
        </div>
      </div>

      <div class="border rounded-lg p-4 relative group">
        <img src="../imgs/gucci.png" alt="Gucci duffle bag" class="w-full h-40 object-contain mb-4" />
        <h3 class="font-medium text-gray-700">Gucci duffle bag</h3>
        <div class="flex items-center gap-2 my-2">
          <span class="text-red-500 font-bold">$960</span>
          <span class="text-gray-400 line-through">$1160</span>
        </div>
        <div class="text-yellow-400 text-sm">★★★★★ <span class="text-gray-500">(65)</span></div>
        <div class="absolute top-2 right-2 flex flex-col gap-2 opacity-0 group-hover:opacity-100 transition-opacity">
          <button class="bg-white rounded-full p-1 shadow"><span>&#9829;</span></button>
          <button class="bg-white rounded-full p-1 shadow"><span>&#128065;</span></button>
        </div>
      </div>

      <div class="border rounded-lg p-4 relative group">
        <img src="../imgs/magnitafon.png" alt="RGB liquid CPU Cooler" class="w-full h-40 object-contain mb-4" />
        <h3 class="font-medium text-gray-700">RGB liquid CPU Cooler</h3>
        <div class="flex items-center gap-2 my-2">
          <span class="text-red-500 font-bold">$160</span>
          <span class="text-gray-400 line-through">$170</span>
        </div>
        <div class="text-yellow-400 text-sm">★★★★★ <span class="text-gray-500">(65)</span></div>
        <div class="absolute top-2 right-2 flex flex-col gap-2 opacity-0 group-hover:opacity-100 transition-opacity">
          <button class="bg-white rounded-full p-1 shadow"><span>&#9829;</span></button>
          <button class="bg-white rounded-full p-1 shadow"><span>&#128065;</span></button>
        </div>
      </div>

      <div class="border rounded-lg p-4 relative group">
        <img src="../imgs/shkaf.png" alt="Small BookSelf" class="w-full h-40 object-contain mb-4" />
        <h3 class="font-medium text-gray-700">Small BookSelf</h3>
        <div class="flex items-center gap-2 my-2">
          <span class="text-red-500 font-bold">$360</span>
        </div>
        <div class="text-yellow-400 text-sm">★★★★★ <span class="text-gray-500">(65)</span></div>
        <div class="absolute top-2 right-2 flex flex-col gap-2 opacity-0 group-hover:opacity-100 transition-opacity">
          <button class="bg-white rounded-full p-1 shadow"><span>&#9829;</span></button>
          <button class="bg-white rounded-full p-1 shadow"><span>&#128065;</span></button>
        </div>
      </div>
    </div>
  </div>


  <div
    class="bg-gradient-to-r w-[1170px] m-auto h-[400px] mt-10 from-black to-gray-900 text-white rounded-lg overflow-hidden p-6 flex 
    flex-col lg:flex-row items-center justify-between gap-8">

    <div class="flex-1 text-center lg:text-left gap-10 flex flex-col">
      <p class="text-sm text-green-400 font-semibold mb-2">Categories</p>
      <h2 class="text-3xl font-bold leading-tight mb-4">Enhance Your <br />Music Experience</h2>

      <div class="flex justify-center lg:justify-start gap-4 mb-6">
        <div class="bg-white text-black rounded-full px-4 py-2 text-sm font-semibold text-center">
          <p>23</p>
          <p class="text-xs">Hours</p>
        </div>
        <div class="bg-white text-black rounded-full px-4 py-2 text-sm font-semibold text-center">
          <p>05</p>
          <p class="text-xs">Days</p>
        </div>
        <div class="bg-white text-black rounded-full px-4 py-2 text-sm font-semibold text-center">
          <p>59</p>
          <p class="text-xs">Minutes</p>
        </div>
        <div class="bg-white text-black rounded-full px-4 py-2 text-sm font-semibold text-center">
          <p>35</p>
          <p class="text-xs">Seconds</p>
        </div>
      </div>

      <button class="bg-green-500 hover:bg-green-600 w-[170px] text-white px-6 py-2 rounded-md text-sm font-semibold">Buy
        Now!</button>
    </div>

    <div class="flex-1">
      <img src="../imgs/caloncka.png" alt="JBL Speaker"
        class="w-full h-auto object-contain" />
    </div>
  </div>

    
  <section class="px-4 flex m-auto flex-col w-[1200px]  md:px-8 py-8 mt-10">
    <ul class="flex flex-row items-center gap-3">
     <div class="w-3 h-9 bg-red-500 rounded "></div>
  <p class="text-red-500 text-sm font-medium mb-1">Our Products</p>
  </ul>
  <h2 class="text-2xl md:text-3xl font-semibold mb-6">Explore Our Products</h2>

  <div class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
   
    <div class="border flex flex-col  h-[280px] rounded-lg p-3 hover:shadow">
      <img src="../imgs/dogs food.png" alt="Dog Food" class="w-full h-40 object-contain">
      <h3 class="mt-3 text-sm font-medium">Breed Dry Dog Food</h3>
      <div class="text-red-500 font-semibold text-sm">$100</div>
      <div class="text-xs text-gray-500">(35)</div>
    </div>

    
    <div class="border h-[280px] rounded-lg p-3 hover:shadow">
      <img src="../imgs/photo.png" alt="Camera" class="w-full h-40 object-contain">
       <button class="w-full mt-2 bg-black text-white text-sm py-1.5 rounded">Add To Cart</button>
      <h3 class="mt-3 text-sm font-medium">CANON EOS DSLR Camera</h3>
      <div class="text-red-500 font-semibold text-sm">$360</div>
      <div class="text-xs text-gray-500">(95)</div>
     
    </div>

    <div class="border rounded-lg p-3 hover:shadow">
      <img src="../imgs/note book.png" alt="Laptop" class="w-full h-40 object-contain">
      <h3 class="mt-3 text-sm font-medium">ASUS FHD Gaming Laptop</h3>
      <div class="text-red-500 font-semibold text-sm">$700</div>
      <div class="text-xs text-gray-500">(325)</div>
    </div>

   
    <div class="border rounded-lg p-3 hover:shadow">
      <img src="../imgs/krem.png" alt="Curology Set" class="w-full h-40 object-contain">
      <h3 class="mt-3 text-sm font-medium">Curology Product Set</h3>
      <div class="text-red-500 font-semibold text-sm">$500</div>
      <div class="text-xs text-gray-500">(145)</div>
    </div>

  
    <div class="border rounded-lg p-3 relative hover:shadow">
      <span class="absolute top-2 left-2 bg-green-500 text-white text-xs px-2 py-0.5 rounded-full">NEW</span>
      <img src="../imgs/yoyo.png" alt="Kids Car" class="w-full h-40 object-contain">
      <h3 class="mt-3 text-sm font-medium">Kids Electric Car</h3>
      <div class="text-red-500 font-semibold text-sm">$960</div>
      <div class="text-xs text-gray-500">(65)</div>
    </div>

  
    <div class="border rounded-lg p-3 hover:shadow">
      <img src="../imgs/keta.png" alt="Soccer Cleats" class="w-full h-40 object-contain">
      <h3 class="mt-3 text-sm font-medium">Jr. Zoom Soccer Cleats</h3>
      <div class="text-red-500 font-semibold text-sm">$1160</div>
      <div class="text-xs text-gray-500">(35)</div>
    </div>

    
    <div class="border rounded-lg p-3 relative hover:shadow">
      <span class="absolute top-2 left-2 bg-green-500 text-white text-xs px-2 py-0.5 rounded-full">NEW</span>
      <img src="../imgs/jossi two.png" alt="Gamepad" class="w-full h-40 object-contain">
      <h3 class="mt-3 text-sm font-medium">GP11 Shooter USB Gamepad</h3>
      <div class="text-red-500 font-semibold text-sm">$660</div>
      <div class="text-xs text-gray-500">(55)</div>
    </div>

    
    <div class="border rounded-lg p-3 hover:shadow">
      <img src="../imgs/jacket.png" alt="Jacket" class="w-full h-40 object-contain">
      <h3 class="mt-3 text-sm font-medium">Quilted Satin Jacket</h3>
      <div class="text-red-500 font-semibold text-sm">$660</div>
      <div class="text-xs text-gray-500">(55)</div>
    </div>
  </div>

  <div class="flex justify-center mt-10">
    <button class="bg-red-500 text-white text-sm font-medium px-5 py-2 rounded hover:bg-red-600 transition">View All Products</button>
  </div>
</section>


<section class="px-4 md:px-8 py-10 w-[1170px] m-auto mt-4">
  <p class="text-red-500 text-sm font-medium mb-1">Featured</p>
  <h2 class="text-2xl md:text-3xl font-semibold mb-6">New Arrival</h2>

  <div class="grid grid-cols-1 lg:grid-cols-4 lg:grid-rows-2 gap-6">
   
    <div class="relative bg-black rounded-lg overflow-hidden lg:col-span-2 lg:row-span-2 h-[600px]">
      <img src="../imgs/modems.png" alt="PlayStation 5" class="w-full h-full object-cover opacity-80">
      <div class="absolute bottom-4 left-4 text-white flex flex-col gap-3 ">
        <h3 class="text-lg font-semibold">PlayStation 5</h3>
        <p class="text-sm">Black and White version of the PS5 coming out on sale.</p>
        <button class="mt-2 px-4 py-1.5 bg-white text-black text-sm font-medium w-[100px] rounded">Shop Now</button>
      </div>
    </div>

    
    <div class="relative bg-black rounded-lg overflow-hidden lg:col-span-2 h-[280px]">
      <img src="../imgs/women.png" alt="Women's Collections" class="w-full h-full object-cover opacity-80">
      <div class="absolute bottom-4 left-4 text-white flex flex-col gap-4 w-[50%]">
        <h3 class="text-base font-semibold">Women’s Collections</h3>
        <p class="text-sm">Featured woman collections that give you another vibe.</p>
        <button class="mt-2 px-3 py-1 bg-white text-black  w-[100px] text-sm rounded">Shop Now</button>
      </div>
    </div>

    
    <div class="relative bg-black rounded-lg overflow-hidden h-[290px] flex flex-col items-center justify-center ">
      <img src="../imgs/caloncas.png" alt="Speakers" class="w-[80%] h-[80%] object-cover opacity-80">
      <div class="absolute bottom-4 left-4 text-white">
        <h3 class="text-base font-semibold">Speakers</h3>
        <p class="text-sm">Amazon wireless speakers</p>
        <button class="mt-2 px-3 py-1 bg-white text-black text-sm rounded">Shop Now</button>
      </div>
    </div>

    
    <div class="relative bg-black rounded-lg overflow-hidden flex flex-col items-center justify-center">
      <img src="../imgs/duhi.png" alt="Perfume" class="w-[80%] h-[80%] object-cover opacity-80">
      <div class="absolute bottom-4 left-4 text-white">
        <h3 class="text-base font-semibold">Perfume</h3>
        <p class="text-sm">GUCCI INTENSE OUD EDP</p>
        <button class="mt-2 px-3 py-1 bg-white text-black text-sm rounded">Shop Now</button>
      </div>
    </div>
  </div>
</section>

<div class="max-w-6xl mx-auto px-4 py-6 mt-8">
  <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6 text-center">
  
    <div class=" p-4 rounded-lg flex flex-col items-center space-y-2">
      <div class="bg-black text-white p-3 rounded-full">
        <img src="../imgs/kamaz.png" class="h-12 w-12">
        
      </div>
      <h3 class="font-bold text-sm">FREE AND FAST DELIVERY:</h3>
      <p class="text-xs text-gray-700">Free delivery for all orders over $140</p>
    </div>

    
    <div class=" p-4 rounded-lg flex flex-col items-center space-y-2">
      <div class="bg-black text-white p-3 rounded-full">
         <img src="../imgs/naushnik.png" class="h-12 w-12">
      
      </div>
      <h3 class="font-bold text-sm">24/7 CUSTOMER SERVICE:</h3>
      <p class="text-xs text-gray-700">Friendly 24/7 customer support</p>
    </div>

   
    <div class=" p-4 rounded-lg flex flex-col items-center space-y-2">
      <div class="bg-black text-white p-3 rounded-full">
         <img src="../imgs/ptichka.png" class="h-12 w-12">
       
      </div>
      <h3 class="font-bold text-sm">MONEY BACK GUARANTEE:</h3>
      <p class="text-xs text-gray-700">We return money within 30 days</p>
    </div>
    
  </div>
</div>
</main>

    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>
