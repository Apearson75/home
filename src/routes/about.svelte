<script lang="ts">
    import Nav from '$lib/Nav.svelte';
</script>

<svelte:head>
    <title>About</title>
</svelte:head>

<section>
    <Nav />
    <div class="bg-gradient-to-r from-slate-200/80 to-slate-300/80">   
        <header class="flex flex-col justify-center items-center text-center min-h-screen">
            <h1 class="my-10 text-9xl font-bold">About</h1>
            <h2 class="text-2xl font-bold">About this website</h2>
        </header>
        <div class=" bg-white/30">
            <h1 class="font-bold underline  lg:text-6xl md:text-6xl text-5xl  lg:text-left lg:mx-10 lg:p-4 md:text-left md:mx-10 md:p-4 text-center">
                This website:
            </h1>
        </div>
    </div>    
</section>