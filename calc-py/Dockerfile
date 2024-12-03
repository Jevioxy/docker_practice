# Используем минимальный образ Python
FROM python:alpine

# Указываем рабочую директорию внутри контейнера
WORKDIR /app

# Копируем файл calc.py в рабочую директорию
COPY calc.py /app/

# Указываем команду для запуска программы
CMD ["python", "calc.py"]
