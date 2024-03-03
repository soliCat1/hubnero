<template>
  <header>
    <IconSprite :name="'burger'" />
    <h1>Team</h1>
    <div class="container">
      <ButtonItem :name="'search'" :width="24" :height="24" />
      <ButtonItem class="active" :name="'bell'" />
      <div class="container--profile">
        <img :src="require('@/assets/ernest1.png')" />
        <span>Ernest Eberly</span>
        <ButtonItem :name="'arrow'" />
      </div>
    </div>
  </header>
</template>

<script>
import IconSprite from "@/components/ui/IconSprite.vue";
import ButtonItem from "@/components/ui/ButtonItem.vue";

export default {
  components: {
    IconSprite,
    ButtonItem
  },
};
</script>

<style scoped>
header {
  display: flex;
  padding: 22px 28px;
  align-items: center;
  justify-content: space-between;
  gap: 28px;
  position: relative;
}

header::before {
  position: absolute;
  content: '';
  top: 0;
  bottom: 0;
  left: 0;
  width: 28px;
  background: linear-gradient(90deg, rgba(42, 53, 90, 0.04) 0%, rgba(42, 53, 90, 0) 100%);
}

h1 {
  font-size: 22px;
  font-weight: 500;
  line-height: normal;
  letter-spacing: 0px;
}

.container {
  margin-left: auto;
  display: flex;
  align-items: center;
  gap: 28px;
}

.container--profile {
  display: flex;
  align-items: center;
  gap: 12px;
  padding-left: 28px;
  border-left: 1px solid #e5e8ef;
}

span {
  display: block;
  font-size: 14px;
  font-weight: 500;
  line-height: 20px;
}

.active {
  position: relative;
}

.active::after {
  position: absolute;
  content: "";
  top: 2px;
  right: -2px;
  width: 8px;
  height: 8px;
  border: 2px solid #ffffff;
  background-color: #fc5a5a;
  border-radius: 50%;
}
</style>
