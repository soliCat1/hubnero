<template>
  <tr>
    <th>
      <img :src="require(`@/assets/${employee.img}`)" />{{ employee.name }}
    </th>
    <th>{{ employee.team }}</th>
    <th>{{ employee.role }}</th>
    <th>{{ employee.mail }}</th>
    <th>{{ employee.birthday }}</th>
    <th>{{ employee.telegram }}</th>
    <th>{{ employee.lastLogin }}</th>
    <th>
      <button class="edit-button" type="button">
        <IconSprite :name="'edit'" /> Edit
      </button>
    </th>
    <th><ButtonItem :name="'delete'" /></th>
  </tr>
</template>

<script>
import ButtonItem from "@/components/ui/ButtonItem.vue";
import IconSprite from "@/components/ui/IconSprite.vue";

export default {
  props: {
    employee: {
      type: Object,
    },
  },
  components: {
    ButtonItem,
    IconSprite,
  },
};
</script>

<style scoped>
th {
  padding: 14px 16px;
  font-size: 14px;
  font-weight: 400;
  line-height: 20px;
  letter-spacing: 0;
  display: flex;
  align-items: center;
  gap: 12px;
}

.edit-button {
  padding: 8px 14px;
  border-radius: 8px;
  border: 1px solid #e5e8ef;
  gap: 8px;
  display: flex;
  align-items: center;
  font-family: inherit;
  font-size: 14px;
  font-weight: 400;
  line-height: 20px;
  letter-spacing: 0;
  background-color: transparent;
  color: inherit;
  cursor: pointer;
}
</style>
