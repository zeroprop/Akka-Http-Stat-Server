Сервер, собирающий статистику о посещении сайта. 
Выполнен в виде двух узлов. Статистика с каждого узла отправляется в Kafka и на выходе высчитывается максимальное посещение сайта
для каждого узла. Для работы с Json используется io.circe, для работы с конфигурацией приложения используется typesafe.config.
