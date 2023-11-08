<script>
  import Card from "../lib/components/Card.svelte";
import Footer from "../lib/components/Footer.svelte";
  import Header from "../lib/components/Header.svelte";
  import NavBar from "../lib/components/NavBar.svelte";

  let cardTitle = "Title";
  let cardDescription = "Description of the card harharharharhar";
  let cardImg = {
  src:"./gallery/header_theme-photos-Hx7xdwhj2AY-unsplash.jpg", alt:"hands kneading dough"
}
  let cardLink = "/"
</script>

<Header></Header>
<main class="min-h-screen flex flex-col">
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<Card {...cardImg} {cardLink} {cardTitle}  {cardDescription}/>
</main>