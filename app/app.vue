<template>
  <UApp>
    <NuxtLayout>
      <UMain>
        <NuxtPage/>
      </UMain>
    </NuxtLayout>
  </UApp>
</template>

<script setup>
useSeoMeta({
  title: 'NH Discord',
  ogTitle: 'NH Discord',
  ogDescription: 'Join a welcoming New Hampshire community where locals meet new friends, share events, and talk about life in the Granite State. Whether you’re here for gaming, or casual chat, there’s always someone nearby to connect with',
  ogImage: 'https://nhdiscord.com/images/NhDiscordLogo.png',
  themeColor: '#0C233C'
})
</script>