# Сергей Царегородцев - CV

Персональная страница-резюме, созданная с помощью Quarto и размещенная на GitHub Pages.

## О проекте

Этот репозиторий содержит персональную страницу-резюме преподавателя фармакологии Российского университета медицины, которая автоматически публикуется на GitHub Pages по адресу https://svtsar.github.io

## Структура проекта

```
svtsar.github.io/
├── _quarto.yml          # Конфигурация Quarto
├── index.qmd            # Главная страница с резюме
├── styles.css           # Кастомные стили
├── cover.png            # Фото профиля
├── .github/workflows/   # GitHub Actions для автоматического деплоя
└── README.md           # Описание проекта
```

## Технологии

- [Quarto](https://quarto.org/) - система для создания технических документов
- R Markdown
- CSS3
- GitHub Pages
- GitHub Actions - автоматический деплой

## Локальная разработка

1. Установите [Quarto](https://quarto.org/docs/get-started/)
2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/svtsar/svtsar.github.io.git
   cd svtsar.github.io
   ```
3. Запустите локальный сервер:
   ```bash
   quarto preview
   ```

## Автоматический деплой

При каждом пуше в ветку `main` сайт автоматически собирается и деплоится на GitHub Pages.

## Автор

**Сергей Царегородцев**

- Преподаватель фармакологии, Российский университет медицины
- Email: sergiotsar@ya.ru
- ORCID: [0000-0002-0254-0516](https://orcid.org/0000-0002-0254-0516)
- GitHub: [@svtsar](https://github.com/svtsar)
- Telegram: @pharmRUM

## Связанные проекты

- [База знаний СНК кафедры фармакологии](https://svtsar.github.io/SNK/docs/) - электронный учебник по научной работе
