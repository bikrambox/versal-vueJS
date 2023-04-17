<template>
  <nav class="navbar">
    <div class="container">
      <div class="navbar-brand">
        <a class="navbar-logo" href="#">My App</a>
      </div>
      <ul class="navbar-menu">
        <li class="navbar-item">
          <a class="navbar-link" href="#">Home</a>
        </li>
        <li class="navbar-item">
          <a class="navbar-link" href="#">About</a>
        </li>
        <li class="navbar-item">
          <a class="navbar-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
.navbar {
  background: rgba(255, 255, 255, 0.25);
  backdrop-filter: blur(10px);
  border-radius: 10px;
  margin: 20px;
  padding: 10px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.navbar-brand {
  margin-right: auto;
}

.navbar-logo {
  font-size: 24px;
  font-weight: bold;
  color: white;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
}

.navbar-menu {
  display: flex;
  margin-left: auto;
}

.navbar-item {
  margin: 0 10px;
}

.navbar-link {
  font-size: 16px;
  color: white;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
  transition: opacity 0.2s;
}

.navbar-link:hover {
  opacity: 0.8;
}
</style>
