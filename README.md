# be-ounce-admin
admin backend services
pip install django

django-admin startproject xxx

python manage.py runserver

python manage.py makemigration user

python manage.py migrate

pip freeze > requirements.txt
其他人可以通过以下命令安装依赖
pip install -r requirements.txt

pip install mysqlclient

pip install pymysql
测试数据库连接
python manage.py check