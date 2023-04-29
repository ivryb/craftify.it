<template>
  <AppLandingNavbar/>
  <!-- Hero -->
  <div class="bg-base-200 py-24">
    <div class="container px-8 text-center">
      <h1 class="text-5xl font-bold">
        Create and publish your new website<br>with just a single phrase!
      </h1>
      <p class="py-10 max-w-3xl mx-auto text-lg">
        Yes, it's that simple! You don't need designers, programmers, or copywriters to share your project with the world.
      </p>

      <div class="mx-auto max-w-md">
        <textarea
          class="textarea textarea-bordered textarea-lg w-full block"
          placeholder="What do you need a website for?"
        />
        <button class="btn btn-primary btn-lg btn-block mt-3">Craftify IT!</button>
      </div>
    </div>
  </div>

  <div class="bg-base py-24">
    <div class="container px-8">
      <h1 class="text-5xl font-bold">
        Section with items
      </h1>
      <p class="py-10 text-lg">
        Yes, it's that simple! You don't need designers, programmers, or copywriters to share your project with the world.
      </p>
      <div>
        <div class="card w-96 bg-base-100 shadow-xl">
          <figure><img src="/images/stock/photo-1606107557195-0e29a4b5b4aa.jpg" alt="Shoes" /></figure>
          <div class="card-body">
            <h2 class="card-title">Shoes!</h2>
            <p>If a dog chews shoes whose shoes does he choose?</p>
            <div class="card-actions justify-end">
              <button class="btn btn-primary">Buy Now</button>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>
