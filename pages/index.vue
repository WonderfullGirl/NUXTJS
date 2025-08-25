<template>
    <div>
        <h1>
            index page
        </h1>
        <h5>
            <nuxt-link to="/work">work</nuxt-link>
        </h5>
        <button @click="changeLayout">Change Layout</button>
    </div>
</template>

<script lang="ts">


    function   changeLayout(): void{
        
        setPageLayout('admin')
    }
</script>