<template lang="">
    <div class="flex dark:bg-gray-900 bg-gray-100">
        <ToggleThemeButton></ToggleThemeButton>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import ToggleThemeButton from './ToggleThemeButton.vue';

export default defineComponent({
    name: 'NavbarMain',
    components: {
        ToggleThemeButton,
    },
    setup() {
        return {};
    },
});
</script>
<style lang=""></style>
