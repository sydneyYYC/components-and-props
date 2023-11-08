<script>
export let cardImg;
export let cardTitle;
export let cardDescription;
export let cardLink;
</script>


<a href={cardLink} class="max-w-max">
<div class="bg-slate-200 max-w-max p-4 flex flex-col">
<img class="min-w-max" {...cardImg}>
<h4 class="text-2xl ">{cardTitle}</h4>
<p>{cardDescription}</p>
</div>
</a>
