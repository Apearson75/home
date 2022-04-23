<script lang="ts">
    export let title: string;
    export let desc: string;
    export let image: string;
    export let gitlink: string;
</script>
 
<div class="rounded-xl overflow-hidden bg-white">
    <img src={image} alt="" class="object-cover">
    <div class="p-8">
        <h2 class="font-semibold underline text-xl">{title}</h2>
        <p class="py-2 font-medium">{desc}</p>
        <a href={gitlink} class="bg-black rounded-md font-semibold text-white px-2 py-1">
            Github Link
        </a>
    </div>
</div>
    