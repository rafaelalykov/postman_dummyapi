# Чтение документации Dummyapi и создание postman colections + tests

[![LinkedIn Badge](https://img.shields.io/badge/-@rafaelalykov-blue?style=flat&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/rafaelalykov/) [![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat&logo=Gmail&logoColor=white)](mailto:rafaelalykov@gmail.com)


### Технологии
<p  align="center">
  <code><img width="5%" title="Postman" src="logo/postman.png"></code>

### Что делаем
* Читаем документацию
* Собираем запросы 
* Вводим окружение и переменные
* Составляем тесты
* Запускаем Test Run

___

##### Согласно документации https://dummyapi.io/docs составляем запросы к каждому методу

<p  align="center">
  <code><img width="100%" title="Postman" src="screenshots/docs_user.png"></code>
</p>

##### К  https://dummyapi.io/data/v1/ для каждого запроса пишем свой эндпоинт и согласно документации заполняем запрос

<p  align="center">
  <code><img width="100%" title="Postman" src="screenshots/creating.png"></code>
</p>

##### Для создоваемых сущностей пропишем команду создания переменных в нашем окружении

<p  align="center">
  <code><img width="100%" title="Postman" src="screenshots/creat_data.png"></code>
</p>
<p  align="center">
  <code><img width="100%" title="Postman" src="screenshots/variables.png"></code>
</p>

##### А для того чтоб не вводить новые параметры при создании user, создаем генерируемые данные в Urlencoded 
<p  align="center">
  <code><img width="100%" title="Postman" src="screenshots/create_random.png"></code>
</p>

##### Для каждого запроса создадим тесты проверки код статуса и для сущностей проверку в теле ответа и запускаем тест колекции.

<p  align="center">
  <code><img width="100%" title="Postman" src="screenshots/test_run.png"></code>
</p>


