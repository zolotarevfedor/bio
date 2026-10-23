# Академический сайт (academicpages)

Сайт собран на шаблоне [academicpages](https://academicpages.github.io/) по образцу
[jaedsongms.github.io/Website](https://jaedsongms.github.io/Website/).

## Где что лежит

| Что | Файл |
|---|---|
| Имя, фото, ссылки под фото | `_config.yml`, блок `author:` |
| Главная страница (клик по имени) | `_pages/about.md` |
| Research | `_pages/publications.md` |
| Teaching | `_pages/teaching.html` |
| Education | `_pages/education.md` |
| Projects | `_pages/projects.md` |
| Honors & Awards | `_pages/awards.md` |
| Пункты верхнего меню | `_data/navigation.yml` |

## Как добавить фото

1. Положить файл в папку `images/` (например, `images/profile.png`).
2. В `_config.yml` вписать имя файла: `avatar : "profile.png"`.

## Как добавить ссылки под фото

В `_config.yml`, в блоке `author:`, заполнить нужные поля (`email`, `googlescholar`,
`orcid`, `linkedin`, `twitter` и т.д.). Пустые поля на сайте не показываются.

## Публикация

Загрузить содержимое папки в репозиторий на GitHub и включить GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / root). Если репозиторий называется
`<username>.github.io`, сайт откроется по адресу `https://<username>.github.io/`. Этот сайт: https://zolotarevfedor.github.io/bio/.
