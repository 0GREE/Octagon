<template>
  <div class="page">
    <Header />
    <main class="main-content">
      <h1 class="main-title">KidsConnect</h1>
      
      <section class="sport-section">
        <h2 class="section-title">Силовой спорт</h2>
        <NuxtLink to="/sports/power" class="section-link">Подробнее →</NuxtLink>
      </section>

      <SectionDivider />

      <section class="sport-section">
        <h2 class="section-title">Лёгкая атлетика</h2>
        <NuxtLink to="/sports/athletics" class="section-link">Подробнее →</NuxtLink>
      </section>

      <SectionDivider />

      <section class="sport-section">
        <h2 class="section-title">Единоборства</h2>
        <NuxtLink to="/sports/martial" class="section-link">Подробнее →</NuxtLink>
      </section>
    </main>
    <Footer />
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'KidsConnect - Главная'
    }
  }
}
</script>

<style scoped>
.page {
  font-family: 'Arial', sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.main-title {
  font-size: 32px;
  text-align: center;
  margin-bottom: 30px;
  color: #2c3e50;
}

.sport-section {
  padding: 20px 0;
}

.section-title {
  font-size: 24px;
  margin-bottom: 15px;
  color: #34495e;
}

.section-link {
  display: inline-block;
  color: #3498db;
  text-decoration: none;
  margin-top: 10px;
}
</style>