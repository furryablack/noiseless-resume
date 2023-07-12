<template>
  <div class="h-full flex flex-col pb-4 pt-6 items-center overflow-y-auto">
    <div class="max-w-3xl flex flex-col">
      <UI.HeadLine />
      <UI.ContactToMe />
      <UI.SummaryInfo />
      <UI.KeyHighlights />
      <UI.Conclusion />
    </div>
  </div>
</template>

<script setup>
import { UI } from '@pages/entire/ui'; 
</script>