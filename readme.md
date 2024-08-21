# Назначение

Группа контейнеров предназначена для разворачивания тестовой среды разработки с применением Kafka.  

Содержит кластер Kafka(3 брокера), один Zookeeper сервер и один реестр схем.

# Результат
Kafka brokers:  localhost:19092, localhost:29092, localhost:39092

Zookeeper: localhost:2181

Confluent Schema Registry: http://locahlost:8081

# Запуск и остановка

Запуск: `docker-compose up -d`

Остановка: `docker-compose stop`





