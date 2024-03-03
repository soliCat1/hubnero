<template>
  <div class="arrow-buttons">
    <button type="button">
      <IconSprite :name="'search-arrow'" />
    </button>
    <button class="down-arrow" type="button">
      <IconSprite :name="'search-arrow'" />
    </button>
  </div>
</template>

<script>
import IconSprite from "@/components/ui/IconSprite.vue";

export default {
  components: {
    IconSprite
  }
};
</script>

<style scoped>
.arrow-buttons {
  height: 20px;
  width: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 3px;
}

button {
  border: none;
  background-color: transparent;
  cursor: pointer;
  color: #C2C9DA;
}

button:hover {
  color: #2A355A;
}

button svg {
  display: block;
}

.down-arrow {
  transform: rotate(180deg);
}

</style>