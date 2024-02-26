<template>
    <div class="filter-con">
        <h1>Filter</h1>
        {{myArray}}
    </div>
</template>

<script>
import Home from './Home.vue';
export default {
    name: 'Filter',
    // props: {
    //     incomeAndMetrics: Array,
    //     indexList: Array
    // },
    methods: {
    }
};

</script>

<style scoped>
.filter-con{
    margin-top: 1rem;
    height: 90vh;
    width: 90vw;
    background-color: rgb(23, 23, 23);
    z-index: 100;
}
.filter-con > *{
    z-index: 101;
    
}
</style>