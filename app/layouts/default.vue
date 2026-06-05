<template>
    <UHeader>
        <template #title>
            <div class="flex items-center gap-2">
                <img src="/images/NhDiscordLogo.png" class="h-12">
                <span>NH Discord</span>
            </div>
        </template>
    </UHeader>
    
    <img src="/images/Mountains.png" class="fixed inset-0 w-full h-full object-cover -z-10 blur-xs">

    <slot />
</template>

<script setup>

</script>