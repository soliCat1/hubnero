<template>
  <button type="button">
    <IconSprite v-if="name === 'search'" :name="'search'" :width="width" :height="height" />
    <IconSprite v-else-if="name === 'close'" :name="'close'" />
    <IconSprite v-else-if="name === 'delete'" :name="'delete'" />
    <IconSprite v-else-if="name === 'table-arrow'" :name="'table-arrow'" />
    <IconSprite v-else-if="name === 'arrow'" :name="'arrow'" />
    <IconSprite v-else-if="name === 'bell'" :name="'bell'" />
  </button>
</template>

<script>
import IconSprite from "@/components/ui/IconSprite.vue";

export default {
  components: {
    IconSprite
  },
  props: {
    name: {
      type: String
    },
    width: {
      type: Number
    },
    height: {
      type: Number
    }
  }
};
</script>

<style scoped>
button {
  border: none;
  background-color: transparent;
  cursor: pointer;
  display: block;
  width: 20px;
  height: 20px;
  color: inherit;
}
</style>