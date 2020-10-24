<template>
    <div>
    <navbar></navbar>
    <gallery></gallery>



    </div>
</template>

<script>
import navbar from '../components/navbar.vue'
import gallery from '../components/gallery.vue'
export default {
    name: 'component-name',
    // props: {},
    data: function(){
        return {}
    },
    // computed: {},
    methods: {
        // -- Metodos
    },
    components: {
        'navbar':navbar,
        'gallery':gallery,

        
    },
}
</script>

<style scoped>
    
</style>