# Star Wars API

    Задача: совершить запрос по API к https://swapi.dev/ и показать следующую информацию:
     Вывести кликабельный список всех персонажей, которые будут возрващаться после обращения к "/people". По умолчанию будет возвращаться 10 записей, по этому необходимо реализовать кнопки "вперед" и, если необходимо, "назад". Например, я кликнул "вперед" и пролистнул список на 10 записей вперед, таким образом у меня появляется возможность вернуться назад по клику на соответствующую кнопку.

    По клику на имя персонажа необходимо отрбразить поля с информацией о нём в виде таблицы:

    в заголовке:
    имя;
    год рождения;
    пол;
    список фильмов;
    родная планета;
    подвид (species);

Добавить кнопку "Назад к списку" и вернуться на то поле, с которого перешли к деталям персонажа. Эту информацию можно "запоминать" через хранилища браузера.
Оформить вид на стороне клиента таким образом, чтобы это не выглядело вырвиглазным. Добавить .css для списка, кнопок, списков; скомонировать элементы таким образом, чтобы не было "дыр" на странице, т.е. полноценная страница с приятным интерфейсом. Подумать над форматом вывода информации: как будут скрываться или отображаться новые элементы.
