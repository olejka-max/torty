<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Доставка тортов — SweetCake</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-pink-50 text-gray-800">
  <header class="bg-rose-300 p-6 text-center shadow-md">
    <h1 class="text-4xl font-bold">SweetCake</h1>
    <p class="text-lg mt-1">Вкусные торты с бесплатной доставкой по городу</p>
  </header>

  <section class="p-6">
    <h2 class="text-2xl font-semibold mb-4 text-center">Наши торты</h2>
    <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
      <div class="bg-white p-4 rounded shadow">
        <img src="https://via.placeholder.com/300x200" alt="Торт 1" class="rounded mb-2">
        <h3 class="text-xl font-bold">Тирамису</h3>
        <p>Нежный крем и кофе</p>
        <p class="text-rose-600 font-bold mt-2">1200 ₽</p>
      </div>
      <div class="bg-white p-4 rounded shadow">
        <img src="https://via.placeholder.com/300x200" alt="Торт 2" class="rounded mb-2">
        <h3 class="text-xl font-bold">Клубничный чизкейк</h3>
        <p>Сочная клубника и сырный крем</p>
        <p class="text-rose-600 font-bold mt-2">1400 ₽</p>
      </div>
      <div class="bg-white p-4 rounded shadow">
        <img src="https://via.placeholder.com/300x200" alt="Торт 3" class="rounded mb-2">
        <h3 class="text-xl font-bold">Медовик</h3>
        <p>Классический рецепт с мёдом</p>
        <p class="text-rose-600 font-bold mt-2">1000 ₽</p>
      </div>
    </div>
  </section>

  <section class="bg-rose-100 p-6 mt-10">
    <h2 class="text-2xl font-semibold mb-4 text-center">Заказ и доставка</h2>
    <form class="max-w-lg mx-auto space-y-4" onsubmit="event.preventDefault(); alert('Ваш заказ принят! Мы свяжемся с вами.');">
      <input type="text" placeholder="Ваше имя" class="w-full p-3 border rounded" required />
      <input type="tel" placeholder="Телефон" class="w-full p-3 border rounded" required />
      <input type="text" placeholder="Адрес доставки" class="w-full p-3 border rounded" required />
      <select class="w-full p-3 border rounded" required>
        <option disabled selected>Выберите торт</option>
        <option>Тирамису</option>
        <option>Клубничный чизкейк</option>
        <option>Медовик</option>
      </select>
      <button type="submit" class="bg-rose-500 text-white px-6 py-3 rounded hover:bg-rose-600">
        Заказать с бесплатной доставкой
      </button>
    </form>
  </section>

  <footer class="text-center text-sm p-4 bg-rose-300 mt-10">
    © 2025 SweetCake — Доставка тортов. Все права защищены.
  </footer>
</body>
</html>
