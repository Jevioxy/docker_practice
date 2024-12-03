# Указываем базовый образ
FROM python:alpine

# Указываем рабочую директорию внутри контейнера
WORKDIR /testdir/python

# Копируем локальный файл test.py в контейнер
COPY test.py /testdir/python

# Задаём команду, которая будет выполняться при запуске контейнера
CMD ["python", "test.py"]
