<template>
<div class="_container h-16 flex items-center pl-20">
    <div class="name text-2xl">Web Application</div>
    <div class="items flex items-center absolute right-20">
        <div class="item">Home</div>
        <div class="item">About</div>
        <div class="item">Languages</div>
        <div class="item">Courses</div>
        <div class="item">Feedback</div>
    </div>
</div>
</template>

<script>
export default {
    setup() {
        
    },
}
</script>

<style scoped>
._container {
    background-color: #3B4252;
    color: #D8DEE9;
}

.item {
    margin-left: 40px;
}

.item:hover {
    color: #88C0D0;
    cursor: pointer;
}
</style>