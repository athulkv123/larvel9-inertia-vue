<template>
  <Link href="/">Main Page</Link>&nbsp;
  <Link href="/hello">Show Page</Link>
  <div>The Page with time {{ timer }}</div>
  <slot>Default</slot>
</template>

<script setup>
import { Link } from '@inertiajs/inertia-vue3'
import {ref} from 'vue'
const timer = ref(0)
</script>