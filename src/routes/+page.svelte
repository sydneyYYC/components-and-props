<script>
  import Card from "../lib/components/Card.svelte";
  import Header from "../lib/components/Header.svelte";
  import {cardOne} from "../lib/data.js";
  import {cardTwo} from "../lib/data.js";
</script>

<Header></Header>
<main class="min-h-screen flex flex-col items-center">
<h1 class="my-4 text-2xl">Welcome to my Baking Website</h1>


<Card {...cardOne}/>

<Card {...cardTwo}/>
</main>

