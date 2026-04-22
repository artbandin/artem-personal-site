# Artem personal site

Минимальный статический сайт для GitHub Pages.

## Что внутри

- `index.html` — главная страница
- `styles.css` — стили
- `assets/` — изображения
- `.github/workflows/pages.yml` — автодеплой на GitHub Pages

## Локальный запуск

Открыть `index.html` в браузере или поднять простой сервер:

```bash
python3 -m http.server 8000
```

## Публикация на GitHub Pages

1. Создать новый репозиторий на GitHub, например `artem-personal-site`
2. Запушить содержимое этой папки в `main`
3. В репозитории открыть **Settings → Pages**
4. Если workflow не включился автоматически, выбрать **GitHub Actions** как source
5. После первого пуша сайт будет доступен по адресу вида `https://<user>.github.io/<repo>/`

## Что стоит доделать

- заменить `assets/profile-photo.svg` на реальное фото Артёма
- добавить публичные ссылки на канал / GitHub / домен
- при желании подключить кастомный домен через `CNAME`
