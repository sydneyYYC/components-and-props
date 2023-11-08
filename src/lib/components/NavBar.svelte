<script>
  export let navItems = [
    {name: 'home', href:"/"},
    {name: 'gallery', href:"/gallery"},
     {name:'about', href:"/about"}
    ]
</script>

<!-- TODO add hover -->
<header class="max-w-full flex justify-between items-center bg-amber-900 text-white">
  <div class="p-2 hover:yellow-500"> Logo </div>
  <nav>
  <ul class="flex g-2">
    {#each navItems as {name, href}}
    <li class="p-2"><a href={href}>{name}</a></li>
    {/each}
  </ul>
</nav>
</header>