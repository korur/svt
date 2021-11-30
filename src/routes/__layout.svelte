<script>
    import NavBar from "../components/NavBar.svelte";
</script>



<div class="text-gray-600 grid md:grid-cols-3">


    <NavBar></NavBar>

<main class="px-16 py-6 bg-gray-100 m-0 md:col-span-2">

    <slot />
</main> 

   
</div>


<style>
@tailwind base;
@tailwind components;
@tailwind utilities;

</style>