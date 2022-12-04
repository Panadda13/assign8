<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/h.png" alt="">
            </div>
            <div class="content">
                <h3>Favorite Music&Series</h3>
                <span>It is what you do right now that make a difference.</span>
                <p>It's about making a website about what you like. by selecting songs and series.</p>
                <router-link to="/about" class="btn"> music&series <i class="fas fa-user"></i> </router-link>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar }
    
}
</script>

<style>

</style> 