<template>
    <header class="bg-black text-yellow-300 border border-dashed border-red-500 p-5">
      <div class="container mx-auto flex justify-between items-center">
        <a href="/" class="text-4xl font-extrabold transform rotate-12 hover:rotate-0 transition-transform">LOGO</a>
        <nav>
          <ul class="flex space-x-8">
            <li>
              <a href="/courses" class="text-lg font-mono hover:text-pink-500 transition-colors">Курсы</a>
            </li>
            <li>
              <a href="/about" class="text-lg font-mono hover:text-green-500 transition-colors">О нас</a>
            </li>
            <li>
              <a href="/contact" class="text-lg font-mono hover:text-blue-500 transition-colors">Контакты</a>
            </li>
            <li>
              <a href="/login" class="text-lg font-mono hover:text-purple-500 transition-colors">Вход</a>
            </li>
          </ul>
        </nav>
      </div>
    </header>
  </template>
  
  <script setup>
  // В этом примере нет необходимости в скриптовой части
  </script>
  
  <style scoped>
  /* Примеры нестандартного дизайна */
  header {
    box-shadow: 0 0 15px rgba(255, 0, 0, 0.6);
  }
  
  a {
    text-transform: uppercase;
    letter-spacing: 1.5px;
  }
  
  ul {
    border: 2px dotted yellow;
  }
  </style>
  