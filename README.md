# Учебный проект "Место"

#### Спринт 6:
1. Добавлена библиотека `gh-pages`, автоматически размещающая проект на GitHub Pages, в `package.json` добавлен скрипт `deploy`, запускающий сборку;
2. Добавлен класс `Api` для работы с сервером;
3. Карточки загружаются с сервера;
4. Добавлен класс `PopupWithConfirmation.js` для всплывашек с кнопкой подтверждения;
5. Изменен шаблон карточки - добавлен счетчик лайков;
6. Карточки добавляются / удаляются через API;
7. Аватар берется из ответа сервера, сохраняет на сервере новый, в разметке исправлено object-fit для аватара (для не квадратных аватаров);
8. Настройки валидации перенесены в `src/utils/const.js`;