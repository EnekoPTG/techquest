Адаптировал только под 1920px, 1280px и 1024px

Я решил что если карточки будут кликабельными и переводить на другие страницы, то их не стоит заключать в "button", поэтому "button" добавил только кнопкам "Read more" внутри карточек

"cursor: pointer" изначально прописан в "a:-webkit-any-link" во всех браузерах, не вижу смысла прописывать дополнительно в CSS

Переход на DETAILS с HOME-PAGE осуществлён через кнопку "See More" в конце страницы или по первой широкой карточке, обратно так же по кнопке внизу

Не уверен был как именно вставлять адреса картинок в src, но т.к заливал дополнительно в портфолио решил использовать просто "img/xxx.png"

Возможно что-то в CSS будет лишним т.к изначально писал на Flexbox, а потом решил переделать на Grid
