<script>
  let name = 'world';
  let age = 85;

  function assign() {
    name = 'cho';
    age = 990;
  }
</script>

<h1>Hello {name}</h1>
<h2 class={age < 85 ? 'active' : ''}>{age}</h2>

<img src="" alt={name} />

<!-- 양방향 바인딩은 bind: 을 붙인다. -->
<input type="text" bind:value={name} />
<button on:click={assign}>Assign</button>

<style>
  h1 {
    color: red;
  }

  .active {
    color: blue;
  }
</style>
