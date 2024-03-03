<template>
  <div class="team">
    <TeamInfo />
    <button class="add-button" type="button"><IconSprite class="add-button__icon" :name="'add-button'" />Add new Employee</button>
    <TeamTable />
    <TeamPagination />
  </div>
</template>

<script>
import TeamInfo from "@/components/TeamInfo.vue";
import IconSprite from "@/components/ui/IconSprite.vue";
import TeamTable from "@/components/TeamTable.vue";
import TeamPagination from "@/components/TeamPagination.vue";

export default {
  components: {
    TeamInfo,
    IconSprite,
    TeamTable,
    TeamPagination
  },
};
</script>

<style scoped>
.team {
  padding: 28px;
  background-color: #2a355a0a;
  min-height: 88vh;
  display: flex;
  flex-direction: column;
  gap: 28px;
}

.add-button {
  font-family: inherit;
  padding: 14px 16px;
  color: #ffffff;
  background-color: #8f20ef;
  font-size: 14px;
  font-weight: 400;
  line-height: 20px;
  letter-spacing: 0;
  border-radius: 12px;
  gap: 12px;
  display: flex;
  border: none;
  width: fit-content;
}

.add-button__icon {
  background-color: #9c3fee;
  border-radius: 6px;
}
</style>
