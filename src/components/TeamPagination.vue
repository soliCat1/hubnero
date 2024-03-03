<template>
  <ul class="team__pagination">
    <li><ButtonItem :name="'arrow'" style="transform: rotate(90deg)" /></li>
    <li>1</li>
    <li class="active">2</li>
    <li>3</li>
    <li>...</li>
    <li>12</li>
    <li><ButtonItem :name="'arrow'" style="transform: rotate(-90deg)" /></li>
  </ul>
</template>

<script>
import ButtonItem from "@/components/ui/ButtonItem.vue";

export default {
  components: {
    ButtonItem,
  },
};
</script>

<style>
.team__pagination {
  padding: 16px;
  border-radius: 12px;
  background-color: #ffffff;
  list-style: none;
  display: flex;
}

.team__pagination li {
  font-size: 14px;
  font-weight: 400;
  line-height: 20px;
  letter-spacing: 0;
  width: 36px;
  height: 36px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  color: #8591ae;
}

.team__pagination li.active {
  background-color: #f5f7fb;
  color: inherit;
  border-radius: 12px;

}
</style>
