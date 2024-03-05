<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>
  </WelcomeItem>
  <WelcomeItem>
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a>
  </WelcomeItem>
</template>
