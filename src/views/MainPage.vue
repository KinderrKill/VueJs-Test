<template>
    <div class="main-page">
        <h1>Main Page</h1>
        <Navbar />
    </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
    name: "MainPage",
    components: {
        Navbar
    }
}
</script>
