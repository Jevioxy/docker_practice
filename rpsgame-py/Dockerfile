# Используем минимальный образ Python
FROM python:alpine

# Указываем рабочую директорию внутри контейнера
WORKDIR /testdir/python

# Копируем файл RockPaperScissorsGame.py в рабочую директорию
COPY RockPaperScissorsGame.py /testdir/python/

# Указываем команду для запуска программы
CMD ["python", "RockPaperScissorsGame.py"]
