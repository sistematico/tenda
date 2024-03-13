<script lang="ts">
	import { Icons } from '$lib/components/icons'
</script>

<main class="flex flex-col h-screen">
  <div class="w-full sm:w-1/2 lg:w-1/3 m-auto">
    <div class="flex flex-col items-center rounded-xl shadow-md p-5">
      <img class="object-scale-down h-48" src="/img/tenda.jpg" alt="Tenda" />
      <!-- <h1 class="text-3xl font-bold underline"> Gaming</h1> -->
      <div class="neon">
        <span>Tenda</span>
        <span>Gaming</span>
      </div>
      <div class="flex">
        <a href="https://wp.tendagaming.com.br" target="_blank">
          <Icons name={'whatsapp'} />
        </a>
        <a href="https://dc.tendagaming.com.br" target="_blank">
          <Icons name={'discord'} />
        </a>
        <a href="https://fb.tendagaming.com.br" target="_blank">
          <Icons name={'facebook'} />
        </a>
      </div>
    </div>
  </div>
</main>

<style>
  main > div > div {
    background-color: rgba(0, 0, 0, 0.61);
    backdrop-filter: blur(5px);
  }
</style>
