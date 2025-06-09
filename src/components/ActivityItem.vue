<script lang="ts">
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'ActivityItem',
  components: {},
  setup() {
    const title = ref('')
    const priority = ref(0)

    return { title, priority }
  },
  methods: {},
})
</script>
<template>
  <div>
    <div>{{ title }}</div>
    <div>{{ priority }}</div>
  </div>
</template>
<style scoped></style>
