<template>
    <div>

                    <div class="text-sm text-gray-500 mb-4 w-[1170px] m-auto">
  <a href="#" class="text-gray-400">Home</a> / <span class="font-bold text-black">Contact</span>
</div>

    <section class=" p-10 gap-[30px] flex w-[1170px] m-auto flex-col md:flex-row items-start bg-white shadow-md  mt-6">

        <div class="flex flex-col gap-6 md:w-1/3 p-4">
            <div class="flex flex-col gap-4 ">
                <h3 class="flex items-center text-red-600 font-semibold mb-2">
                    <span
                        class="w-8 h-8 bg-red-600 rounded-full flex items-center justify-center text-white mr-2">📞</span>
                    Call To Us
                </h3>
                <p class="text-gray-600">We are available 24/7, 7 days a week.</p>
                <p class="text-gray-600">Phone: +880111222</p>
            </div>
            <hr class="border">
            <div class="flex flex-col gap-4 ">
                <h3 class="flex items-center text-red-600 font-semibold mb-2">
                    <span
                        class="w-8 h-8 bg-red-600 rounded-full flex items-center justify-center text-white mr-2">✉️</span>
                    Write To Us
                </h3>
                <p class="text-gray-600">Fill out our form and we will contact you within 24 hours.</p>
                <p class="text-gray-600">Emails: customer@exclusive.com</p>
                <p class="text-gray-600">Emails: support@exclusive.com</p>
            </div>
        </div>


        <div class="md:w-2/3 p-4">
            <form class="space-y-4">
                <div class="flex flex-col md:flex-row space-y-4 md:space-y-0 md:space-x-4">
                    <input type="text" placeholder="Your Name *"
                        class="w-full md:w-1/3 p-2 border border-gray-300 rounded bg-gray-50 focus:outline-none focus:ring-2 focus:ring-red-500">
                    <input type="email" placeholder="Your Email *"
                        class="w-full md:w-1/3 p-2 border border-gray-300 rounded bg-gray-50 focus:outline-none focus:ring-2 focus:ring-red-500">
                    <input type="text" placeholder="Your Phone *"
                        class="w-full md:w-1/3 p-2 border border-gray-300 rounded bg-gray-50 focus:outline-none focus:ring-2 focus:ring-red-500">
                </div>
                <textarea placeholder="Your Message" class="w-full h-40 p-2 border border-gray-300 rounded bg-gray-50
                 focus:outline-none focus:ring-2 focus:ring-red-500"></textarea>
                <div class="flex w-full justify-end">
                    <button type="submit" class="w-full  md:w-auto px-6 py-2 bg-red-600 text-white rounded hover:bg-red-700
                 transition duration-300">Send Message</button>
                </div>
            </form>
        </div>
    </section>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>