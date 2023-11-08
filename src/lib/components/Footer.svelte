<script>
export let footItems = [
    {name: 'home', href:"/"},
    {name: 'gallery', href:"/gallery"},
     {name:'about', href:"/about"}
    ]
</script>

<footer class="flex flex-col items-center justify-center bg-amber-900 text-amber-50">
  <ul class="flex">
    {#each footItems as {name, href}}
    <li class="p-2 my-2"><a href={href}>{name}</a></li>
    {/each}
  </ul>
  <p>&copy;Sydney Bruce</p>
  <div>Logo</div>
</footer>