<script>
  import { store } from "../store";
  import Incrementer from "./counterHelpers/Incrementer.svelte";
  import Decrementer from "./counterHelpers/Decrementer.svelte";
  import Setter from "./counterHelpers/Setter.svelte";
</script>

<h1>The count is {$store}</h1>

<Incrementer />
<Decrementer />
<Setter />
