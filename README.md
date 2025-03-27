# План изучения React с созданием UI-кита

**Цель:** Постепенно освоить React, параллельно разрабатывая библиотеку переиспользуемых компонентов (кнопки, карточки, инпуты и др.).

---

## 1. Подготовка
- Установка окружения:
  - Node.js + npm/yarn/pnpm
  - Создание проекта через `create-react-app` или `Vite + React`
  - Настройка Git (опционально)
- Изучение основ JSX и структуры React-проекта

---

## 2. Основы React
### Теория:
- Компоненты (функциональные vs классовые)
- Пропсы (`props`)
- Состояние (`useState`)
- Хуки: `useEffect`, `useMemo`, `useCallback`
- Стилизация (CSS-модули/Styled Components/Tailwind)

### Практика:
- `Button` (варианты `primary`, `secondary`)
- `Text` (заголовки, параграфы)

---

## 3. Списки и формы
### Теория:
- Рендеринг списков (`map`, `key`)
- Управление формами (`useRef`, обработка сабмита)

### Практика:
- `Input` (текст, число, checkbox)
- `Dropdown`/`Select`
- `Card` (контейнер с заголовком)

---

## 4. Продвинутые хуки
### Теория:
- Кастомные хуки (`useToggle`, `useInput`)
- Контекст (`useContext`)

### Практика:
- Переключатель темы (светлая/тёмная)
- `Modal` с использованием контекста

---

## 5. Роутинг
### Теория:
- React Router (`react-router-dom`)

### Практика:
- Страница-демо для UI-кита с навигацией

---

## 6. Работа с API
### Теория:
- Запросы (`fetch`/`axios`)
- Обработка загрузки/ошибок

### Практика:
- Компонент `DataFetching` (демо API)
- `Toast` (уведомления)

---

## 7. Финальная сборка
- Документация:
  - Storybook/MDX (опционально)
  - README с примерами
- Публикация:
  - Сборка (`npm run build`)
  - Размещение на GitHub Pages

---

## 8. Дальнейшее развитие
- Тестирование (Jest + React Testing Library)
- Анимации (Framer Motion)
- Интеграция TypeScript

## Полезные ресурсы
- [Официальная документация React](https://react.dev)
- [React Tutorial (freeCodeCamp)](https://www.freecodecamp.org/learn/front-end-development-libraries/react/)
- [Storybook для документации](https://storybook.js.org/)