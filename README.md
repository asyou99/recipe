Для установки проекта после клонирования выполняем команды:
#1
composer install
#2
В файле config/db.php настраиваем подключение к БД
#3
В файле web.php есть компонент капчи с ключами настроеными на локальный домен
recipe.loc усли домен у вас другой ключи надо поставить соответсвующие 
#4
Выполняем миграции php yii migrate