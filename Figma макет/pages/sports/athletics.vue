<template>
  <div class="page">
    <Header />
    <main class="main-content">
      <h1 class="main-title">KidsConnect</h1>
      <h2 class="page-subtitle">Лёгкая атлетика</h2>
      <p class="location">(в Юбилейном мкр.)</p>

      <SectionDivider />

      <div class="back-link">
        <NuxtLink to="/">← Назад на карту</NuxtLink>
      </div>

      <SectionDivider />

      <h3 class="section-header">ГРУППЫ</h3>
      <div class="group-info">
        <p>Этап начальной подготовки</p>
        <p>- Петрова Елена Александровна</p>
        <p>- 15 из 20</p>
        <p>- 12 месяцев</p>
      </div>

      <SectionDivider />

      <h3 class="section-header">РАСПИСАНИЕ ЗАНЯТИЙ</h3>
      <div class="schedule">
        <p>- Пн, Вт, Чт, Сб</p>
        <p>- Пн, Вт, Чт, Сб</p>
        <p>- 0.0001 - 10.0001</p>
        <p>- 8:00 - 19:30</p>
      </div>

      <SectionDivider />

      <h3 class="section-header">ОПИСАНИЕ</h3>
      <div class="description">
        <p>Лёгкая атлетика - олимпийский вид спорта, включающий беговые виды, спортивную ходьбу, технические виды (прыжки и метания), многоборья, пробеги (бег по шоссе), кроссы (бег по пересеченной местности).</p>
      </div>

      <SectionDivider />

      <h3 class="section-header">СОДЕРЖАНИЕ ПРОГРАММЫ</h3>
      <div class="program-content">
        <table class="program-table">
          <tr>
            <td>Базовый уровень</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>Базовый уровень стенности первый второй год обучения 253 часа.</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Обязательные предметы области (количество часов - 15);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Перечисление основных объектов (количество часов - 10);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Горячие количества часов - 4;</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Стоянная количество часов - 3;</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Аттестация (количество часов - 4);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>Базовый уровень стенности третий четвертый год обучения, 46 часов.</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Обязательные предметы области (количество часов - 25);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Разрабатывающие предметы области (количество часов - 18);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Горячие количества часов - 7;</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Аттестация (количество часов - 24);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Аттестация (количество часов - 4);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>Базовый уровень стенности пятый-шестой год обучения 420 часов.</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Обязательные предметы области (количество часов - 27);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Вычитанные предметные области (количество часов - 15);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Горячие количества часов - 5;</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Аттестация (количество часов - 9);</td>
            <td>✅</td>
          </tr>
          <tr>
            <td>• Аттестация (количество часов - 6);</td>
            <td>✅</td>
          </tr>
        </table>
      </div>

      <SectionDivider />

      <h3 class="section-header">Углубленный уровень</h3>
      <div class="empty-section">
        <!-- Контент для углубленного уровня -->
      </div>

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
      title: 'KidsConnect - Лёгкая атлетика'
    }
  }
}
</script>

<style scoped>
.location {
  font-style: italic;
  color: #7f8c8d;
  margin-bottom: 20px;
}

.section-header {
  font-size: 22px;
  color: #2c3e50;
  margin-bottom: 15px;
}

.group-info,
.schedule,
.description {
  margin-bottom: 20px;
  line-height: 1.6;
}

.program-table {
  width: 100%;
  border-collapse: collapse;
}

.program-table td {
  border: 1px solid #ddd;
  padding: 8px 12px;
  vertical-align: top;
}

.program-table tr:nth-child(even) {
  background-color: #f9f9f9;
}

.empty-section {
  min-height: 100px;
  border: 1px dashed #ddd;
  margin-bottom: 30px;
}
</style>