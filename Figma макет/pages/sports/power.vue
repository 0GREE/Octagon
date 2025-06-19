<template>
  <div class="page">
    <Header />
    <main class="main-content">
      <h1 class="main-title">KidsConnect</h1>
      <h2 class="page-subtitle">Силовой спорт</h2>

      <SectionDivider />

      <section class="technology-section">
        <h3 class="technology-title">Технология отделения</h3>
        <p class="technology-subtitle">(в: Общевойсковая мера)</p>
        <p class="area-label">Площадь отделения</p>
        
        <ul class="page-list">
          <li><strong>Стр. 1</strong> (см. стр. 2)</li>
          <li><strong>Стр. 3</strong> (см. стр. 4)</li>
        </ul>
      </section>

      <SectionDivider />

      <!-- Повторяющиеся секции -->
      <template v-for="n in 11" :key="n">
        <section class="technology-section">
          <h3 class="technology-title">Технология отделения</h3>
          <p class="technology-subtitle">(в: Управление и управление)</p>
          
          <ul class="page-list">
            <li><strong>Стр. 1</strong> (см. стр. 2)</li>
            <li><strong>Стр. 3</strong> (см. стр. 4)</li>
          </ul>
        </section>
        <SectionDivider />
      </template>

      <div class="back-link">
        <NuxtLink to="/">← Назад</NuxtLink>
      </div>
    </main>
    <Footer />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'KidsConnect - Силовой спорт'
    }
  }
}
</script>

<style scoped>
.page-subtitle {
  font-size: 28px;
  color: #2c3e50;
  margin-bottom: 20px;
}

.technology-section {
  margin-bottom: 30px;
}

.technology-title {
  font-size: 20px;
  margin-bottom: 5px;
  color: #34495e;
}

.technology-subtitle {
  font-style: italic;
  margin-bottom: 10px;
  color: #7f8c8d;
}

.area-label {
  font-weight: bold;
  margin-bottom: 10px;
}

.page-list {
  list-style-type: none;
  padding-left: 20px;
}

.page-list li {
  margin-bottom: 8px;
}

.back-link {
  margin-top: 40px;
}

.back-link a {
  color: #3498db;
  text-decoration: none;
  font-size: 18px;
}

.back-link a:hover {
  text-decoration: underline;
}
</style>