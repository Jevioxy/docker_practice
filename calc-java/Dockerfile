FROM openjdk:17-jdk-slim

# Создаём рабочую директорию
WORKDIR /app

# Копируем всё содержимое текущей папки в контейнер
COPY . /app

# Компилируем Java-программу
RUN javac calc.java

# Указываем команду для запуска
CMD ["java", "calc"]
