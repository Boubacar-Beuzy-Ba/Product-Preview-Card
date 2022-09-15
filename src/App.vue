<script setup>
</script>

<template>
  <main>
  <div class="max-w-sm w-full lg:max-w-3xl sm:flex bg-white rounded-3xl overflow-hidden shadow-lg">
      <img src="../src/assets/image-product-desktop.jpg" alt="Product" class="invisible md:visible sm:invisible hidden md:block sm:hidden rounded-t md:rounded-l-3xl w-full md:w-1/2">
      <img src="../src/assets/image-product-mobile.jpg" alt="Product" class="visible md:invisible sm:visible block md:hidden sm:block rounded-t md:rounded-l-3xl w-full md:w-1/2">
    <div class="mx-3 p-4">
      <h3 class="text-xl text-gray-500 uppercase tracking-widest">perfume</h3>
      <h1 class="text-3xl text-black my-9 capitalize">Gabrielle Essence Eau De Parfum</h1>
      <p class="text-md text-gray-600 my-9 text-base"> A floral, solar and voluptuous interpretation composed by Olivier Polge, Perfurmer-Creator for the House of CHANEL</p>
      <div class="mx-3 my-9 flex justify-arround items-center">
        <span class="text-3xl  price font-semibold">$149.99</span>
        <span class="text-sm text-gray-700 mx-12 line-through">$169.99</span>
      </div>
      <button class="mx-auto my-9 flex justify-center items-center rounded-xl w-full h-12 text-white shadow-lg btn">
        <span>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 00-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 00-16.536-1.84M7.5 14.25L5.106 5.272M6 20.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm12.75 0a.75.75 0 11-1.5 0 .75.75 0 011.5 0z" />
          </svg></span>
        <span class="text-center text-xl font-semibold">Add to Cart</span>
        </button>
    </div>
  </div>
  </main>
</template>

<style>
.price {
  color: hsl(158, 36%, 37%);
}
.btn {
  background-color: hsl(158, 36%, 37%);
}
:active.btn {
  background-color: hsl(158, 62%, 17%);
}
</style>
