# Фурӯғи илму дониш

Сайт программы поддержки учителей математики в регионах Таджикистана.
Исполнитель: ОБО «Пешрафт». Автор сайта: Yorov Muhammadmurod.

Адрес: https://furughi-ilm.pages.dev (Cloudflare Pages).

## Что в папке

- `index.html` — весь сайт в одном файле: текст на трёх языках (RU, TJ, EN),
  стили, скрипты и фотографии внутри. Открывается двойным щелчком.
- `favicon.*`, `icon-*.png`, `apple-touch-icon.png` — иконка сайта.
- `og-image.jpg` — картинка, которая видна, когда ссылкой делятся в Telegram,
  WhatsApp, Facebook.
- `site.webmanifest`, `sitemap.xml`, `robots.txt` — для телефонов и поисковиков.
- `_headers` — настройки безопасности для Cloudflare Pages.
- `DESIGN.md` — как устроен сайт и правила дизайна.
- `LICENSE` — права на сайт.

## Как опубликовать

Cloudflare: Workers & Pages → Create → Pages → Upload assets → перетащить
содержимое этой папки целиком. Любой другой хостинг статических сайтов
тоже подойдёт: достаточно загрузить эти файлы.

Если сайт переезжает на свой домен, замените `https://furughi-ilm.pages.dev`
на новый адрес в `index.html`, `sitemap.xml` и `robots.txt`.

## Заявки с сайта

Анкета учителя, заявка на ремонт и сообщение руководителю отправляются в CRM
Пешрафта (`window.PESHRAFT_CRM_ENDPOINT` в начале `index.html`). Если CRM
недоступна, открывается письмо на info@peshraft.charity.
