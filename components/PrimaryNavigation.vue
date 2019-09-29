<template>
    <div>
        <div v-if="navOpen" class="primary-navigation">
            <div class="container">
                <div class="flex flex-col">
                    <h6 class="text-gray-500">Navigation</h6>
                    <a href="#" class="text-white">Home</a>
                    <a href="#" class="text-white">About</a>
                    <a href="#" class="text-white">Resources</a>
                    <button class="text-white" @click="toggleMenu">Close Menu</button>
                </div>
            </div>
        </div>
        <button class="text-white" @click="toggleMenu">Open Menu</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            navOpen: false
        }
    },
    methods: {
        toggleMenu() {
            this.navOpen = !this.navOpen;
        }
    }
}
</script>

<style>
    .primary-navigation {
        position: fixed;
        height: 100vh;
        left: 0;
        top: 0;
        width: 100vw;
        background: black;
    }
</style>