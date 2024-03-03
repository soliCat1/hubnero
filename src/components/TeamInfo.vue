<template>
  <div class="team__info">
    <div class="icon-container">
      <IconSprite style="color: #1e96fc" :name="'user'" />
    </div>
    <h2>Team <IconSprite :name="'info'" /></h2>
    <ul>
      <li
        v-for="item in info"
        :key="item.title"
        :class="{ men: item.title === 'men', online: item.title === 'online' }"
      >
        <span class="value">{{ item.value }}</span>
        <span class="title">{{ item.title }}</span>
      </li>
    </ul>
  </div>
</template>

<script>
import IconSprite from "@/components/ui/IconSprite.vue";

export default {
  components: {
    IconSprite,
  },
  data: () => ({
    info: [
      { title: "members", value: 130 },
      { title: "online", value: 36 },
      { title: "men", value: 50 },
      { title: "women", value: 80 },
      { title: "average age", value: 29 },
      { title: "days work on average", value: 265 },
      { title: "days work newest employee", value: 36 },
      { title: "days work oldest employee", value: 1256 },
    ],
  }),
};
</script>

<style scoped>
.team__info {
  padding: 16px 28px;
  border-radius: 12px;
  display: flex;
  align-items: center;
  background-color: #ffffff;
  width: fit-content;
}

.icon-container {
  background-color: #2a355a0a;
  border-radius: 8px;
  width: 32px;
  height: 32px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 16px;
}

h2 {
  font-size: 14px;
  font-weight: 500;
  line-height: 20px;
  letter-spacing: 0px;
  margin-right: 90px;
  flex-shrink: 0;
}

ul {
  list-style: none;
  display: flex;
  width: fit-content;
}

li {
  padding: 0 36px;
  border-right: 1px solid #e5e8ef;
}

li:first-child {
  padding-left: 0;
}

li:last-child {
  padding-right: 65px;
  border: none;
}

span {
  display: block;
}

.value {
  font-size: 22px;
  font-weight: 500;
  line-height: 29px;
  letter-spacing: 0;
}

.title {
  font-size: 12px;
  font-weight: 400;
  line-height: 18px;
  letter-spacing: 0;
  color: #8591ae;
}

.men {
  padding-right: 0;
  border: none;
}
.online {
  position: relative;
}

.online::after {
  position: absolute;
  content: "";
  width: 6px;
  height: 6px;
  top: 5px;
  right: 33px;
  border-radius: 50%;
  background-color: #24c182;
}
</style>
