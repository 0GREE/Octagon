<template>
  <div class="page">
    <Header />
    <main class="main-content">
      <h1 class="main-title">KidsConnect</h1>
      <h2 class="page-subtitle">Единоборства</h2>

      <SectionDivider />

      <MartialArtsTable 
        title="Возникая борьба"
        location="на ул. Нордольская"
        code="КЦ-000"
        coach="Джова"
        note="Без лот"
        address="Пудовые, д.15А"
        organization="СК-Выпорг"
        days="Пн. Ср. Пт"
      />

      <SectionDivider />

      <MartialArtsTable 
        title="Возникая борьба"
        location="на ул. Нордольская"
        coach="Джова"
        note="Без лот"
        address="Пудовые, д.15А"
        organization="СК-Выпорг"
        days="Пн. Ср. Пт"
      />

      <SectionDivider />

      <MartialArtsTable 
        title="Возникая борьба"
        location="на ул. Нордольская"
        code="КЦ-000"
        note="Без лот"
        address="Пудовые, д.15А"
        organization="СК-Выпорг"
        days="Пн. Ср. Пт"
      />

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
      title: 'KidsConnect - Единоборства'
    }
  }
}
</script>