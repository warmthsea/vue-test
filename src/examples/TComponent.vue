<script lang="ts" setup generic="T">
defineProps<{
  item: T
  list: T[]
}>()

useTitle('泛型组件 | TComponent')
</script>

<template>
  <div>
    <h2 class="font-semibold">
      泛型组件 | TComponent
    </h2>
    <p>
      item: {{ item }}
    </p>
    <p>
      list: {{ list }}
    </p>
  </div>
</template>
