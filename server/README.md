## Сборка образа
### сначала собираем jar файл
mvn jar:jar
#### или кликаем на 
server/plugins/jar/jar:jar

### Собираем image
docker build -t chat-server:v1 .

### Запускаем в докере контейнер
docker run -d -p 8189:8189 --name chat-server chat-server:v1
