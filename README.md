# **Задача №2 - Докеризация приложения**

Нужно взять готовое приложение для контейнеризации db-api-for-docker.jar и упаковать в образ (т.е. создать Dockerfile и docker-compose.yml)

Общие условия:

1.  Приложению для работы нужна Java 8 (используйте в качестве базового образа openjdk:8-slim)
2.  Никаких внешних файлов, кроме самого jar-ника не требуется
3.  jar'ник запускается командой java -jar db-api-for-docker.jar и поднимает сервер на порту 9999 (для теста сделайте GET http://localhost:9999/api/cards)