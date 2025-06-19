<template>
  <table class="martial-table">
    <tr>
      <th colspan="2">{{ title }}</th>
    </tr>
    <tr>
      <td colspan="2">({{ location }})</td>
    </tr>
    <tr v-if="code">
      <td colspan="2">{{ code }}</td>
    </tr>
    <tr v-if="coach">
      <td><strong>{{ coach }}</strong></td>
      <td></td>
    </tr>
    <tr v-if="note">
      <td><strong>{{ note }}</strong></td>
      <td></td>
    </tr>
    <tr>
      <td><strong>М - г/порук, ул</strong></td>
      <td>{{ address }}</td>
    </tr>
    <tr v-if="organization">
      <td><strong>О - {{ organization }}</strong></td>
      <td></td>
    </tr>
    <tr v-if="days">
      <td><strong>{{ days }}</strong></td>
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
.martial-table {
  width: 100%;
  border-collapse: collapse;
  margin: 20px 0;
  font-family: Arial, sans-serif;
}

.martial-table th,
.martial-table td {
  border: 1px solid #ddd;
  padding: 8px 12px;
  text-align: left;
}

.martial-table th {
  background-color: #f2f2f2;
  font-size: 18px;
}

.martial-table td {
  font-size: 16px;
}
</style>