<script lang="ts" setup>
const handleClick = () => {
  alert('Button clicked')
}
</script>

<template>
  <button
    @click="handleClick"
    id="ui-button"
    class="rounded-[5px] border-none p-[10px] text-white bg-[blue]"
  >
    <slot />
  </button>
</template>
