
 Приложения добавления фотографий в альбом.

 компонент Modal - отвечает за отображение картинки в модальном окне

 компонент Forms -  обрабатывает добавление  изображения в  хранилище
 
 компонент AlbumsList - отвечает за рендер списка альбомов с API

 компонент Albums - отвечает за рендер списка альбомов с API

сам редюсер бработки находиться в файле index.js отдельно выносить не стал (хотя надо было бы)


функции редюсера:

close- меняет состояние для отображения компонентов ри открытии модального окна

add - складывает новое состояние в стору 

delete - удаляет с состояния по  id фотографии id альбома  (айдишник генерим рандомный специально чтобы был больше чео в основном json и не было совпадений)

addList -  увеличивае исходное количество альбомов через состояние  


  