# Используем минимальный образ OpenJDK
FROM openjdk:17-alpine

# Указываем рабочую директорию внутри контейнера
WORKDIR /testdir/java

# Копируем файл game.java в рабочую директорию
COPY game.java /testdir/java/

# Компилируем файл game.java
RUN javac game.java

# Запускаем скомпилированную программу
CMD ["java", "game"]
