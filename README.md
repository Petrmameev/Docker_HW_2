## Для запуска контейнера c backend-сервером:

1. Перейти в локальную директорию проекта

2. Собрать образ:

<code>bash docker build -t cicd .</code>


3. Запустить сборку:

<code>docker run --name cicd_server -d -p 8000:8000 cicd</code>
