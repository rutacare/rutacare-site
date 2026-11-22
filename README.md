# rutacare-site

Исходники сайта https://rutacare.pl (Ruta Care).

## Структура

| Папка / файл | Что это | Адрес на сайте |
|---|---|---|
| `index.html` | Главная страница (пока заглушка «Strona w przygotowaniu») | https://rutacare.pl/ |
| `anketa/` | Выбор языка анкеты для украинских и русскоязычных кандидаток (UA, RU), `noindex` | https://rutacare.pl/anketa/ |
| `ankieta/` | Страница польской анкеты (PL), `noindex` | https://rutacare.pl/ankieta/ |

В папках `anketa/` и `ankieta/` лежат `index.html` и `logo.png`.

## Как выкладывается

Вручную: SeoHost, DirectAdmin → File Manager → `domains/rutacare.pl/public_html`. Структура папок здесь совпадает со структурой на хостинге. GitHub Pages отключён, сайт работает только на хостинге.

## Логотип

`logo.png` вырезан из мастер-файла `Corporate Identity/logo/ruta-care-logo-master.svg` (слой `Color_full`, цветной полный, 448 px, прозрачный фон). Менять логотип нельзя, его правила описаны в `Corporate Identity/BRAND.md`.
