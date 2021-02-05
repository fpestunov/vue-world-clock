# World Clock

- вывод простых часов HH:MM:SS;
- добавление часов из списка городов;
- тема: день и ночь;
- часы: классические/цифровые;
- перемещение блоков на странице;
- сохранение данных в базу браузера;
- добавить кнопку настроек с опциями - примечание, удалить;
- вывод времени и города в заголовок окна (https://medium.com/@Taha_Shashtari/the-easy-way-to-change-page-title-in-vue-6caf05006863)
```js
  document.title = "Some new title text";
  newPageTitle = 'The title has changed!'; 
  document.querySelector('title').textContent = newPageTitle; 
```


## Resources
- Datetime libs https://momentjs.com/, https://github.com/zloirock/dtf
- часовые пояса https://habr.com/ru/company/mailru/blog/438286/
- https://vuejsexamples.com/tag/clock/
- https://github.com/eddyerburgh/vue-digital-clock/blob/master/src/Clock.vue - электронные часы
- https://yandex.ru/time/ - образец часов