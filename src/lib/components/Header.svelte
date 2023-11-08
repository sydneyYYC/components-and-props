<script>
export let headerTitle = 'Welcome!';
export let headerImg = {
  src:"./gallery/header_theme-photos-Hx7xdwhj2AY-unsplash.jpg", alt:"hands kneading dough"
}
</script>

<div class=" grid min-w-full min-height-[600px] grid-rows-2 grid-col-2">
  <h1 class="row-span-full text-6xl font-bold col-start-1 z-10 self-center px-8 text-amber-950">{headerTitle}</h1>
  <img class="col-span-3 row-span-full col-start-1 saturate-50" {...headerImg}>
</div>