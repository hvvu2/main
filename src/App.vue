<template>
    <header>
        <div class="wrapper">
            <nav>
                <RouterLink to="/">Home</RouterLink>
            </nav>
        </div>
    </header>

    <RouterView />
</template>

<script lang="ts" setup>
import { RouterLink, RouterView } from "vue-router";
</script>
