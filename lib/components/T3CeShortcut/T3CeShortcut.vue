<template>
  <div>
    <T3Renderer :shortcut="shortcut" />
  </div>
</template>

<script>

export default {
  name: 'T3CeShortcut',
  props: {
    shortcut: {
      type: Array,
      required: true
    }
  }
}
</script>
