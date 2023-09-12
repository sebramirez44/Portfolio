<script lang="ts">
    let count = 0;
    console.log(count);
</script>  
<h1>Counter: {count}</h1>
<button on:click={() => count+=1}>Increase</button>
<button on:click={() => count-=1}>Decrease</button>