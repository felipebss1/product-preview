<template>
  <main
    class="md:flex max-w-[375px] md:max-w-[590px] w-11/12 mx-auto rounded-lg bg-white"
  >
    <figure>
      <img
        src="./assets/images/image-product-mobile.jpg"
        alt="perfume picture"
        class="rounded-t-lg md:hidden"
      />
      <img
        src="./assets/images/image-product-desktop.jpg"
        alt="perfume picture"
        class="hidden md:flex rounded-l-lg pr-6"
      />
    </figure>
    <div class="w-10/12 mx-auto">
      <p
        class="tracking-[0.25rem] mt-5 text-[#6c7289] text-sm font-medium font-['Montserrat']"
      >
        PERFUME
      </p>
      <p class="my-3 text-[#1c232b] text-3xl font-bold font-['Fraunces']">
        Gabrielle Essence Eau De Parfum
      </p>
      <p class="text-[#6c7289] text-[0.98rem] md:text-[1.07rem]">
        A floral, solar and voluptuous interpretation composed by Olivier Polge,
        Perfumer-Creator for the House of CHANEL.
      </p>
      <div class="flex mt-10">
        <span class="font-['Fraunces'] text-3xl pr-4 text-[#3c8067] font-bold"
          >$149.99</span
        >
        <span class="flex items-center line-through text-[#6c7289]"
          >$169.99</span
        >
      </div>
      <button
        type="button"
        class="flex items-center py-4 md:py-3 w-full md:w-11/12 justify-center text-white my-5 bg-[#3c8067] rounded-lg font-['Montserrat'] text-sm hover:bg-[#1a4031] hover:rounded-lg"
      >
        <img class="pr-3" src="./assets/images/icon-cart.svg" alt="cart icon" />
        Add to Cart
      </button>
    </div>
  </main>
  <footer>
    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="https://github.com/felipebss1">Bruno Soares</a>.
    </div>
  </footer>
</template>
<style scoped>
.attribution {
  font-size: 11px;
  text-align: center;
}

.attribution a {
  color: hsl(228, 45%, 44%);
}
</style>
