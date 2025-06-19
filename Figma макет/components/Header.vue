<template>
  <header class="header">
    <div class="header-content">
      <h1 class="logo">KidsConnect</h1>
      <nav class="nav">
        <NuxtLink to="/" class="nav-link">Главная</NuxtLink>
        <NuxtLink to="/sports/power" class="nav-link">Силовой спорт</NuxtLink>
        <NuxtLink to="/sports/athletics" class="nav-link">Лёгкая атлетика</NuxtLink>
        <NuxtLink to="/sports/martial" class="nav-link">Единоборства</NuxtLink>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  background-color: #2c3e50;
  color: white;
  padding: 15px 0;
  margin-bottom: 30px;
}

.header-content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

.logo {
  margin: 0;
  font-size: 24px;
}

.nav {
  display: flex;
  gap: 20px;
}

.nav-link {
  color: white;
  text-decoration: none;
  font-weight: 500;
}

.nav-link:hover {
  text-decoration: underline;
}
</style>