<script lang="ts">
    import Card from '$lib/Card.svelte';
    import Nav from '$lib/Nav.svelte';
</script>

<svelte:head>
    <title>About</title>
</svelte:head>

<section>
    <Nav />
    <div class="bg-gradient-to-r from-slate-200/80 to-slate-300/80">   
        <header class="flex flex-col justify-center items-center text-center min-h-screen">
            <h1 class="my-10 text-9xl font-bold text-center">About</h1>
            <h2 class="text-2xl font-bold">About this website</h2>
        </header>
        <div class=" bg-white/30 p-6">
            <h2 class="font-bold underline  lg:text-6xl md:text-6xl text-5xl  lg:text-left lg:mx-10 lg:p-4 md:text-left md:mx-10 md:p-4 text-center">
                This website:
            </h2>
            <p class="font-semibold  lg:text-2xl md:text-2xl text-xl  lg:text-left lg:px-24 md:text-left md:px-24 text-center p-4">
                This website was made to show all my projects that I have made. I have used many programming languages but I mostly like to use 
                <span class="text-transparent font-bold bg-clip-text bg-gradient-to-r from-slate-500 to-slate-700">Python, Javascript, Dart and C#.</span>
            </p>
        </div>
        <div class="flex flex-col justify-center items-center bg-slate-700">
            <span class="lg:w-1/2 lg:h-1/2 lg:p-20 p-4">
                <Card title="Phoneguybot" desc="A discord bot using Python and discord.py. It has 30 commands that you can use on your server." link="https://github.com/Phoneguytech75/PhoneguyBot" image="https://cdn.discordapp.com/avatars/852619132138160148/3279a298c890dd33d900a1cd2bbcc7e7.png?size=4096"/>
            </span>
        </div>
    </div>    
</section>