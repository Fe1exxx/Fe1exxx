# 🧰 frontend playground

> Песочница для экспериментов: React, TypeScript, алгоритмы, UI-паттерны  
> Всё — в режиме «сделал → проверил → зафиксировал»

<div align="center">
  <a href="https://react.dev">
    <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black" alt="React 19">
  </a>
  <a href="https://vitejs.dev">
    <img src="https://img.shields.io/badge/Vite-5-646CFF?logo=vite" alt="Vite 5">
  </a>
  <a href="https://www.typescriptlang.org">
    <img src="https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript" alt="TypeScript 5">
  </a>
  <a href="https://tailwindcss.com">
    <img src="https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?logo=tailwind-css" alt="Tailwind CSS 3">
  </a>
</div>

<br>

## 🔧 Проекты

| Название | Стек | Особенности | Ссылка |
|----------|------|-------------|--------|
| **Курс: Web‑разработка** | HTML, Bootstrap | Адаптивная структура, модули, видеоблоки | [открыть](https://fe1exxx.github.io/BootStrap/) |
| **Тема + текст** | React, TS, `localStorage` | Переключение темы (`data-theme`), сохранение состояния | [код](https://github.com/Fe1exxx/React_changing_the_theme_and_text_and_localStorage) |
| **Прокрутка** | Vanilla JS | Индикатор скролла, `scrollTo({ behavior: 'smooth' })`, `passive: true` | [код](https://github.com/Fe1exxx/Focus_and_scroll_indicator) |
| **Галерея животных** | React, TS, Tailwind | Фильтрация (`type`), поиск (`.toLowerCase().includes()`), типизированные данные | [код](https://github.com/Fe1exxx/...) |
| **Портфолио** | React, TS, Vite | Минималистичный лендинг, адаптив | [открыть](https://fe1exxx.github.io/Portfolio/) |

<br>

## 📦 Текущий фокус

- [x] `useState`, `useEffect`, управление состоянием  
- [x] Типизация: интерфейсы, union‑типы, дженерики (`useState<T>`)  
- [x] Работа с массивами: `map`, `filter`, `find`, `some`  
- [x] `fetch` / `async`/`await`, обработка ошибок  
- [x] `localStorage`: сохранение / восстановление  
- [ ] `useMemo` / `useCallback` — профилирование  
- [ ] React Router — маршрутизация  
- [ ] Тестирование: Vitest + RTL  
- [ ] Node.js API (Express) — минимальный бэкенд  

<br>

## 💼 Контакты

- **Email**: `maxas1488@gmail.com`  
- **Telegram**: `@fex_d`  
- **GitHub**: [@Fe1exxx](https://github.com/Fe1exxx)

---

<!-- Анимация: линейный прогресс-бар внизу -->
<div align="center">
  <div style="width: 100%; height: 4px; background: #e5e7eb; border-radius: 2px; overflow: hidden">
    <div style="
      height: 100%;
      width: 65%;
      background: linear-gradient(90deg, #3b82f6, #8b5cf6);
      animation: pulse 2s ease-in-out infinite;
    "></div>
  </div>
</div>

<style>
@keyframes pulse {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.6; }
}
</style>
