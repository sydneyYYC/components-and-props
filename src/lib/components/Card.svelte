<script>
// export let cardImg;
export let cardTitle;
export let cardDescription;
export let cardLink;
</script>


<a href={cardLink} class="max-w-max">
<div class="bg-orange-200 min-w-[15%] p-4 flex flex-col justify-center items-center m-4 hover:bg-orange-400">
<!-- <img class="min-w-max self-center mb-2" {...cardImg}> -->
<h4 class="text-2xl ">{cardTitle}</h4>
<p>{cardDescription}</p>
</div>
</a>
