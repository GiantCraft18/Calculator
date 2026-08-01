<!--- 
  Переливающийся README для калькулятора.
  Использует CSS-анимацию градиента для всего текста.
--->

<div align="center">

# <span class="rainbow" style="background: linear-gradient(90deg, #ff6b6b, #feca57, #48dbfb, #ff9ff3, #54a0ff, #5f27cd, #ff6b6b); background-size: 300% 300%; -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; animation: shift 5s ease-in-out infinite; font-weight: 800; font-size: 2.8rem; letter-spacing: 1px;">✨ Переливающийся калькулятор ✨</span>

<style>
  @keyframes shift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  .rainbow-text {
    background: linear-gradient(90deg, #ff6b6b, #feca57, #48dbfb, #ff9ff3, #54a0ff, #5f27cd, #ff6b6b);
    background-size: 300% 300%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    animation: shift 5s ease-in-out infinite;
    font-weight: 600;
  }
  .rainbow-link {
    background: linear-gradient(90deg, #feca57, #ff6b6b, #48dbfb, #5f27cd);
    background-size: 300% 300%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    animation: shift 4s ease-in-out infinite;
    font-weight: 600;
    text-decoration: none;
  }
  .rainbow-link:hover {
    filter: brightness(1.2);
  }
</style>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/MIT-License-green?style=for-the-badge" alt="MIT License" />
</p>

<p align="center">
  <span class="rainbow-text" style="font-size: 1.2rem;">🌈 Минималистичный, адаптивный, с клавиатурной поддержкой</span>
</p>

</div>

---

## <span class="rainbow-text" style="font-size: 2rem;">🌟 Особенности</span>

- <span class="rainbow-text">**Базовые операции**</span>: сложение (+), вычитание (−), умножение (×), деление (÷), остаток от деления (%).
- <span class="rainbow-text">**Умный ввод**</span>: автоматическое форматирование чисел, обработка десятичных точек, ограничение длины ввода.
- <span class="rainbow-text">**Отображение выражения**</span>: показывает текущее вводимое выражение и результат.
- <span class="rainbow-text">**Управление**</span>:
  - `AC` — полный сброс.
  - `⌫` — удаление последнего символа.
  - `=` — вычисление результата.
- <span class="rainbow-text">**Клавиатурная поддержка**</span>: все кнопки дублируются клавишами (цифры, `+`, `-`, `*`, `/`, `%`, `Enter`/`=`, `Backspace`, `Escape`/`Delete`).
- <span class="rainbow-text">**Адаптивный дизайн**</span>: корректно отображается на мобильных устройствах и десктопах.

---

## <span class="rainbow-text" style="font-size: 2rem;">🚀 Установка и запуск</span>

1. <span class="rainbow-text">**Скачайте** файл `index.html` (или скопируйте код).</span>
2. <span class="rainbow-text">**Откройте** его в любом браузере (Chrome, Firefox, Edge, Safari и т.д.).</span>
3. <span class="rainbow-text">Готово! Калькулятор сразу готов к использованию.</span>

<span class="rainbow-text">Никаких дополнительных зависимостей или серверов не требуется — всё работает локально.</span>

---

## <span class="rainbow-text" style="font-size: 2rem;">⌨️ Использование</span>

- <span class="rainbow-text">**Нажмите на кнопки** мышью или тач-экраном.</span>
- <span class="rainbow-text">**Используйте клавиатуру**:</span>
  - <span class="rainbow-text">Цифры `0–9` и точка `.` для ввода чисел.</span>
  - <span class="rainbow-text">`+`, `-`, `*`, `/`, `%` для операций.</span>
  - <span class="rainbow-text">`Enter` или `=` для вычисления.</span>
  - <span class="rainbow-text">`Backspace` для удаления последнего символа.</span>
  - <span class="rainbow-text">`Escape` или `Delete` для полной очистки.</span>

---

## <span class="rainbow-text" style="font-size: 2rem;">📁 Структура проекта</span>

<span class="rainbow-text">Проект состоит из одного файла `index.html`, который включает:</span>

- <span class="rainbow-text">**HTML** — разметка интерфейса.</span>
- <span class="rainbow-text">**CSS** — стилизация, тени, адаптивность.</span>
- <span class="rainbow-text">**JavaScript** — вся логика калькулятора (обработка нажатий, вычисления, обновление дисплея).</span>

---

## <span class="rainbow-text" style="font-size: 2rem;">🌐 Демонстрация</span>

<span class="rainbow-text">Вы можете опробовать калькулятор онлайн:</span>  
<a href="#" class="rainbow-link">✨ Открыть демо-версию ✨</a>  
<span class="rainbow-text">*(вставьте ссылку, если разместите на GitHub Pages или другом хостинге)*</span>

---

## <span class="rainbow-text" style="font-size: 2rem;">🎨 Настройка</span>

<span class="rainbow-text">При желании вы можете легко изменить внешний вид:</span>

- <span class="rainbow-text">**Цвета**: отредактируйте значения `background`, `color` и `box-shadow` в CSS.</span>
- <span class="rainbow-text">**Размеры**: измените `padding`, `font-size` и `gap` у кнопок.</span>
- <span class="rainbow-text">**Поведение**: логика вычислений находится в функции `compute()` внутри тега `<script>`.</span>

---

## <span class="rainbow-text" style="font-size: 2rem;">📄 Лицензия</span>

<span class="rainbow-text">Этот проект распространяется свободно. Вы можете использовать, модифицировать и распространять его без ограничений.</span>

<span class="rainbow-text">Подробнее в файле [`LICENSE`](LICENSE).</span>

---

<div align="center">
  <p>
    <span class="rainbow-text" style="font-size: 1.3rem;">Сделано с ❤️ и ✨ переливами ✨</span>
  </p>
  <p>
    <a href="#" class="rainbow-link" style="font-size: 1.1rem;">⭐ Поставьте звезду, если понравилось!</a>
  </p>
</div>