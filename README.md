## Документация для онлайн каталога запчастей [acat.online](https://acat.online)
Вся работа с каталогом происходит по стандартным REST запросам.
Для получения доступа зарегистрируйтесь в [онлайн каталоге](https://acat.online), после регистрации вам будет выдан Authorization token.
Этот Authorization token необходим для идентификации пользователя. Не передавайте его третьим лицам!

Каждый каталог описан в соответсвующих папках.
Каталоги отличаются друг от друга структурой, но схема работы схожа - для доступа нужен Authorization token
(этот токен передается при каждом запросе в Head параметре Authorization).
Далее выбираем тип транспортного средства (CARS_NATIVE, CARS_FOREIGN и т.д.), марку. Затем, в соответсвии с каталогом, вы получите
различные ответы. Чтобы перейти на следующий уровень нужно в URL добавлять необходимые параметры, которые так-же описаны в документации.

Если у вас есть какие-либо вопрос - задавайте их по email support@autodealer.ru