# Публикация на GitHub Pages — пошагово

## 1. Создайте репозиторий

На GitHub нажмите **New repository**.

Рекомендуемое имя: `english-lab`.

## 2. Загрузите файлы

В корень репозитория должны попасть:

```text
index.html
.nojekyll
README.md
DEPLOY_GITHUB_PAGES.md
```

Главный файл сайта обязательно должен называться `index.html`.

## 3. Включите Pages

**Settings → Pages → Build and deployment**

Выберите:

```text
Source: Deploy from a branch
Branch: main
Folder: /(root)
```

Нажмите **Save**.

## 4. Откройте сайт

После публикации появится ссылка:

```text
https://USERNAME.github.io/english-lab/
```

Если репозиторий называется `USERNAME.github.io`, ссылка будет:

```text
https://USERNAME.github.io/
```

## 5. Как обновлять сайт

Заменяйте только `index.html` новой версией и делайте Commit. GitHub Pages автоматически обновит сайт.

## Пользовательский домен

Если позже захотите подключить собственный домен, это делается в **Settings → Pages → Custom domain**. Для первого запуска это не требуется.
