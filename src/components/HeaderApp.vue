<script setup lang="ts">
interface HeaderAppProps {
    pageTitle: string
}

defineProps<HeaderAppProps>()

</script>

<template>
    <div class="head">
        <h4>{{ pageTitle }}</h4>
    </div>
</template>

<style scoped>
.head {
    width: 100%;
    height: 2rem;

    display: flex;
    align-items: center;
    padding-inline: 24px;
}
</style>