# Методичка Java 12

Исходный проект: https://github.com/1ommyS/itp-ebook. История коммитов и указание авторства сохранены.

Адрес после публикации: https://itpark32.github.io/java-12-metodichka/

## Локальный запуск

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements-docs.txt
python -m mkdocs serve
```

Проверка сборки: `python -m mkdocs build --strict`.

## Публикация

В настройках репозитория откройте **Settings → Pages → Build and deployment → Source** и выберите **GitHub Actions**.
Workflow `.github/workflows/ci.yml` собирает сайт и публикует его при каждом push в `main`. Его также можно запустить вручную через **Actions → Publish handbook to GitHub Pages → Run workflow**.
