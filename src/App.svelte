<script>
  import { onMount } from 'svelte'
  import { createScene } from './lib/scene'

  let el;
  
  onMount(() => {
    createScene(el);
  });

</script>

<canvas bind:this={el}></canvas>