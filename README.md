# api_yamdbКак запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

git clone git@github.com:Gor-1/api_yamdb.git
cd api_yamdb
Cоздать и активировать виртуальное окружение:

python -m venv env
source venv/Scripts/activate
python -m pip install --upgrade pip
Установить зависимости из файла requirements.txt:

pip install -r requirements.txt
Выполнить миграции:

python3 manage.py makemigrations
python3 manage.py migrate
Запустить проект:

python3 manage.py runserver
