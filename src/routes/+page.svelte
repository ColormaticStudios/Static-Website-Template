<script lang="ts">
  let count = $state(0);
</script>

<main>
  <h1 class="mt-[10%] w-full text-center text-4xl font-bold text-indigo-700">
    Welcome to your new static Vite+SvelteKit+Tailwind+Sass website!
  </h1>

  <div
    class="mx-auto mt-[15%] w-fit rounded-xl border border-slate-300 bg-slate-100 px-6 py-4 shadow-lg"
  >
    <button
      class="mx-auto cursor-pointer rounded-lg border border-blue-700 bg-blue-600 px-4 py-2 text-white shadow-md duration-150 hover:border-blue-800 hover:bg-blue-700 hover:shadow-lg"
      onclick={() => {
        count++;
      }}
    >
      Click me!
    </button>
    <br />
    <p class="w-full pt-3 text-center">
      {count} clicks
    </p>
  </div>
</main>
