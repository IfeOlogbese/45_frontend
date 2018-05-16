<template>
    <div id="app">
        <div class="wrapper platform-index">
            <!-- Sidebar Holder -->
            <app-sidebar></app-sidebar>

            <!-- Page Content Holder -->
             <app-content></app-content>
        </div>
    </div>
</template>

<script>
import AppSidebar from '@/components/AppSidebar.vue'
import AppContent from '@/components/AppContent.vue'
export default {
    name: 'App',
    components: {
        AppSidebar,
        AppContent
    }
}
</script>

<style lang="scss">
    @import 'static/sass/main.scss'
</style>

