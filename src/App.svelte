<script>
  import Tailwindcss from './tailwindcss.svelte';
  import Icon from '@iconify/svelte';

  const image = 'https://picsum.photos/600/400';
</script>

<Tailwindcss />

<main>
  <div class="bg-slate-950 h-screen text-white">
    <div class="p-10 flex justify-center">
      <div class="border-white border-4 w-auto p-5 rounded-sm flex flex-col gap-4">
        <div class="border-white border-4 w-auto p-0 rounded-sm">
          <img src={image} alt="">
        </div>
        <div class="border-white border-4 w-auto p-2 rounded-sm flex flex-row gap-2">
          <div class="active:border-white active:border-4 p-1 border-transparent border-4">
            <Icon icon="line-md:pencil-twotone" width={40} height={40} />
          </div>
          <div class="active:border-white active:border-4 p-1 border-transparent border-4">
            <Icon icon="line-md:pencil-twotone" width={40} height={40} />
          </div>
          <div class="active:border-white active:border-4 p-1 border-transparent border-4">
            <Icon icon="line-md:pencil-twotone" width={40} height={40} />
          </div>
        </div>
      </div>
    </div>
  </div>
</main>

<style global>
  
</style>