
<template>
  <header class="header sticky-top">
    <div class="container">
      <div class="logo">
        <img src="portfolio.png" alt="Logo">
      </div>
      <nav  class="nav">
        <ul class="nav-list">
          <li class="nav-item"><a href="#home" class="nav-link">Home</a></li>
          <li class="nav-item"><a href="#projects" class="nav-link">Projects</a></li>
          <li class="nav-item"><a href="#contact" class="nav-link">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo img {
  max-width: 100px;
}

.nav {
  flex-grow: 1;
}

.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
}

.nav-item {
  margin-right: 20px;
}

.nav-link {
  color: #fff;
  text-decoration: none;
  font-size: 18px;
}

.nav-link:hover {
  text-decoration: underline;
}
</style>
