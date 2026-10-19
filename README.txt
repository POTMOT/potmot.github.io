САЙТ POTAPP — КАК ВЫЛОЖИТЬ И ОБНОВЛЯТЬ
======================================

ВЫКЛАДКА (один раз)
1. На GitHub создай новый репозиторий с именем ровно: potmot.github.io
   (Public, без README). Такое имя делает сайт главным: https://potmot.github.io/
2. Нажми "uploading an existing file" и перетащи ВСЁ содержимое этой папки
   (файлы и папки fonts, img, games, privacy). Commit changes.
3. Settings → Pages → Branch: main, / (root) → Save. Через 1–2 минуты сайт откроется.
   Старая страница политики https://potmot.github.io/spacestranger-privacy/ продолжит работать.

ЧТО ПОМЕНЯТЬ / ДОПОЛНИТЬ
- Иконка Cook it!: положи файл img/cook-it/icon.jpg (квадрат 512×512).
- Ссылка на Cook it!: в index.html найди "Замени ссылку на прямую страницу игры".
- Скриншоты Космического Странника: положи 01.jpg … 05.jpg в img/space-stranger/
  (те, что выгружал из Figma для RuStore).
- Когда игра выйдет в RuStore: в index.html и games/space-stranger/index.html
  найди комментарии "Когда игра выйдет" и вставь ссылку на RuStore.

НОВОСТЬ
В index.html, раздел НОВОСТИ: скопируй блок <article class="post"> … </article>
и вставь его ВЫШЕ остальных, поменяй дату, заголовок и текст.

НОВАЯ ИГРА
В index.html, раздел ИГРЫ: скопируй блок <article class="game"> … </article>.
Для отдельной страницы игры скопируй папку games/space-stranger и поправь тексты.

СВОЙ ДОМЕН (потом)
Купи домен, затем Settings → Pages → Custom domain. Сайт останется бесплатным.
