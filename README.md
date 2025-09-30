# ASAP Rocky — Простой статический сайт
Собран минимальный статический проект (4 страницы) — HTML / CSS / JS, без фреймворков.

Структура:
- index.html — главная
- bio.html — биография
- discography.html — дискография (с интерактивом)
- gallery.html — галерея
- styles.css — стили
- script.js — логика

## Как разместить на GitHub Pages (кратко)
1. Создайте репозиторий на GitHub.
2. Инициализируйте локально, добавьте файлы, сделайте коммит:
```bash
git init
git add .
git commit -m "Initial commit — ASAP Rocky site"
git branch -M main
git remote add origin https://github.com/<ваш_логин>/<repo>.git
git push -u origin main
```
3. На GitHub: `Settings` → `Pages` → выберите `Deploy from a branch` → branch: `main`, folder: `/ (root)` и нажмите `Save`.
4. Через несколько минут сайт будет доступен по адресу: `https://<ваш_логин>.github.io/<repo>/`

Доп. информация и официальная документация GitHub Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
