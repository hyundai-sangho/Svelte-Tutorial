<!-- <script>
  let name = 'world';
  let toggle = false;
</script>

<button
  on:click={() => {
    toggle = !toggle;
  }}>Toggle</button
>

{#if toggle}
  <h1>Hello {name}!</h1>
{:else}
  <div>No name!!</div>
{/if} -->
<script>
  let name = 'Fruits';
  let fruits = ['Apple', 'Banana', 'Cherry', 'Orange', 'Mango'];

  function deleteFruit() {
    fruits = fruits.slice(1);
  }
</script>

<h1>Hello {name}!</h1>
<ul>
  {#each fruits as fruit}
    <li>{fruit}</li>
  {/each}
</ul>

<button on:click={deleteFruit}>Eat it!!</button>
