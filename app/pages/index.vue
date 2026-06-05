<template>
    <UPageSection
    title="New Hampshire's Biggest Community Discord server"
    :description="hero_description"
    >
    <img src="/images/hero.png" class="rounded-md" alt="">
    </UPageSection>

    <UPageSection>
        <UPricingPlans :plans="plans"/>
    </UPageSection>

</template>

<script setup lang="ts">
import type { PricingPlanProps } from '@nuxt/ui';


const hero_description = "Join a welcoming New Hampshire community where locals meet new friends, share events, and talk about life in the Granite State. Whether you’re here for gaming, dating, or casual chat, there’s always someone nearby to connect with"

const plans = ref<PricingPlanProps[]>([
    {
        title: "NH Discord",
        description: hero_description,
        features: [
            'Active Community',
            '700+ Members',
            'Weekly Events',
            'News'
        ],
        button: {
            label: "Join Now!",
            to: 'https://discord.gg/PFM7gQJa2H'
        }
    }
])

</script>