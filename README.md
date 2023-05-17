# Проект по программной инженерии

Приложение использует модель (`deepset/roberta-base-squad2`), которая отвечает на вопросы по тексту на английском языке.    

Ссылка на используемую [модель](https://huggingface.co/deepset/roberta-base-squad2) 

Для запуска необходимо установить пакеты путём выполнения команды: `pip install -r requirements.txt`.  
И далее выполнить запуск приложения: `streamlit run app.py`    

Запуск тестов:  `pytest`    

Приложение также доступно по [ссылке](https://6boyz-project-practicum-app-rc363a.streamlit.app/)

Сборка докер контейнера: `docker build -t answers-to-questions .`

Запуск контейнера: `docker run -p 8501:8501 answers-to-questions`

## Описание проекта
Функция данного приложения заключается в ответе на произвольный вопрос по контексту на англ. языке

Цель учебного проекта: разработать Web приложение машинного обучения и развернуть его. <br>
Задачи:
* Выбрать модель, которая будет подходить для учебного проекта
* Выбрать площадку и инструменты для развертывания
* Разработать приложение
* Провести тесты
* Развернуть приложение
* Оформить репозиторий

Команда проекта: 
* [Мирвода Артем](https://github.com/Roccowen)
* [Сергеев Илья](https://github.com/allwanttokissme)
* [Шевляков Дмитрий](https://github.com/prettygodboi)
* [Касов Артем](https://github.com/A-Kasov)

# Пример работы:
![sol](https://user-images.githubusercontent.com/67365071/211650678-9ed0b304-f945-4ad7-86bc-1c37541eec9a.gif)
