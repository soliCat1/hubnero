<template>
  <div class="team__table">
    <table>
      <thead>
        <tr>
          <th><ButtonItem :name="'search'" :width="20" :height="20" />Business Name<ArrowButtons /></th>
          <th>
            <ButtonItem :name="'close'" />Team<ArrowButtons />
            <ButtonItem :name="'table-arrow'" style="margin-left: auto" />
          </th>
          <th>
            <ButtonItem :name="'close'" />Role<ArrowButtons />
            <ButtonItem :name="'table-arrow'" style="margin-left: auto" />
          </th>
          <th><ButtonItem :name="'close'" />Gmail<ArrowButtons /></th>
          <th>
            <ButtonItem :name="'close'" />Birthday<ArrowButtons />
            <ButtonItem :name="'table-arrow'" style="margin-left: auto" />
          </th>
          <th><ButtonItem :name="'close'" />Telegram<ArrowButtons /></th>
          <th><ButtonItem :name="'close'" />Last Login<ArrowButtons /></th>
          <th>User permissions</th>
          <th></th>
        </tr>
      </thead>
      <tbody>
          <EmployeeItem
            v-for="employee in employees"
            :key="employee.id"
            :employee="employee"
          />
        </tbody>
    </table>
  </div>
</template>

<script>
import ButtonItem from "@/components/ui/ButtonItem.vue";
import ArrowButtons from "@/components/ui/ArrowButtons.vue";
import EmployeeItem from "@/components/ui/EmployeeItem.vue";
import {data} from "@/mocks/employees.js"

export default {
  components: {
    ButtonItem,
    ArrowButtons,
    EmployeeItem
  },
  data: () =>({
    employees: data
  })
};
</script>

<style>
.team__table {
  padding: 16px 28px;
  border-radius: 12px;
  background-color: #ffffff;
}

table {
  width: 100%;
}

tr {
  display: grid;
  grid-template-columns: 2.2fr 2.2fr 2.2fr 2.2fr 2.2fr 2.2fr 2.2fr 1.6fr 0.5fr;
}

thead tr {
  background-color: #f5f7fb;
  border-radius: 12px;
}

thead th {
  font-size: 12px;
  font-weight: 500;
  line-height: 16px;
  letter-spacing: 0;
  padding: 24px 16px;
  border-left: 1px solid #e5e8ef;
  display: flex;
  gap: 4px;
  align-items: center;
}

thead th:first-child,
thead th:last-child {
  border: none;
}
</style>
