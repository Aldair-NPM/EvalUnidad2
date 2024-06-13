<template>
    <h1 class="text-center">Hola desde el componente del Dashboard</h1>
    <Footer></Footer>
</template>

<script>
    import Footer from '../components/Footer.vue'

    export default{
        components:
            {
                Footer
            }
    }
</script>