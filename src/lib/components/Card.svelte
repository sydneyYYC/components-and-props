<script>
export let cardImg;
export let cardTitle;
export let cardDescription;
export let cardLink;
</script>

{#if cardTitle}
<a href={cardLink} class="max-w-max">
<div class="bg-orange-200 max-w-min p-8 flex flex-col justify-center items-center m-4 hover:bg-orange-400">
<img class="max-w-[300px] self-center mb-2" src="{cardImg}">
<h4 class="text-2xl font-semibold">{cardTitle}</h4>
<p class="">{cardDescription}</p>
</div>
</a>
{:else}
<p></p>
{/if}