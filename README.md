```vue
<template>
    <div>
        <!-- name is a string, so toUpperCase() should work, right? -->
        {{ name.toUpperCase() }}
    </div>
</template>

<script setup lang="ts">
    const name = ref<string>() // Type: globalThis.Ref<string, string>
</script>
```
