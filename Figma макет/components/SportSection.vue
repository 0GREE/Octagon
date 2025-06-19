<template>
  <section class="sport-section">
    <h2>{{ title }}</h2>
    <h3>(в: {{ subtitle }})</h3>
    
    <ul class="pages-list">
      <li v-for="page in pages" :key="page.number">
        <strong>Стр. {{ page.number }}</strong> (см. стр. {{ page.ref }})
      </li>
    </ul>
    
    <hr class="section-divider">
  </section>
</template>

<script>
export default {
  props: {
    title: String,
    subtitle: String,
    pages: Array
  }
}
</script>

<style scoped>
.sport-section {
  margin-bottom: 30px;
}

.pages-list {
  list-style-type: none;
  padding: 0;
}

.section-divider {
  margin: 20px 0;
  border: 1px solid #eee;
}
</style>