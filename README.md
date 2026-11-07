# Keepsake — лендинг дизайн-студії

Адаптивна верстка лендингу студії Keepsake: шапка з мобільним меню, секції About, Our Works, Journal, Contact, блок статистики та футер з формою підписки.

**Демо:** https://nekronik10.github.io/landing-keepsake/

## Технології

- HTML5, CSS3 (Flexbox, CSS-змінні, медіазапити)
- Google Fonts
- Google Icons та Bootstrap Icons
- Без JavaScript і фреймворків

## Рішення

- **Мобільне меню** працює без JS: прихований чекбокс і `:has(#burger:checked)`.
- **Фільтри Our Works** прокручуються горизонтально: `overflow-x: auto`, `flex: 0 0 auto`.
- **Статистика** на мобайлі йде сіткою 2×2 на флексі.
- **Форма підписки**: валідація через `:user-invalid`, екран успіху через `:target`.
- **Стрілки меню** і соцкнопки зроблені на CSS (`::after`, `border-radius: 50%`).
- Іменування класів за BEM.