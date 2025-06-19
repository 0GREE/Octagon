<template>
  <footer class="footer">
    <div class="footer-content">
      <p class="copyright">© 2024 KidsConnect. Все права защищены.</p>
      <div class="footer-links">
        <NuxtLink to="/" class="footer-link">Главная</NuxtLink>
        <NuxtLink to="/sports/power" class="footer-link">Силовой спорт</NuxtLink>
        <NuxtLink to="/sports/athletics" class="footer-link">Лёгкая атлетика</NuxtLink>
        <NuxtLink to="/sports/martial" class="footer-link">Единоборства</NuxtLink>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: #2c3e50;
  color: white;
  padding: 20px 0;
  margin-top: 50px;
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

.copyright {
  margin: 0;
}

.footer-links {
  display: flex;
  gap: 20px;
}

.footer-link {
  color: white;
  text-decoration: none;
}

.footer-link:hover {
  text-decoration: underline;
}
</style>