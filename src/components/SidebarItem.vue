<template>
  <div class="sidebar">
    <div class="sidebar__container">
      <a href="/" class="logo__link">
        <IconSprite :name="'logo'" />
      </a>
    </div>
    <ul class="sidebar__list">
      <li :class="{active : link.active}" v-for="link in links" :key="link.id">
        <a href="/">
          <IconSprite :name="link.name" />
        </a>
      </li>
    </ul>
    <div class="sidebar__container sidebar__container--button">
      <button type="button">
        <IconSprite :name="'plus'" />
      </button>
    </div>
  </div>
</template>

<script>
import IconSprite from "@/components/ui/IconSprite.vue";

export default {
  components: {
    IconSprite
  },
  data: () => ({
    links: [
      {
        id: 1,
        name: 'tools',
        active: false},
      {
        id: 2,
        name: 'charts',
        active: false},
      {
        id: 3,
        name: 'money',
        active: false},
      {
        id: 4,
        name: 'attachment',
        active: false},
      {
        id: 5,
        name: 'documents',
        active: false},
      {
        id: 6,
        name: 'tickets',
        active: false},
      {
        id: 7,
        name: 'settings',
        active: false},
      {
        id: 8,
        name: 'business',
        active: false},
      {
        id: 9,
        name: 'user',
        active: true}
    ],
  })
};
</script>

<style scoped>
.sidebar {
  width: 72px;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.sidebar__container {
  padding: 28px 26px;
}

.sidebar__list {
  list-style: none;
  display: flex;
  flex-direction: column;
}

.sidebar__container--button {
  padding: 28px;
  border-top: 1px solid #e5e8ef;
  margin-top: auto;
}

li {
  padding: 12px 26px;
  position: relative;
}

a {
  color: #8591AE;
}

a:hover {
  color: #8F20EF;
}

li.active::after {
  content: '';
  position: absolute;
  top: center;
  left: 0;
  width: 4px;
  height: 20px;
  border-radius: 0 100px 100px 0;
  background-color: #8F20EF;
}

li.active a {
  color: #8F20EF;
}

button {
  border: none;
  cursor: pointer;
  background-color: transparent;
  color:#8591AE;
}
</style>
