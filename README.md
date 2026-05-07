# Bioniq Prototypes

Кликабельные HTML-прототипы продуктов Bioniq. Без бэкенда, на моковых данных.

## Структура

```
shared/      — общие assets: логотипы, дизайн-токены (Montserrat, цвета)
web/         — веб-прототипы (desktop)
app/         — мобильные прототипы (375px frame)
```

## Прототипы

### Web

| Прототип | Описание | Ссылка |
|---|---|---|
| [store](web/store/) | Магазин витаминов: каталог, наборы, корзина, чекаут, оплата, личный кабинет | https://slnkt.github.io/bioniq-prototypes/web/store/ |

### App

_(пока пусто)_

## Дизайн-токены

- **Primary**: `#042033` (тёмно-синий)
- **Error**: `#d10714`
- **Background**: `#ffffff` / `#fafafa`
- **Text primary**: `rgba(0,0,0,.87)` / **secondary**: `rgba(0,0,0,.54)`
- **Шрифт**: Montserrat (400, 500, 600, 700)
- **Логотипы**: `shared/logo-blue.svg`, `shared/logo-black.svg`

См. [`shared/tokens.css`](shared/tokens.css).

## Локальный запуск

```bash
cd web/store && python3 -m http.server 8765
# открыть http://localhost:8765/
```
