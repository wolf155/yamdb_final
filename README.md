![Yamdb_workflow](https://github.com/wolf155/yamdb_final/workflows/yamdb_workflow.yaml/badge.svg)

# api_yamdb
## **Как запустить проект:**
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/wolf155/infra_sp2
cd infra_sp2
```
Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
Для Win отдельно установить
```
pip install wheel
```


Выполнить миграции:

```
python3 manage.py migrate
```
Запустить проект:
```
python3 manage.py runserver
```

### Автор
Александр

### Лицензия
GPL
