<script>
    export let id; 
    
</script>



<section id={id} class={"min-h-screen flex flex-col px-4"}>
    <div class="flex flex-col flex-1 max-w-[1400px] mx-auto w-full p-10 lg:p-13">
        <slot />
    </div>
</section>
