<script>
    let count = 0;
    $: squared = count ** 2;
    $: squaredMinusOne = squared - 1;
    function handleClick() {
        count += 1
    }
</script>

<button on:click={handleClick}>Counter is: {count}</button>
<h1>Square value of counter is: {squared}</h1>
<h2>Squared minus one is: {squaredMinusOne}</h2>