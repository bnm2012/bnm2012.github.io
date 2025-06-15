<script setup>
import { ref } from 'vue'
</script>

<template>
  <div class="container">
    <header>
      <h1>aaaaa</h1>
    </header>

    <main class="main">
      <div>
        <a href='/AutoCAD工具箱安装包/updates.txt'>
          <h2>updates.txt</h2>
        </a>
        <a href='/N2N/N2N_version.json'>
          <h2>N2N_version.json</h2>
        </a>
        <a href='/N2N/N2N管理工具1.0.exe'>
          <h2>N2N管理工具1.0.exe</h2>
        </a>
        <a href='/N2N/N2N管理工具1.1.exe'>
          <h2>N2N管理工具1.1.exe</h2>
        </a>
      </div>
    </main>

    <footer class="footer">
      <p>Powered by Vue 3 + Vite</p>
    </footer>
  </div>
</template>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  font-family: Arial, sans-serif;
}

header {
  padding: 2rem 0;
  text-align: center;
  background-color: #f8f9fa;
}

.main {
  flex: 1;
  padding: 2rem;
  max-width: 800px;
  margin: 0 auto;
}

.main a {
  display: block;
  margin: 1rem 0;
  padding: 1rem;
  background-color: #e9ecef;
  border-radius: 5px;
  color: #212529;
  text-decoration: none;
  transition: all 0.2s ease-in-out;
}

.main a:hover {
  background-color: #ced4da;
}

.footer {
  background-color: #343a40;
  color: white;
  padding: 2rem;
  text-align: center;
}
</style>
