<script>
    let myvariable = $state(false);

    function changeState() {
        myvariable = !myvariable;
    }
</script>

{#if myvariable}
  <p>yes it's true</p>
{:else}
  <p>no it's false</p>
{/if}

<button onclick={changeState}>Click me</button>
