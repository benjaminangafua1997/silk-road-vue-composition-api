
<script setup>
import  {RouterLink}  from 'vue-router';
import HeadTopVue from '../components/HeadTop.vue';

</script>
<template> 
    <div class="container">
        <HeadTopVue />
       <div class="main">
            <div> Real estate without the hassle</div>
            <div><input type="text" class="property" placeholder="FIND A PROPERTY"></div>
            <div class="filter"><strong><router-link to="/widget"><font-awesome-icon :icon="['fas', 'filter']" /></router-link>  FILTER</strong></div>
        </div>
        <div class="bottom-content">
            <div>OUR LATEST POSTINGS</div>
            <div><span class="material-symbols-outlined">expand_circle_down</span></div>
        </div>
    </div>
</template>
<style scoped>
.container{
    display: grid;
    grid-template-rows: auto 2fr auto;
    height: 100vh;
}
</style>