# TwitterCopy

В данном проекте я пытался реализовать главную страницу Twitter образца 2012 года при помощи React + JavaScript. Это мой первый проект с использованием React.

Для запуска проекта (проект должен быть локально запущен):

### `npm start`

[http://localhost:3000](http://localhost:3000)

## Какие функции реализованы?

1. Лента твитов, которая обновляется по мере появления новых твитов.
2. Возможность написать свой твит, воспользовавшись полем "Написать твит". При отправке он появится в ленте твитов с указанием имени пользователя и его никнейма (картинка 1).
3. Размер окна твита в ленте автоматически растягивается в зависимости от размера сообщения.
4. Реализован поиск сообщений, который реагирует как на текст в твите, так и на имя пользователя либо его никнейм. Поиск происходит сразу, без нажатия кнопки поиск (картинка 2).
5. При создании поста дата его создания сохраняется и время написания твита меняется в зависимости от того, как давно пост был написан (X секунд назад, X минут назад, X часов назад, X дней назад, X лет назад).
6. Хэштеги слева генерируются случайно из специального массива слов при каждом новом рендере страницы.

Картинка 1
<img width="1440" alt="Снимок экрана 2022-07-09 в 10 46 43 AM" src="https://user-images.githubusercontent.com/91781655/178097168-640cb589-2867-4847-b763-5cb816a5f2e7.png">

Картинка 2
<img width="1440" alt="Снимок экрана 2022-07-09 в 10 47 00 AM" src="https://user-images.githubusercontent.com/91781655/178097189-3c3b893f-fb6c-482b-bbc6-6ca374771a57.png">
