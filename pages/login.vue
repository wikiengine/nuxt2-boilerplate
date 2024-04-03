<template>
  <div class="pt-20">
    <div
      class="flex flex-col mx-auto justify-center self-center max-w-2xl p-6 gap-y-4"
    >
      <b-card
        title=""
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        tag="article"
        class="mb-2"
      >
        <div>
          <label for="email" class="font-bold">Email</label>
          <input
            name="email"
            type="text"
            class="border-2 rounded w-full px-2 py-1"
          />
        </div>

        <div>
          <label for="password" class="font-bold">Password</label>
          <input
            name="password"
            type="password"
            class="border-2 rounded w-full px-2 py-1"
          />
        </div>
        <div class="float-right mt-10">
          <b-button href="#" variant="success">Login</b-button>
        </div>
      </b-card>
    </div>
  </div>
</template>

<script>
export default {};
</script>
