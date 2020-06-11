# Тестовое задание для соискателей на вакансию Frontend developer

## Для выполнения задания, делаем форк этого репозитория и разворачиваем в нем через vue-cli новый проект.


## Задача
 
 vue компонент добавления сайта как приложение pwa (Add to home screeen)
 
 Необходимо написать кроссбраузерный компонент добавления сайта как приложение
 
 - Определяем поддержку этой функции браузером
 - Регистрируем service worker и необходимые колбэки для установки, проверки обновления и определения offline режима
 - Выводим уведомление "Добавить на главный экран", если уже добавлено и запущено в режиме standalone то уведомление не показываем
 - Проверяем наличие новой версии сайта и предлагаем загрузить обновление
 - можно использовать https://cli.vuejs.org/ru/core-plugins/pwa.html, главное чтобы компонент кооректно работал.
 
 
 ### Внимание! данный компонент должен корректно работать во всех современных браузерах chrome, opera, safari + iphone (safari, chrome)
 
 **Ссылки на документацию:**
 
 https://codelabs.developers.google.com/codelabs/add-to-home-screen/#0
 https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Add_to_home_screen
