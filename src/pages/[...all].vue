<script setup lang="ts">
const { t } = useI18n()
</script>

<template>
  <div>
    {{ t('Pagina não encontrada') }}
  </div>
</template>

<route lang="yaml">
meta:
  layout: 404
</route>
