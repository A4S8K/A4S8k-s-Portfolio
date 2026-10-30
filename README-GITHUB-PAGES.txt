КАК ОПУБЛИКОВАТЬ ГОТОВОЕ ПОРТФОЛИО НА GITHUB PAGES

Архив github-pages-ready.zip содержит уже собранный сайт.
Устанавливать Node.js или запускать команды не нужно.

1. Распакуйте github-pages-ready.zip.
2. Создайте публичный репозиторий в своём аккаунте GitHub.
   Например, назовите его portfolio.
3. Выберите Add file → Upload files и загрузите распакованное
   содержимое архива: index.html, папку assets, favicon.svg и .nojekyll.
   Сам ZIP загружать не нужно.
   index.html должен лежать в корне репозитория, рядом с assets.
   Не помещайте эти файлы внутрь дополнительной папки portfolio или dist.
4. Сохраните загрузку в ветку main (Commit changes).
5. Откройте Settings → Pages.
   Build and deployment → Source: Deploy from a branch.
   Branch: main. Folder: / (root). Нажмите Save.
6. Дождитесь завершения публикации. В Settings → Pages появится
   ссылка на ваш сайт; там же можно нажать Visit site.

Для аккаунта A4S8k и репозитория portfolio пример адреса:
https://a4s8k.github.io/portfolio/
Это пример будущего адреса, а не подтверждение публикации.
Файлы подходят и для другого названия репозитория.

ОБНОВЛЕНИЕ САЙТА

Готовый архив — снимок текущей версии. Чтобы обновить содержимое,
измените исходники, выполните npm run build и замените опубликованные
файлы содержимым dist, включая новые файлы assets и index.html.

Если хотите автоматическую сборку после изменений, используйте
исходники из portfolio.zip и инструкцию README.md внутри них.
Для этого варианта в Settings → Pages выбирается Source: GitHub Actions.
Не смешивайте два способа публикации в одном репозитории.

Инструкция GitHub:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Публикация в GitHub из этого чата не выполнялась.
