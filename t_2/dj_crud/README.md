### Создание образа:
docker build ./ --tag=my_django

### Запуск контейнера:
docker run --name mydj -d -p 8000:8000 my_django