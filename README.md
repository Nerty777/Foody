Available Scripts:<br>
server - npm start;<br>
client - npm run server and npm start;<br>

<h3>Задание:</h3>
    <ul>
      <li>React, Redux.</li>
      <li>
        Сделать шапку приложения состоящую из логотипа, списка навигации и меню
        пользователя с выпадающим меню.
      </li>
      <li>Сделать таблицу истории заказов из файла order-history.json</li>
      <li>
        Сделать сетку блюд из файла menu.json, добавить поиск по имени блюда.
      </li>
      <li>Сделать формы логина и регистрации.</li>
      <li>
        Сделать секцию комментариев к блюду. Список где выводятся комментарии и
        форма с textarea и select, в котором указан рейтинг от 0 до 10, и
        кнопкой для добавления комментария.
      </li>
      <li>
        При рендере App, необходимо сделать запрос на бекенд и забрать список
        всех заказов, отрендерить его в таблице.
      </li>
      <li>
        Добавьте в каждую строку таблицы кнопку Удалить, при клике на которую,
        происходит HTTP запрос на бекенд для удаления записи по id. После ответа
        удаляем на фронте.
      </li>
      <li>
        Добавьте в каждую строку таблицы кнопку Детальнее, при клике на которую,
        идет HTTP- запрос на бекенд для получения записи по id. Результат овтета
        от бекенда отобразить в любом виде.
      </li>
      <li>
        Когда идет запрос на одну запись по id, добавьте индикатор загрузки,
        который отображается пока идет запрос, после чего отображается модальное
        окно.
      </li>
      <li>Модальное окно можно закрыть и продолжить работать с таблицей.</li>
      <li>
        Добавьте форму для создания записи в истории. Дата используется
        на момент сабмита. Адрес доставки, цена и рейтинг вводятся в поля формы.
      </li>
      <li>
        При сабмите формы идет POST запрос на бекенд с составленным объектом.
        Ждем ответа от бекенда и если все ок, добавлям в список истории на
        фронте.
      </li>
      <li>
        Добавить авторизацию, используйте 2 сервера, один json-server для
        коллекции продуктов, второй для регистрации пользователя.
      </li>
    </ul>
