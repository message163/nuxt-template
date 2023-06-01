<template>
  <div>
        {{a}}

        <div>
          {{ hello }}
        </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
const hello = ref('hello')
const a = 1
</script>
