<template>
    <header>
        <div>
            <div>
                <nav>
                    <RouterLink to="/">Memorotes</RouterLink>
                </nav>
                <nav>
                    <RouterLink to="/member">Member</RouterLink>
                </nav>
            </div>
        </div>
    </header>

    <RouterView />
</template>

<script lang="ts" setup>
import { RouterLink, RouterView } from "vue-router";
</script>
