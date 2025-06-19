<template>
  <table class="schedule-table">
    <tr>
      <th colspan="2">{{ title }}</th>
    </tr>
    <tr>
      <td colspan="2">({{ location }})</td>
    </tr>
    <tr v-if="code">
      <td colspan="2">{{ code }}</td>
    </tr>
    <tr>
      <td><strong>Джова</strong></td>
      <td></td>
    </tr>
    <tr>
      <td><strong>Без лот</strong></td>
      <td></td>
    </tr>
    <tr>
      <td><strong>М - г/порук, ул</strong></td>
      <td>Пудовые, д.15А</td>
    </tr>
    <tr>
      <td><strong>О - СК-Выпорг</strong></td>
      <td></td>
    </tr>
    <tr>
      <td><strong>Пн. Ср. Пт</strong></td>
      <td></td>
    </tr>
  </table>
</template>

<script>
export default {
  props: {
    title: String,
    location: String,
    code: String,
    coach: String,
    note: String,
    address: String,
    organization: String,
    days: String
  }
}
</script>

<style scoped>
.schedule-table {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: 30px;
}

.schedule-table th, 
.schedule-table td {
  border: 1px solid #ddd;
  padding: 8px;
  text-align: left;
}

.schedule-table th {
  background-color: #f2f2f2;
}
</style>