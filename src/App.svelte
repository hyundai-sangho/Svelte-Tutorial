<!-- <script>
  // import { onMount } from 'svelte';

  let name = 'world';
  let isRed = false;

  // onMount(() => {
  //   const box = document.querySelector('.box');
  //   box.addEventListener('click', () => {
  //     isRed = !isRed;
  //   });
  // });

  function enter() {
    name = 'enter';
  }

  function leave() {
    name = 'leave';
  }
</script>

<h1>Hello {name}!!</h1>
<div
  class="box"
  style="background-color:{isRed ? 'red' : 'orange'}"
  on:click={() => {
    isRed = !isRed;
  }}
  on:mouseenter={enter}
  on:mouseleave={leave}
>
  Box!
</div>

<style>
  .box {
    width: 300px;
    height: 150px;
    background: orange;
  }
</style> -->
<script>
  let text = '';
</script>

<h1>{text}</h1>

<input
  type="text"
  value={text}
  on:input={(e) => {
    text = e.target.value;
  }}
/>

<input type="text" bind:value={text} />

<button
  on:click={() => {
    text = 'cho';
  }}>클릭</button
>
