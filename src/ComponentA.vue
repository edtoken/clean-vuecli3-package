<template>
    <div class="component-a">
        <h1>Component A</h1>
        <slot></slot>
    </div>
</template>
<script>
    export default {};
</script>
<style lang="css" scoped>
    .component-a {
        padding: 15px;
        border: 1px solid #ddd;
    }
</style>
